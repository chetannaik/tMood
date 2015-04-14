# tMood 
###### A pebble app that analyses the sentiment of people around you using twitter feeds at your location.

[`IBM Alchemy API`](http://www.alchemyapi.com/) [`Twitter REST API`](https://dev.twitter.com/rest/public) [`Python Anywhere`](https://www.pythonanywhere.com)

#### Summary
This is the pebble app that we made during [bitcamp](http://bitca.mp/) hackathon. This repository contains code for the backend service. The code for the pebble app that uses this service is available [here](https://github.com/yiochen/tMood).

- The backend service is hosted in pythonanywhere.com and we are using flask web framework for handling requests.
- It accepts input requests in the form of a JSON array containing list of place names.
- This is then used to get the tweets around the list of places.
- We use sentiment classifier by IBM Alchemy to get the tweet sentiments.
- Then we randomly select 16 tweets along with their sentiments and return it in JSON format.

#### Team Members:
- Chetan Naik
- Yiou Chen
- Kavana Anand
- Jie Liang

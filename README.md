Hubot Weather
=========

Hubot script to show weather for some city.

# Installation

Add ```"hubot-weather":"*"``` in ```package.json``` file under dependencies.

Add ```"hubot-weather"``` in ```external-scripts.json``` file.

Run ```npm install``` command and you are ready to go!

Add environment variable `HUBOT_OWM_APIKEY` with API key to openweathermap [More info here](http://openweathermap.org/faq#error401).

#Example

```
hubot weather in Riga
```

Reply:

```
Forecast for today in Riga, LV
Condition: Clouds, broken clouds
Temperature (min / max): 12°C / 12°C
Humidity: 100%
Type: 1

Last updated: Mon Sep 29 2014 08:50:00 GMT+0300 (EEST)
```

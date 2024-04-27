# HomeAssistant

Links:
* https://github.com/Blueforcer/awtrix3


## Basic Setup

* prefer native installs over docker, since not all features are avialable in a common docker install
* add mosquitto MQTT server

## Ulanzi Control

  POST http://192.168.0.242/api/apps

```json
[
   {
      "name":"time",
      "show":true,
      "pos":3
   },
   {
      "name":"date",
		 "show":true,
      "pos":0
   },
   {
      "name":"Temperature",
		  "show":false,
      "pos":2
   },
   {
      "name":"Humidity",
      "show":false
   },
   {
      "name":"Battery",
      "show":false
   },
   {
      "name":"jeef_weather",
      "show":false,
      "pos":4
   },
   {
      "name":"calendar.daniel",
      "show":true
   },
   {
      "name":"weather.openweathermap",
      "show":true
   },
   {
      "name":"rain_forecast",
      "show":true
   }
]
```

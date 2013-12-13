Pebble Text Watch Plus
======================

This Pebble app provides the popular Text Watch watchface with a scroll text on the bottom.

Please make sure your Pebble is running firmware 2.0! If not? get it from: https://developer.getpebble.com/2/getting-started/

The scroll text will be set by this android app at set intervals.
Just make sure the url will return JSON output like:
```
 {"text":"<your text goes here>"}
```
I.e.
```
 {"text":"December 12, BTC/USD=903.95"}
```

Screenshots:<br>
![Android screenshot](http://jeroennijhof.nl/pebble/app.png)&nbsp;![Text watch screenshot](http://jeroennijhof.nl/pebble/pebble1.png)&nbsp;![Text watch screenshot](http://jeroennijhof.nl/pebble/pebble2.png)

The max text length supported is 115 characters.
We are working on a new version which will support 1k characters.

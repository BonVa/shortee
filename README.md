# shortee

## about
Shorten everything like URLs, long texts, and being able to get the original stuff.


You'll be able to deploy this as server, or just use it as a tool. 


DB will be required, if not it can still work for partial funcitons.

## Usage :
``` go 
shortUrl := shortee.DoUrl("www.exp.com/jack/maria/knife/flower", "t.jr.com") // may be something like "t.jr.com/2/U7"
shortText := shortee.DoText("whatever that's too long for your application to deal with...", "prefix") //may be something like "prefixWowSoShort"
```

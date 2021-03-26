# AQAAPP
source of app prototype APP for AQA sensor
### what can do AQA app ?
data and logs visualistation form serial monitor is better for AQA sensor and have some **colors** ;-) 
see more [here](https://gallery.appinventor.mit.edu/?galleryid=bdffdd3d-3b5b-49ba-bf7e-71ba9af0570e) 

you need use specify fireware like [AQAHC-06](https://github.com/unloquer/AQA/tree/AQAHC-06) 
you can implement into other AQA code 

### whats is important to implement

- Bluethoot, work with hc-06
- prints like pm25, data from dht, led colors like "verde , amarillo ,rojo"...
- use  9600 bauds

	  Serial.begin(9600);

see more [the commit](https://github.com/unloquer/AQA/commit/4bc40cee887f5f7a59355608a04a20cd2a0f3b10)
### i want to contribute
Thanks

you can export unloquer_AQA.aia in [mit app inventor](http://appinventor.mit.edu/)

we wait you contribution

###  common problems
Problem :never upload fireware and dont show error log
Solution :disconect hc-06 when you upload the fireware

# screenshots
![](http://wiki.unloquer.org/_media/personas/jero98772/screenshot_20210325-184344.png)

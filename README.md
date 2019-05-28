# Ev3Simulator


[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Ev3Simaulator is an easy solution for coding and debugging your ev3 pyhton script. 

  - Debugging
  - Codding
  - No need in actual ev3


### Installation

Ev3Simulator requars a pip and python to run.

Install the dependencies and devDependencies and start the server.

```sh
$ pip -install ev3simulator
```
### Components

* LargeMotor- the simulation of LargeMotor from basic ev3 Librery
* UltrasonicSensor- the simulation of UltrasonicSensor from basic ev3 Librery

### Use sample
This is the exaple how to creat the realisation of Largemotor class. It's absolutly the same as using LargeMotor in basic ev3 libery.
```sh
mL = LargeMotor("outA")
```
Things are getting trickier than you are adding an UltrasonicSensor.
You shoud yuse the add_wall method to add the start and finish coordinats of your wall. And of course you can set the angle between sensor and robot vector.
```sh
usR = UltrasonicSensor("in1", angle=-40)
usR.add_wall(x_start=0, y_start=60, x_finish=130, y_finish=60)
```

License
----

MIT


**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>

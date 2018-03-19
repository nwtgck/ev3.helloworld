# EV3 Hello World
[![Build Status](https://travis-ci.org/nwtgck/ev3.helloworld.svg?branch=master)](https://travis-ci.org/nwtgck/ev3.helloworld)

[LEGO Mindstorms EV3](https://www.lego.com/en-us/mindstorms/products/mindstorms-ev3-31313) Hello World in Scala

<table border="0">
  <tr>
    <td><a href="http://www.lejos.org/ev3.php">leJOS</a> </td>
    <td>0.8.1-beta</td>
  </tr>
  <tr>
    <td><a href="http://www.scala-lang.org">Scala</a> </td>
    <td>2.11</td>
  </tr>
</table>

## How to use

* install [leJOS](http://www.lejos.org/ev3.php) on EV3
* run `sbt assembly` to create executable `helloworld.jar` file
* connect EV3 via USB cable
* run `. deploy.sh` to deploy to EV3 Brick via USB connection
* on EV3 brick under leJOS select `Programs` > `helloworld.jar` > `Execute program`

![alt tag](https://www.dropbox.com/s/lqehwp246suddpr/2014-04-21%2022.44.54.jpg?raw=1)

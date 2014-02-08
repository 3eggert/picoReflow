picoReflow
==========

Turns a Raspberry Pi into a universal, web enabled Reflow Oven Controller.

![Image](https://apollo.open-resource.org/_media/mission:resources:picoreflow_webinterface.jpg)

Based on MAX 31855 Cold-Junction K-Type Thermocouple and Raspberry Pi GPIO driven Solid State Relays.


Python Requirements:

Gentoo:

  - dev-python/bottle
  - dev-python/gevent
  - dev-python/gevent-websocket


Raspbian:

sudo apt-get install python-dev libevent-dev
sudo pip install greenlet bottle gevent gevent-websocket


More info: https://apollo.open-resource.org/mission:resources:picoreflow

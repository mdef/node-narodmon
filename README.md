node for narodmon.ru project


node-red-node-narodmon
=====================

A <a href="http://nodered.org" target="_new">Node-RED</a> node to send data to <a href="http://narodmon.ru" target="_new">narodmon.ru</a>.

Install
-------

Run the following command in the root directory or in userDir (~./.node-red/) of your Node-RED install

        npm install mdef/node-narodmon



Usage
-----

Posts data to Narodmon.

Define mac in node settings.

The msg.payload Should contain formated part of the url like T1=24&T2=22 where T1 - name of the sensor and 24 sensors value.

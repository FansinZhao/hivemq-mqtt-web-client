hivemq-mqtt-web-client
======================

*update js file 原作者的项目有很久没有更新了，一些js脚本已经下载不了，我从 https://www.bootcdn.cn/ 更新了一下js脚本，项目可以正常运行了,并且增加了Docker使用方式*

## A websockets based MQTT Client for your browser.

This client runs on any modern browser, which supports websockets (sorry Internet Explorer <10!).
You can use it to publish and subscribe at the same time.

See it in action at [http://hivemq.com/demos/websocket-client/](http://www.hivemq.com/demos/websocket-client/ "MQTT Websocket Client")

## How to use it

Read the blog post about ["A full-featured MQTT client for your browser"](http://www.hivemq.com/full-featured-mqtt-client-browser/ "A full-featured MQTT client for your browser")



#### *Docker*

```
docker run -itd --rm -p 80:80 fansin/hivemq-mqtt-web-client
```

then visit  address`http://localhost/`, now , enjoy it. 



## Localhost / Local network

You can also use this client to connect to a broker on your local machine ("localhost") or any machine in your local network which is reachable from the machine which your browser runs on.



## MQTT Broker

This web client works perfectly with the [HiveMQ MQTT broker](https://www.hivemq.com/hivemq/ "HiveMQ MQTT Broker") with enabled websockets.

If you don’t like to use a self hosted (or locally running) HiveMQ, you can use the [public MQTT broker](http://www.hivemq.com/showcase/public-mqtt-broker/ "Public MQTT Server") from the [MQTTDashboard](http://www.mqttdashboard.com/ "MQTT Dashboard").

* Host: **broker.mqttdashboard.com**
* Websockets port: **8000**


## Why another MQTT Client

We at [HiveMQ](https://www.hivemq.com/ "HiveMQ") needed a quick and simple way to develop and test our applications which use MQTT over websockets, so we sat down for a few hours and built this client which also works for your local development machine.

## Can I embedd it / ship it with my software?

Sure! We would however be very glad if you would honor the work by linking to the original client source or mentioning that this websocket client was developed initially for HiveMQs websocket support. 

# Contributing

If you want to contribute to HiveMQ MQTT Web Client, see the [contribution guidelines](CONTRIBUTING.md).

# License

HiveMQ MQTT Web Client is licensed under the `APACHE LICENSE, VERSION 2.0`. A copy of the license can be found [here](LICENSE).


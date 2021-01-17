A websockets based MQTT Client for your browser.
This client runs on any modern browser, which supports websockets (sorry Internet Explorer <10!). You can use it to publish and subscribe at the same time.

See it in action at http://hivemq.com/demos/websocket-client/

How to use it
Read the blog post about "A full-featured MQTT client for your browser"

Docker
docker run -itd --rm -p 80:80 fansin/hivemq-mqtt-web-client
then visit addresshttp://localhost/, now , enjoy it.

Localhost / Local network
You can also use this client to connect to a broker on your local machine ("localhost") or any machine in your local network which is reachable from the machine which your browser runs on.

MQTT Broker
This web client works perfectly with the HiveMQ MQTT broker with enabled websockets.

If you don’t like to use a self hosted (or locally running) HiveMQ, you can use the public MQTT broker from the MQTTDashboard.

Host: broker.mqttdashboard.com
Websockets port: 8000
Why another MQTT Client
We at HiveMQ needed a quick and simple way to develop and test our applications which use MQTT over websockets, so we sat down for a few hours and built this client which also works for your local development machine.

Can I embedd it / ship it with my software?
Sure! We would however be very glad if you would honor the work by linking to the original client source or mentioning that this websocket client was developed initially for HiveMQs websocket support.

Contributing
If you want to contribute to HiveMQ MQTT Web Client, see the contribution guidelines.

License
HiveMQ MQTT Web Client is licensed under the APACHE LICENSE, VERSION 2.0. A copy of the license can be found here.


# palava.tv

[palava.tv](https://palava.tv) is a cost-free, simple to use, secure, and open source platform for video calls, built on top of the [WebRTC](https://webrtc.org/) technology.

## Bug Reports and Feature Requests

Please use this repository's issue system to notify us about bugs you encounter when using palava.tv: https://github.com/palavatv/palava/issues/new/choose

## The palava.tv Stack

The three main ingredients of palava.tv are the following:

Project | Description
--------|------------
[signaltower](https://github.com/palavatv/signaltower)* | The websocket endpoint which manages the meeting rooms, implemented in Elixir
[palava-web](https://github.com/palavatv/palava-web) | The Vue.js application that lets you access palava.tv
[palava-client](https://github.com/palavatv/palava-client) | The JavaScript library which communicates with the signaltower

*) The older Ruby-based [palava-machine](https://github.com/palavatv/palava-machine) is still available and functions as a drop-in replacement for the signaltower

## Setup your own palava.tv

Detailed instructions will follow soon. You can find an example nginx config file [here](https://github.com/palavatv/palava/blob/master/config/nginx/palava).

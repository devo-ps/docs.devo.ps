---
title: ZeroMQ
layout: page
links:
    - title: Official website
      url: http://zeromq.org/
configuration: {}
---
ØMQ (also spelled ZeroMQ, 0MQ or ZMQ) is a high-performance asynchronous messaging library aimed at use in scalable distributed or concurrent applications. It provides a message queue, but unlike message-oriented middleware, a ØMQ system can run without a dedicated message broker. The library is designed to have a familiar socket-style API.

ØMQ is developed by a large community of contributors, founded by iMatix, which holds the domain name and trademarks. There are third-party bindings for many popular programming languages.

## Configuration example

    services:
      zeromq: '*'
    configuration:
      zeromq: {}
Overview
--------

Stomp is the Simple (or Streaming) Text Orientated Messaging Protocol and
JMS is the Java Message Service (JMS) API which is a Java API for sending
messages between two or more clients. The STOMP-JMS project provides applications
a JMS client interface to the STOMP wire protocol.

Heartbeat
---------

The proposed implementation implements the STOMP 1.2 spec(http://stomp.github.io/stomp-specification-1.2.html#Heart-beating), and is configurable via the system property:

    -Dstompjms.heartbeat=X,Y

Reference
---------

* [JMS 1.1 Specification](http://java.sun.com/products/jms/docs.html)
* [STOMP 1.0 Specification](http://stomp.github.com/stomp-specification-1.0.html)


Immediate
----------

* Make tests run on all enabled transports
* Use setTimeout to make direct transport "async"

* Implement basic FBP protocol in msg
* Add collision detection for queue names,
at least warning. Mismatching datatypes on same names

Soon
-----

* Support for FBP components which we can only have one of in FBP protocol
* Ability to spawn participants from cordinator

Later
-----

* Handle disconnects/errors in MQTT and AMQP
* Add ability to directly ruote between queues for AMQP
* Move queue abstraction to separate library, for reuse in noflo-runtime etc
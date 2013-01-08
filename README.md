LeapRuby
==========

Leap integration with JRuby, with easy access to Leap's events.

## Setup

* Clone this directory (gem not setup yet)
* Install JRuby[http://jruby.org/getting-started].
* Get the latest version of the Leap SDK (0.7.0).
* Copy these files here: `cp /path/to/Leap/lib/{libLeap.dylib,lib_LeapJava.dylib,LeapJava.jar} .`
* Run the `Leap` background application
* Run `rake` to test the connection of your Leap (it will output simple info about each frame, and demonstrates how to listen for Leap events)

## Sample.rb

This is just a proof-of-concept "Hello World" that mimics the
`Sample.*` files in Leap SDK.

== Author

* Tieg Zaharia (github[http://github.com/tiegz])

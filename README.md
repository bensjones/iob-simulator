# iob-simulator
Web simulator for Internet of Buckets

# Background
Internet of buckets is a 10x5 grid of 5 gallon buckets that are addressable and change color by sending curl calls. Each
bucket is controlled by an esp8266. There is only 1 internet of buckets and it takes time to setup and so it can be a
challenge to build and test things to drive the internet of bucket. The iob-simulator allows people to test stuff without
having to have everything setup.

# Using the iob-simulator

Using the simulator is as easy as making a curl call to a url with specific params

params:

* bucketPos (int) bucket location from top left of a 10x5 grid.
* program (string) program to run. Options are:
    * ocean
    * vapor
    * spinner
    * rainbow
    * bonfire
    * ctrlh
    * circle
    * tron
    * kinect
* programParams (string) params to pass to the program


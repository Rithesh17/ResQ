# ResQ
An android application designed for communication between rescuers and victims during natural disasters.

### Situation
* This application is a post-disaster management Android application, that is, the region of use is already struck with a disaster.
* There is no communcation network in the region. Hence conventional methods for calling rescuers cannot be employed.

### Solution Proposed
* We will be employing network-free communication approach to tackle the problem.
* The application will be of two parts - one for the victims of disaster and the other for the rescuers.
* The solution is as follows:
  * The rescuers will broadcast a message within the disaster region.
  * The application at the victim's end within the area will capture the signal sent by the rescuers and reply back with a SOS message.
  * The rescuers will recieve the message from the victim, identify the location of the victim and rescue him.

### Implementational complications
* Which communication medium to use, now the network is down? (Bluetooth, Infrared, etc.)
* How to get the location of the victim?
* Can you make the application of the victim to act as a repeater of the messages (so that the range of communication can be increased)?

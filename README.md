# Ticker


Ticker is a Java library meant to help users utilize timers easily, without going through the proccess of creating timers and timertasks. 
To use, download .jar file included here and import into your Java project.

Here are the following methods avaibile to call:

Ticker.create(int k)                Creates a new timer, parameter specifies how many milliseconds in between each tick.
Ticker.tick()                       Simulates a timer tick; useful when put into loops.
Ticker.stop()                       Cancels the current timer.

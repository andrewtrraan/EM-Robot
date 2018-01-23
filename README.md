# EM-Robot

An Electromagnet Robot that picks up scrap pieces of metal. The robot combines, Arduino, Raspberry Pi with Python and Java in order to move around, move the magents up and down, energize/deenergize the magnets, and to sense if an object is too close and stops. 


Python was utilized in two different ways in order for the robot to be controlled remotely:

<ul>

  <li>Wireless keybaord method which used Pygame and read what keys were pressed and sent certain serial bits to the Arduino to allow the robot to perform certain commands</li> 
  <li>Java app method which had the app send web requests to a Flask server that sent certain serail bits to the Arduino and in turn allow the robot to perform certain commands.</li>
</ul>

Arduino was utilized by:

<ul>
  <li>Energzing and de-energizing the electromagnets to pick up the scrap pieces of metal</li>
  <li>Control the motor control boards that allowed the robot to move</ul>
    <li>Control the servo motors that moved the arms up and down</li>
</ul>

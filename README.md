# power-distribution-board
The main purpose of power distribution board is to distribute power from LiPo battery to other electrical component (such as servo motor, single board computer, microcontroller, etc) safely. This board is used by Gladiatos Team from University of Indonesia Robotics Team.

<h1>Powerdist Version 1.0</h1>
Powerdist version 1.0 was made with the addition of two features, i.e. overvoltage protection and overcurrent protection. Overvoltage protection circuit consist of bipolar junction transistor for switching device and zener diode as a regulator device. Then, fuse is used for overcurrent protection to prevent high current damaging other component.

<br>![1](https://user-images.githubusercontent.com/65435469/204571328-1184fc5b-2867-441f-a05e-d578bcf7d121.PNG)
![2](https://user-images.githubusercontent.com/65435469/204571347-c9ff644c-06c0-4e51-b3bb-c2a1eb6b4ce7.PNG)

<h1>Powerdist Version 2.0</h1>
Powerdist version 2.0 is the simplified version of the powerdist version 1.0. In this version, there is no overvoltage protection circuit because the voltage from LiPo battery is already stabilized by buck boost converter.

<br>![3](https://user-images.githubusercontent.com/65435469/204571365-fe694ebb-dfe3-4a91-b858-cea61e1a796e.PNG)
![4](https://user-images.githubusercontent.com/65435469/204571374-54455dbb-e269-41ff-9265-348152640edc.PNG)

# Music Synthesizer

This repository contains code for the Envison Project Music Synthesizer

In the recent years efforts have been made to synthesize music using computers instead of musical 
instruments. These efforts have led to creation of algorithms which can be used to make sound of musical instruments. One such algorithm is the Karplus strong algorithm. This algorithm can produce sound of stringed instruments like guitar. It mimics the mechanics of the string of a stringed instrument. In this project we have used this algorithm in two different ways.  

We call the two different ways as hardware implementation and software implementation. The two folders named Hardware implementation and Software implementation contain intructions provided by the mentors and codes written by the mentees for the corresponding implementation. 

## Software implementation method 

The Karplus Strong algorithm has been executed using the python language. The focus in this method was to write efficient python code for the algorithm. The Software implementation folder contains two folders Instructions and Code_by_mentees and a file best_results.wav. The Code_by_mentees folder contains the programs written by the mentees using the instructions file in the instruction folder. The file best_result.wav is the best sound we got using the different codes.


## Hardware implementation method
In this method we have used the Verilog language to implement the Karplus Strong algorithm. The verilog code was written based on the following block diagram.

Delay line and filter were first implemented as independent modules.Later, these modules were put together in the main module.  
The hardware implementation folder contains three folders Filter, Delay line and Main design. Each folder contains two files,the design file and testbench file. The design file contains program for the design of the component and testbench contains code for the verification of that design.   

## Team Members

* Dharanadeeran 
* Nakul
* Nihar
* Saathwik

## Mentors

* Sujay
* Moha

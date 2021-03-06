# Implementation of TCP-Jersey in ns-3
## Course Code: CS821
## Assignment: #2

### Overview

TCP-Jersey [1] is a variant of TCP, It makes TCP to perform better in wireless and wired-wireless hybrid networks environment 
by differentiating the packet losses caused by network congestions from the losses caused by wireless link errors. This repository
provides an implementation of TCP-Jersey in ns-3 [2].

You can also find pseudocode for TCP-Jersey [here](https://github.com/ShefaliGups11/Implementation-of-TCP-Jersey-in-ns-3/wiki/TCP-Jersey).

### TCP-Jersey Faireness Example

An example program is provided for evaluation of TCP-Jersy fairness as compared to other well known TCPS in

` src/example/tcp/jersey-fairness.cc `

and can be executed as follows:

` ./waf --run examples/tcp/jersey-fairness `

### References:

[1] Xu, Kai, Ye Tian, and Nirwan Ansari. "TCP-Jersey for wireless IP communications." IEEE Journal on selected areas in communications 22.4 (2004): 747-756.

[2] https://www.nsnam.org/ns-3-dev/

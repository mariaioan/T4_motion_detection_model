# T4_motion_detection_model

In this repository I implement a motion detection model for the direction selective cell T4 in the _Drosophila_ visual system. 
This model is published by Zavatone-Veth et al., 2020 and here I implement it in python as part of my master's module at JGU, Mainz.

Figure 1 of the main reference is completed and can be replicated via the script Figure_1.
The functions used in every script are in the script fig1_functions_latest.

Possible improvements:
In Fugure 2B the amplitudes of the calcium responses are wrong and have different kind of resposnes than the published paper.
Moreover, in Figure 2C the amplitudes are also wrong possibly propagating some earlier bug in the code. 

The code for spatiotemporal tuning in Figure 2C is slow, and could be more efficient. 
In order to do so, we'd need to first change all functions in fig1_functions_latest
to receive arrays instead of singular pairs of values.That way we could ommit the nested for loops and have a faster code.


# Circuit-Simulation
Circuit Simulation using eSim and Sky Water 130nm pdk

Design and Analysis of SR Flipflop:

SR Flipflop Is designed using Esim and 130 nm Technology. only NMOS and CMOS are used in the designing.
In the waveform S and R are the inputs and also CLK is also given. Based on the input, output Q and Qbar will changes. 
The input states set and reset 1 is an undesirable or invalid condition and that state must be avoided. 
If both the S and R inputs are 0 then the output wont change.  it will follow the pervious one.

while executing I didnt get the output later i came to know that i missed to keep sky130 pdk in same workspace.
So keep sky130 pdk in the same folder as .cir file . To run and get waveform run .cir.out file in ngspice.
for design of circuit i  refered the  circuit from the reference paper and the design is got expected output.
and final waveform is also matched with the refernce  waveform except some small fluctuations.
![Design and Analysis of SR Flipflop waveform](https://user-images.githubusercontent.com/67550103/130239278-be9751ae-b19a-478a-b9e1-16ca91d2a559.png)
![Design and Analysis of SR Flipflop circut ](https://user-images.githubusercontent.com/67550103/130239284-bba9cecc-fdd1-4e3e-895a-e0a3f423a88d.png)

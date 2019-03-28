# Communication-project
Digital Communications Matlab-Simulink Project



## BPSK modulation scheme

#### Explanation

**Binary Phase Shift Keying** (BPSK) is a two phase modulation scheme, where the 0’s and 1’s in a binary message are represented by two different phase states in the carrier signal: ?=0? for binary 1 and ?=180? for binary 0.
This is also called as 2-phase PSK or Phase Reversal Keying.

Using the Random Integer Generator as a source to generate a random sequence of binary bits, then **BPSK** modulated signal is transmitted through Additive White Gaussian Noise (AWGN) channel where a noise is add to signal and after reception of base band signal some error is found (Pe). It is compared the input binary sequence and demodulated output by using error rate calculator block.

#### Set of instructions

* First, set the block parameters of Random Integer Generator
* Make sure that all blocks are connected
* Adding constellation diagrams before and after the noise
* Adding simout block and change variable name to ber, limit data points to last:2 and save format as 2D-array
* Then, write in terminal bertool, plot Theoretical BER with modulation type PSK and order of 2, use this to compare with.
* Monte carlo Eb/No is ranging from -10 to 10 dB, then browse the file .slx, add ber variable name then Run

#### Scatter Plot

##### before noise at Transmitter

![Image of Yaktocat](https://Dalia-mohamed98.github.com/images/yaktocat.png)
 

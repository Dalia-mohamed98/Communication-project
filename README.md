# Communication-project
Digital Communications Matlab-Simulink Project



## BPSK modulation scheme

#### Explanation


**Binary Phase Shift Keying** (BPSK) is a two phase modulation scheme, where the 0’s and 1’s in a binary message are represented by two different phase states in the carrier signal: ?=0? for binary 1 and ?=180? for binary 0.

**Binary Phase Shift Keying** (BPSK) is a two phase modulation scheme, where the 0â€™s and 1â€™s in a binary message are represented by two different phase states in the carrier signal: Î¸=0âˆ˜ for binary 1 and Î¸=180âˆ˜ for binary 0.

This is also called as 2-phase PSK or Phase Reversal Keying.

Using the Random Integer Generator as a source to generate a random sequence of binary bits, then **BPSK** modulated signal is transmitted through Additive White Gaussian Noise (AWGN) channel where a noise is add to signal and after reception of base band signal some error is found (Pe). It is compared the input binary sequence and demodulated output by using error rate calculator block.

#### Set of instructions


* First, set the block parameters of Random Integer Generator
* Make sure that all blocks are connected
* Adding constellation diagrams before and after the noise
* Adding simout block and change variable name to ber, limit data points to last:2 and save format as 2D-array
* Then, write in terminal bertool, plot Theoretical BER with modulation type PSK and order of 2, use this to compare with.

* First, set the size parameter of Random Integer Generator to 2
* Make sure that all blocks are connected
* Adding constellation diagrams before and after the noise
* Adding simout block and change variable name to ber, limit data points to last:2 and save format as 2D-array
* Then, write in terminal bertool, plot Theoretical BER with modulation type **PSK** and order of 2, use this to compare with.

* Monte carlo Eb/No is ranging from -10 to 10 dB, then browse the file .slx, add ber variable name then Run

#### Scatter Plot

##### before noise at Transmitter


![Image of Yaktocat](https://Dalia-mohamed98.github.com/images/yaktocat.png)
 

![ScatterImage of BPSK before noise](/figures/BPSK_before.png)
 
##### after noise at Reciever

![ScatterImage of BPSK after noise](/figures/BPSK_after.png)
 
#### BER performance figure
![BER figure](/fig/BPSK.fig)



## QPSK modulation scheme

#### Explanation

**Quadrature Phase Shift Keying** (QPSK) is a form of Phase Shift Keying in which two bits are modulated at once, selecting one of four possible carrier phase shifts (0, 90, 180, or 270 degrees).
QPSK allows the signal to carry twice as much information as ordinary PSK using the same bandwidth.

Using the Random Integer Generator as a source to generate a random sequence of binary bits, then **QPSK** modulated signal is transmitted through Additive White Gaussian Noise (AWGN) channel where a noise is add to signal and after reception of base band signal some error is found (Pe). It is compared the input binary sequence and demodulated output by using error rate calculator block.

#### Set of instructions

* First, set the size parameter of Random Integer Generator to 4
* Make sure that all blocks are connected
* Adding constellation diagrams before and after the noise
* Adding simout block and change variable name to ber, limit data points to last:2 and save format as 2D-array
* Then, write in terminal bertool, plot Theoretical BER with modulation type **PSK** and order of 4, use this to compare with.
* Monte carlo Eb/No is ranging from -10 to 10 dB, then browse the file .slx, add ber variable name then Run

#### Scatter Plot

##### before noise at Transmitter

![ScatterImage of QPSK before noise](/figures/QPSK_before.png)
 
##### after noise at Reciever

![ScatterImage of QPSK after noise](/figures/QPSK_after.png)
 
#### BER performance figure
![BER figure](/fig/QPSK.fig)


## FSK modulation scheme

#### Explanation

**Frequency Phase Shift Keying** (FSK) is a frequency modulation scheme in which digital information is transmitted through discrete frequency changes of a carrier signal. In general, FSK is a nonlinear digital modulation method.

Using the Random Integer Generator as a source to generate a random sequence of binary bits, then **FSK** modulated signal is transmitted through Additive White Gaussian Noise (AWGN) channel where a noise is add to signal and after reception of base band signal some error is found (Pe). It is compared the input binary sequence and demodulated output by using error rate calculator block.

#### Set of instructions

* First, set the size parameter of Random Integer Generator to 8
* Make sure that all blocks are connected
* Adding constellation diagrams before and after the noise
* Adding simout block and change variable name to ber, limit data points to last:2 and save format as 2D-array
* Then, write in terminal bertool, plot Theoretical BER with modulation type **FSK** and order of 8, use this to compare with.
* Monte carlo Eb/No is ranging from -10 to 10 dB, then browse the file .slx, add ber variable name then Run

#### Scatter Plot

##### before noise at Transmitter

![ScatterImage of FSK before noise](/figures/FSK_before.png)
 
##### after noise at Reciever

![ScatterImage of FSK after noise](/figures/FSK_after.png)
 
#### BER performance figure
![BER figure](/figures/BER.png)



## QAM-16 modulation scheme

#### Explanation

**Quadrature amplitude modulation** (QAM) conveys two bit streams by changing the amplitude of two carrier waves that have the same frequency and a 90Â° shift. The most common type of QAM modulation is rectangular QAM, were the constellation points are arranged in a square grid.
In QAM system,two amplitude-modulated (AM) signals are combined into a single channel.

Using the Random Integer Generator as a source to generate a random sequence of binary bits, then **QAM** modulated signal is transmitted through Additive White Gaussian Noise (AWGN) channel where a noise is add to signal and after reception of base band signal some error is found (Pe). It is compared the input binary sequence and demodulated output by using error rate calculator block.

#### Set of instructions

* First, set the size parameter of Random Integer Generator to 16
* Make sure that all blocks are connected
* Adding constellation diagrams before and after the noise
* Adding simout block and change variable name to ber, limit data points to last:2 and save format as 2D-array
* Then, write in terminal bertool, plot Theoretical BER with modulation type **QAM** and order of 16, use this to compare with.
* Monte carlo Eb/No is ranging from -10 to 10 dB, then browse the file .slx, add ber variable name then Run

#### Scatter Plot

##### before noise at Transmitter

![ScatterImage of QAM-16 before noise](/figures/QAM16_before.png)
 
##### after noise at Reciever

![ScatterImage of QAM-16 after noise](/figures/QAM16_after.png)
 
#### BER performance figure
![BER figure](/figures/BER.png)



## QAM-64 modulation scheme

#### Explanation

**Quadrature amplitude modulation** (QAM) conveys two bit streams by changing the amplitude of two carrier waves that have the same frequency and a 90Â° shift. The most common type of QAM modulation is rectangular QAM, were the constellation points are arranged in a square grid.
In QAM system,two amplitude-modulated (AM) signals are combined into a single channel.

Using the Random Integer Generator as a source to generate a random sequence of binary bits, then **QAM** modulated signal is transmitted through Additive White Gaussian Noise (AWGN) channel where a noise is add to signal and after reception of base band signal some error is found (Pe). It is compared the input binary sequence and demodulated output by using error rate calculator block.

#### Set of instructions

* First, set the size parameter of Random Integer Generator to 64
* Make sure that all blocks are connected
* Adding constellation diagrams before and after the noise
* Adding simout block and change variable name to ber, limit data points to last:2 and save format as 2D-array
* Then, write in terminal bertool, plot Theoretical BER with modulation type **QAM** and order of 64, use this to compare with.
* Monte carlo Eb/No is ranging from -10 to 10 dB, then browse the file .slx, add ber variable name then Run

#### Scatter Plot

##### before noise at Transmitter

![ScatterImage of QAM-64 before noise](/figures/QAM64_before.png)
 
##### after noise at Reciever

![ScatterImage of QAM-64 after noise](/figures/QAM64_after.png)
 
#### BER performance figure
![BER figure](/figures/BER.png)


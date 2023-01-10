# Yin Pitch Tracking
### Implementation of the Yin pitch detection algorithm in pure C

## Author
[Ashok Fernandez](https://github.com/ashokfernandez/)

## Acknowledgements

Thanks to [JorenSix](https://github.com/JorenSix/) for the original C++ implementation


## Description

The [YIN algorithm](http://audition.ens.fr/adc/pdf/2002_JASA_YIN.pdf) is a popular algorithm for tracking pitch (or the fundamental frequecy) of a monophonic audio signal. This project is an implementation of the Yin algorithm in C, suitable for embedded systems.

The code was ported to C from C++ from the [The Pidato Experiment](https://github.com/JorenSix/Pidato). The Pidato project was originally written for the Arduino platform, hence the C++. This is an attempt to port the algorithm implemented in the Pidato project to a more generic module in pure C, and has been used sucessfully in both embedded systems and high level applications. The Pidato Experiment is licensed under the GNU LGPL v3 license agreement.

Furthermore, the Pidato Experiment code was based on [The TarsosDSP Project](https://github.com/JorenSix/TarsosDSP) which has no license. TarsosDSP is developed at University College Ghent, Faculty of Music. See [TarsosDSP README](https://github.com/JorenSix/TarsosDSP/blob/master/README.textile) for further information.

Some information about TarsosDSP can be found in the paper TarsosDSP, a Real-Time Audio Processing Framework in Java, by Joren Six, Olmo Cornelis, and Marc Leman, in Proceedings of the 53rd AES Conference (AES 53rd), 2014. If you use TarsosDSP in academic research, please cite this paper.

# **Concept of IQ Signal**
The term “I/Q” is an abbreviation for “in-phase” and “quadrature.”

They form the basis of complex RF signal modulation and demodulation, both in hardware and in software, as well as in complex signal analysis, “quadrature” applied to both a signal and the modulation/demodulation techniques associated with that signal.

>The term “I/Q” is also used to describe the format of the data that is used to represent a complex signal. The I/Q data format is used in many applications, including software-defined radio (SDR), digital radio, and digital television.

 By convention, the I signal is a cosine waveform, and the Q signal is a sine waveform. As you know, a sine wave (without any additional phase) is shifted by 90° relative to a cosine wave.

The I/Q signal is a complex signal, which means that it is a signal that has both a magnitude and a phase. The magnitude of the I/Q signal is the same as the magnitude of the original signal, and the phase of the I/Q signal is the same as the phase of the original signal.
- The first thing to understand about I/Q signals is that they are always amplitude-modulated, not frequency- or phase-modulated. However, I/Q amplitude modulation is different from the AM technique discussed in Chapter 4: in an I/Q modulator, the signals that modulate the I/Q sinusoids are not shifted such that they are always positive. In other words, I/Q modulation involves multiplying I/Q waveforms by modulating signals that can have negative voltage values, and consequently the “amplitude” modulation can result in a 180° phase shift. 
- The second thing to understand about I/Q signals is that they are always complex signals. In other words, they have both a magnitude and a phase. The magnitude of the I/Q signal is the same as the magnitude of the original signal, and the phase of the I/Q signal is the same as the phase of the original signal.

***
>The signal can be described as a function of time by the following equation:
```
            V(t) = A * sin (2 * π * f * t + Ф)

            where:

                        A: is the peak amplitude

                        f: is the frequency

                        t: is time

                        Ф: is the phase shift
```
***

![IQ img](https://www.tek.com/-/media/sites/default/files/u811871/what20iq20image205.png)

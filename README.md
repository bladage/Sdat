# Sdat - Software Defined Audio Testing
## A GNU Radio Application to Measure the Quality of Audio Devices

The thesis represents a system concept which determines quality indicators of audio devices.
It is implemented by GNU Radio, but the concept is described in a way that other software
and hardware can realize this system, too. 

The considered indicators are the tranfer function,
the signal-to-noise ratio (SNR), the total harmonic distortion (THD), the gain, and the linear
dynamic range (LDR) of audio equipment. The presented implementation uses the sound card
of a personal computer (PC) as a measuring instrument. The input of the device under test
(DUT) is connected to the sound card’s output and the DUT’s output is wired to the sound card’s
input. This approach is a black-box testing method. For example, equipment like amplifiers,
equalizers, mixing consoles, filters, crossover networks, and analog-to-digital (A/D) or digital-to-
analog converters (D/A) can be inspected. However, the following test concepts are not adequate
for the perceived audio quality of devices which uses low bit rate coding schemes. In addition,
the system has got a signal generator, a data logger for the quality indicators, an adjustable
digital input filter, and a time domain and frequency domain display of the output and input
signals.

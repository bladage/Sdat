# Sdat - Software Defined Audio Testing
## A GNU Radio Application to Measure the Quality of Audio Devices

![Sdat](https://user-images.githubusercontent.com/51378715/155023860-69fc6134-5d5b-47a6-b15f-be6d85821699.png)

### Features:
- Based on: GNU Radio Companion v3.8.5.0-5-g982205bd and Python 3.6.9
- Signal generator: sine, rectangle, saw tooth, triangle, frequency sweeps
- Adjustable quantization of the signals
- Time scope and FFT spectrum
- SNR, THD+N, gain measurements
- Data logger which creates CSV-files
- Adjustable digital input filter
- Black-box testing via the PC's sound card:
![system](https://user-images.githubusercontent.com/51378715/155024382-dd0fc359-0a77-4605-b7cb-5d8efdfc4f64.png)

## There is a thesis (Project Work) which discusses the application / system concept in detail:
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





# IEEE QCE 2025

Demos for https://qce.quantum.ieee.org/2025/tutorials-abstracts/#tut08.

## Hardware configuration

Install daughtercards as follows:

DAC daughtercards:
* RF out, 1st slot (ports 4-7)
* Balun ("simplified") out, 2nd slot (ports 8-11)
* DC out, 3rd slot (ports 12-15)

ADC daughtercards:
* DC in, 0th slot (ports 0-1)
* RF in, 2nd slot (ports 4-5)
* Balun ("simplified") in, 3rd slot (ports 6-7)

Cables:
* DAC port 12 -> ADC port 0
* DAC port 13 -> ADC port 1
* DAC port 4 -> ADC port 5, with 40 dB attenuation
* DAC port 5 -> ADC port 4, with 40 dB attenuation
* DAC port 8 -> ADC port 6

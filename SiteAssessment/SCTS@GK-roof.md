# Spectral Analysis for SCTS @ Gisbert-Kapp
This document is for the Sutton-Coldfield Transmitting Station (SCTS) information and measurements.  

## SCTS Channels

  ![Figure caption/alt text](..\Images\Tx\SCTS\Digital_TV_Signals.png "Figure caption/alt text")
  
## Measurements

### Spectral Analysis w/ Dipole @ Gisbert-Kapp Roof (2024-06-13)
![GKroof 350-450MHz](../Images/SpecAnalyser/FSH3/BlackDipole/GKroof 350-450MHz.png)

![GKroof 380-400MHz.png](../Images/SpecAnalyser/FSH3/BlackDipole/GKroof 380-400MHz.png)

### Spectral Analysis /w Log-Harmonic @ 328 Lab Preparation
The Yagi-Uda antenna is first characterised using the VNA between 300MHz-1GHz. 
Observed -20dB insertion loss with $S_{11}$ between 400MHz - 1GHz.
The (Joe's) Patch Antenna (below) performed better than the Yagi-Uda in indoors in the well sheilded Rm328.
![Rm329 550-750.jpg](../Images/SpecAnalyser/Other/YagiUda/Rm329 550-750.jpg)
 
### Spectral Analysis /w Reference Dipole @ Gisbert-Kapp Roof (2024-06-18)
Failed to observe more than 5dB above noise floor of any signal between 400-1GHz, which leads us to suspect that the antenna is faulty. [^1]

![Roof Side.jpg](../Images/Kit/LogHarmonic/Roof Side.jpg)![Roof Out.jpg](../Images/Kit/LogHarmonic/Roof Out.jpg)
This was confirmed with the check of using the small reference dipole antenna and otherwise identical setup. 
![GKroof Ref. Dipole 600-800MHz](../Images/SpecAnalyser/FSH3/RefDipole/GKroof1 600-800.jpg "GKroof Ref. Dipole 600-800MHz")
This revealed many DVB-T peaks at -57dBm, 15-20dB above the noise floor. This achieved with a small reference dipole promisies about 25dB SNR surveillance channel with a properly setup, high gain antenna.

| Found        | Frequency | $P_t$ | SNR |
|:------------:|:---------:|:-----:|:---:|
| NO           | 618.166   | 200kW |     |
| NO           | 626.166   | 200kW |     |
| YES          | 642       | 200kW | 20  |
| YES - Weaker | 650       | 200kW | 15  |
| NO           | 666       | 200kW |     |
| YES          | 674       | 200kW | 20  |
| YES          | 690       | 200kW | 20  |

Comparing the peaks of "GKroof Ref. Dipole 600-800MHz", it appears that not all of the expected signals are being measured. (Perform a full peak comparison using better sweeps and antenna later.) Perhaps the wikipedia article is out of date.

### Repairing and Characterising Yagi-Uda (2024-06-18...)
Found Large Yagi-Uda in old Gisbert-Kapp stock room. 
Required repairs or updates required: 

- [ ] Find F-Type connector to N- and SMA type. **Characterised Loss is = ...**
- [ ] Re-attach reflector.
- [ ] Align teeth uniformly. **Characterised BandWidth = ...**

== TODO | Place all charactisation of components into a separate document== 

[^1]: Images show antenna in vertical mode. Horizontal orientation was attempted and did not improve results noticably. The tripod requires a fix to hold it upright in horizontal. Need to fix for the fixed-up Yagi-Uda to try next.
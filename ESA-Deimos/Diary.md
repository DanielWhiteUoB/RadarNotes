# May 2024 
## 22nd May, Wednesday 
### Met Matias Rittatore (Vid)
First meeting with Mike took place. Video call with [Matias Rittatore](https://www.linkedin.com/in/matias-rittatore/), project manager of this project, at Deimos. There will be another meeting 10th June.

### Established Technical Baseline (Due 5th) 
For approx _June 5th_, we have to put together the ETB. This is the first technical assessment and proposal that will show the price, lead time, technical abilities etc of the radar capability side of the project.

### PDR (need to check) 
For approx late _June 22nd_, the PDR will be shared.  
== Mike will be gone this month (Rome) == 
There will be an in-person meeting at Deimos with this. Further details need to be checked in the project documents.

### Tasks 
**Established Technical Baseline. Due 5th June (2 Weeks)** 
First task, to summarise the technical components and specifications, cost and lead time for the items required for the device. This will be written in the file [s0_ETB](./s0_ETB.md).  

- [ ] **Hardware**
    - [x] USRP (Coherent, 2 Channels), (<700MHz, >16MHz Bandwidth, 12 bits)
    - [ ] BPF (ask Joe)
    - [ ] LNA (ask Joe)
    - [ ] Antennas (High Directional Gain)
        - [ ] Patch antenna (ask Joe)
        - [ ] Yagi-Uda
    
- [ ] **Signal Processing**
    - [ ] Range Doppler Maps (Using the direct tx signal)
    - [ ] Detector (CFAR)
    
- [ ] **Training**
    - [ ] Passive Radar Basics (RRE, Range compression, Velocity Measurements)
    - [ ] Spectral Analysis forpassive radar in an enviornment (Learn Spectrum Analysier)

**Familiarise with essential radio equipment** 
This to be performed in the Birmingham enviornment at first, then repeated in Greece (in June) 

- [x] Get a handle on Spectrum Analyser (SA)
    - [ ] Record Data to Disk
    - [ ] Get and attach a 7000MHz antenna
    - [x] Work with Battery Power

# June 2024
## 28th June, Friday
Meeting with only Mike and Chris. Shared updates in the following areas, each with the following todos:
### RRE Simulation
The simulation tool is useful but requires some better mathematical understanding before this is ready.
For example, bandwidth features in noise power, kTFB - however, this will cancel at a later stage as the FFT is taking place. 
 Therefore, we need to create a full SNR calculator that will inform of the gain through the entier system and processing. 
 This will then enable the display of the range and Doppler resolution, which are as important to understand as operational range.
 There is also a bit more to understand about the noise figure, was directed to Stimson + Baker's "Airborne Radar", but this was not found to contain anything too useful yet
 Other take-a-ways were more straightforward:
- [ ]  Use 10dB losses, not 5dB
- [ ]  Don't try to use the full Rx Amplifier Gain, keep it low, and otherwise consider more the gain of the antenna to be used.
- [ ]  Coherent integration is flexible, but usually done _per-Symbol_. The Symbol rate leads to fast time. Usually in a QAM regieme for DVB-T.
- [ ]  In UK, transmitter gain is summarised in EIRP = $G_t * L_{cables} * P_t$, so gain and power are packaged together. 
### SCTS Measurements
Repeat measurements with a stand and a new Yagi-Uda that will be bought from Maplin.
- [ ] Buy a Yagi-Uda from Maplin 
With these we will get a proper measurement of the 600-700MHz where we expect to see our Transmitted signals.
### Greece Travel
With insurance, decide upon shipping it over.
- [ ] Find a PO box / Mike's friends address to send to
- [ ] Fit new battery and learn how to change the battery
- [ ] Book a UPS/DHL with collection from Goods Outward.
### USRP Procurement
Reach out to Acounts Payable as the first port of call.

- [ ] Hardware 

- [ ] Power Budget 

- [ ] Signal Processor | Cross-cor, followed by CFAR

- [ ] Eg Measurement

40km < distance, 

# July 2024
## 18th July, Thursday | 1st Bi-Weekly Consortium Meeting
First of the Bi-Weekly meetings about to take place.
The first (v1.0) version of the technial baseline was shared feedback was:

### Tasks
Rename, Hardware requirements -> Hardware components 
Before carfeul with "requirement"

Don't state that it actually arrived

This will be done post a site visit, assess the exact need. PBF and LNA 

APPROXIMATIONS ARE GOING TO REFINED IN THE FUTURE
_________
mEMORANDUM, some etb information in the next milestone, maybe 8th - not sure but will submit document
3.1-2 (Varified Detail Design).  4.1.2 Implementation and Varification plan

ESA may say, we need to check withthem  before physical doing somehting.

Output 5 - physical work 

Meeting at 3, July 1st.

## 26th July, Friday | Weekly meeting
Barrety Power for USRP ,
14Bits * 16MHz  = 
* 2
### October 
* More body into overview we present before
* More aobut detail how the downconversion happens
* Signal processing, cfar in depth.
* SNR, PD / PFA
* Joe and Ali has done simulation.
* Antenna -> ADC - Basic Equations -> Range -Dpppler map, SNR -> PD and Pfa
* Weekly update.

## 1st August, Thursday | Mike back!

To send out copmplete rid on monday

  Early septemer - present etb - get feedback. (PDR PM3)
  End of september, submit detailed deisgn (26th) - 2 weeks later DDR (10th Oct)
  Implementation + test_varification  plan - hand in hand 
  How to test requiremnest for the subsystem, tables - each table check everything, and how to test. 
  2 separate docs 
   
# 9th September | Post Summer
- [ ]  Order a new Garmin
- [x]  Did Nuoshi Receipt
- [x]  New Usb-c PSU for laptop #
- [x]  Another Oscillator
- [ ]  Pigeion Rings
    - [ ]  Temp password for rings
## Detailed Design Review
Questions I have:
- The BFP Joe used will not fully attenuate the other channels (650MHz). The LNA also will amplify these signals. Is this sufficient, or does an additional low pass filter need to remove higher channels. Can the other channels be filtered out in DSP?

ToDos:
-[] Risk Assessment (technical) , to maybe be incorperated into powerpoint. 
-[] koint trials at UoB

-[] uobradar -  is there any email validation required

# 24 September
Pre DDR Meeting
mention ntergration
demonstrating can detect
if they pusth - what value?
then can sent warnings to the ir system. (queueing the continuous zoom functionality)

## Meeting 24th Milestone
### DDR
UHF Siwtch for multiple antenna directions
Andrea to check if offline only or also online
### VIP
...

### points ot take home
online or off line - check workpagckages - andrea o check him self
ADS-B
mqtt format
BONN Conference




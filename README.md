# MeetingNotes
ToDo list and Meetings

## ToDo List After DDR+VIP

- [x] Get insurance claim confirmed
- [ ] Buy replacement SpecAnal
- [ ] Make post about insurance + travel
- [ ] Get access to room 228
- [x] Buy a M350 Case from HeliGuy
- [ ] Go to GK storage and find case for PCLsystem
- [x] Get 2 more network switches
- [ ] Buy ADSB Reciever for real time FlightRadar24 information
- [ ] With Alan remove a shelf so we can fit the new drone in the shelf 
- [ ] Pulse train into USRP for pseudo-RDmap
    - [x] Demo PNA to create pulse train
    - [ ] Signal Generator downstrairs (AWG) at Majeeb's desk (mini lab)
    - [ ] Generate Range-Doppler map
- [x] Label the New shelves - adran shelf 0
- [x] EMSIG Manchester 17th
    - [x] Make a poster
    - [x] Print Posters
    - [x] Book travel 
- [x] Share glasgow data
- [x] 18th Deal with Reviewer Comments
- [x] Operate Pigeon tags on UoB radar 

First to sent baseband

### 2024 October 4th

Check what the maximum 1.3xNyquist can be offered by USRP  

Get 8MHz bandwidth pulses (ie any signal at 8MHz bandwidth, easiest to achieve with pulses.), use this to check integrity of recorded data.

Convert 8MHz bandiwdth pulses into range-Doppler map. Ignore the duty cycle - accept ambiguities

Bernie Mulgew - DSP book - a must read.

### 2024 Oct 11th
Light after the week getting the VMP, DDD, VVR and ICD done.
We are looking to confirm by the end of the next week the need for interface chassis. if the data rate is enough…

### 2024 Oct 19th (Post EMSIG Manchester)

Shared the confusion of 8MHz bandwidth pulses - may have come to a resolution in latest (last PNA pulses data).

  Pulse rectangular
  vs pulse at carrier
  Do 1MHz nw pulses
### ESA 
- [x] More information on the fov of the antenna - an estiamte - some number-
- [ ]  actual installation of the ground station, where is the computer going
- [x]  double check reaction time discussio is enough with checking against IR system

- RIDS DD
- [x]  losses to be broken down to component [DDR]
- [x]  define medium aircraft - discrepancy of 10dB [ETB]
- [x]  reaction time update - [DDR]
- [x]  power budget discussion - [ETB]
- [ ]  further mission context and site installation [DDR]
   
    - DDR first if possible - not a big deal
   
    - by 13th - to reshape
 
    - see sidelobes at 13 dB - squares!!!
  - why the spike at the beginning of recording!
  - remove dc offset, check if dC offset withn nyquis generated
  - see DBV-T roof

### Last Before Christmas   
- [x] Ask Matias What is the next milestaone and when
**Sure, the next milestone (DDR/PM4) will focus on the Detailed Design and Implementation and Verification Plan documents (Outputs 3 and 4) we submitted. We plan to have this milestone as early as possible next year, so we will share with you a presentation and let you know as soon as we have a date for the meeting.
The next deliverable (Output 5) is the Campaign Report that will include results from the Implementation (WP5100) and Testing (WP5200) work packages, but it is only due for Progress Meeting 6 (no deliverable is expected for PM5).**
For the passive measurements, in matlab, test,...:
- [ ] that autocorrelation of the ref signal has no delay (wrt cable delta that does seem to exist with comarison of both channels)
- [ ] whats the delay with cable
- [ ] Perform fft of frequency-dim of DVB-T to observe range ambiguities
- [ ] Perform fft of time-dim (and see internal DVB-T pulses) to see Doppler ambiguities
- [ ] Thus produce ambiguity function (auto) of the signal channel recorded
- [ ] Secondly produce ambiguity function of cross-corelated signals (see target amb fun at target location, and also see delay between channels)

#### Deimos Questions from UoB legal
- [ ] What is the purposes of the laser.
- [ ] Export control to other counties, what is 
Amelia Petch - get it on her radar
- [ ] Academic excemption - if the usrp is not going to given to them afterwards ???
Agreement between ESA + Deimos & Deimos + UoB?
#### 2nd Legal Meeting 
- [ ] Academic exemption not a thing!
- [ ] Ameli, we will give this to Demios, then tehy to ESA
- [ ] Indirect export - still requires a licence.
- [ ] Open licence - regular thing. not a UoB thing - no open licence.
- [ ] Or induvidual licence - takes mote time (few months.) Requires other party to sign a declaration.
First thing. What we intend to send is export control.

- [ ] Are we bloddy giving them the thing

**Is this absolutley export control**?
Yes to give to Demios - then they require to give to ESA and follow all the rules.
More aobut the technology.
Consultant to check what type of licence.
//
Outcomes and deliverables - in relation to the SDR. We give it to you in UK.
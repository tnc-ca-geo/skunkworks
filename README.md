# Santa Cruz Island camera trap project
Repo for tracking hardware experimental design related decisions

## Experiement
Falk and Natty are returning to SCI from May 11th - May 17th to deploy and experiement with wireless camera trap technologies. The primary camera trap types that we will test are Buckeye x80 series wireless mesh cameras, but we will also test a home-brewed camera that Falk built with edge detection and LoRa transmission.

### Buckeye range test - Base station at Christy Ranch
Test the limits of line-of-sight range between the buckeye base station and a daisy chain of camera-nodes. Deploy the base station at Christy Ranch or ME on the ridge above Christy Ranch with largest antenna (64", 9 dBi), and begin to stretch the daisy chain of camera nodes out towards Frasier point as far as we can without losing connectivity. Start by putting the smallest antenna on the first node, and walking it out until we lose connection. Make note of that distance. Swap out the antenna for the next size up and repeat. 

Questions to address:
- How far can we stretch a daisy-chain of 3 cameras under line-of-sight conditions?
- What antenna sizes/types work best for what conditions? How much futher range does each step-up in antenna size offer?
- Battery consumption at the repeater nodes. Because they need to pass along data sent from the nodes further afield, they consume a lot more power than the edge node. Will the solar power be sufficient to keep them charged?

### Buckeye ravine test - Base station at Valley Peak
Test the ability to transmit data out of cameras in deep ravines. Place base station on Valley Peak, and experiment with nodes across the valley (North face of South Ridge, West of Airstrip to west of Matanza Rd. turn off from valley road) and directly below VP the ridge on the same ridge (South face of North Ridge, drainage immediately below Valley Peak pointing towards airstrip).

Questions to address:
- What camera network configurations work best for extracting data from deep ravines (repeater node on the ridgeline above the ravines)?
- How does moisture affect RSSI (does it change at night)?
- Test various antennas

### DIY camera test - Centinela 
Set up DIY camera next to the Reconyx at Centinela.

Questions to address:
- Compare performance against Reconyx

### Semi-long-period deployment - Valley Peak
Set up solar-powered base station in pelican case before leaving the island. Return in ~August to assess. Consider moving base station equiptment into more permanent location if it's worth keeping (put all base station equiptment in enclosure, run antenna wire through coduit and attach 64" antenna to mast). 

## Notes from 2-26-20 meeting on SCI
https://docs.google.com/document/d/1gqQZCy-rV4UjYXB1cllBlSssOAxyQhM5_CWcgJNn5F4/edit#

## Equiptment list
https://docs.google.com/spreadsheets/d/1Y59Wla3ryUnkFdNU66Q8Dl6yeSXOZLOLcA5l4gTSJTI/edit?usp=sharing

## Related repos
- Animl base program      http://github.com/tnc-ca-geo/animl-base
- Animl lambda function   http://github.com/tnc-ca-geo/animl-lambda
- Animl ML resources      http://github.com/tnc-ca-geo/animl-ml
- Animl desktop app       https://github.com/tnc-ca-geo/animl-desktop
- Animl platform          https://github.com/tnc-ca-geo/animl

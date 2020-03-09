# sci-cameratrap-project
Repo for tracking hardware experimental design related decisions

## Experiement
Falk and Natty are returning to SCI from May 11th - May 17th to deploy and experiement with wireless camera trap technologies. The primary camera trap types that we will test are Buckeye x80 series wireless mesh cameras, but we will also test a home-brewed camera that Falk built with edge detection and LoRa transmission.

### Buckeye range test - Base station at Christy Ranch
Test the limits of line-of-sight range between the buckeye base station and a daisy chain of camera-nodes. Deploy the base station at Christy Ranch or ME on the ridge above Christy Ranch, and stretch the daisy chain of camera nodes out towards Frasier point as far as we can without losing connectivity.

Questions to address:
- How far can we stretch a daisy-chain of cameras under line-of-sight conditions?
- Battery consumption at the repeater nodes. Because they need to pass along data sent from the nodes further afield, they consume a lot more power than the edge node. Will the solar power be sufficient to keep them charged?

### Buckeye ravine test - Base station at Valley Peak
Test the ability to transmit data out of cameras in deep ravines. Place base station on Valley Peak, and experiment with nodes across the valley (North face of South Ridge, West of Airstrip to west of Matanza Rd. turn off from valley road) and directly below VP the ridge on the same ridge (South face of North Ridge, drainage immediately below Valley Peak pointing towards airstrip).

Questions to address:
- What camera network configurations work best for extracting data from deep ravines?
- How does moisture affect RSSI (does it change at night)?
- Test various antennas

### DIY camera test - Centinela 
Set up DIY camera next to the Reconyx at Centinela.

Questions to address:
- Compare performance against Reconyx

### Longer-period deployment - Valley Peak
Set up base station in small metal enclosure on VP mast before leaving the island. TBD how long we'll leave it set up. 

## Notes from 2-26-20 meeting on SCI
https://docs.google.com/document/d/1gqQZCy-rV4UjYXB1cllBlSssOAxyQhM5_CWcgJNn5F4/edit#

## Equiptment list
https://docs.google.com/spreadsheets/d/1Y59Wla3ryUnkFdNU66Q8Dl6yeSXOZLOLcA5l4gTSJTI/edit?usp=sharing

## Related repos
- Animl lambda function - github.com/tnc-ca-geo/animl-lambda
- Animl platform - https://github.com/tnc-ca-geo/animl

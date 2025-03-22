## Marge - Observing SIP and RTP

This is the main repository for marge, a observability system designed for Telecom providers.

It aims to be an open source alternative to Voipmonitor and it takes inspirantion in OCOM using the well known Homer as a base willing to provide KPIs, statistics and better troubleshooting and understanding of your network. It acts as a centralized server with distributed agents capturing packets in a vendor agnostic way.

We're extending a bit the HEPv3 protocol and changing how the Homer essentially works for this job so, if you don't use the docker-compose provided within this repo keep in mind to install the Heplify agent and server that we have forked, they're submodules of this repo.

---------------------------------------------------------

### How it Started
I started working as a network administrator in a huge SIP provider that didn't have OCOM nor voipmonitor in that time, it became a nightmare for me to troubleshoot and see things the way I were used so with my dev and observability background I've thought to myself it would be a little fun to implement something, discovered Homer and did cool things that my coworkers kinda loved so here I am starting this open-source platform for those who may strugle with the same things.  

### What I look for with it?
Implement end to end monitoring in a SIP environment with an easy to use, plug and play installation. It will probably include some 5G needs like Diameter.
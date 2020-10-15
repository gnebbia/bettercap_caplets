# A collection of bettercap caplets


- arpspoof (check out the target IP for a more targeted poisoning)
- hstshijack (note, we should substitute the default one in bettercap with this one)


The bin/ directory contains the working version of bettercap.

Note that we may need to launch it by using:

    locate libpcap
    cp libpcap.0.so.whatever libpcapwhatevertheoldbettercapwants
    sudo LD_PRELOAD=libpcapwhatevertheoldbettercapwants ./bettercap

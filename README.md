# DC-Electronic-Load
Digitally controlled dc electronic load.  

The core idea is to use multiple smaller low cost MOSFETs in parallel instead of a single higher device to cut costs.
Since the current through a semiconductor has a positive temperature coefficient this presents a novel engineering challenge because an unsuitable design could risk a thermal runaway event where a single transistor would handle increasingly larger currents until failure. To prevent such a catastrophic event a circuit to ensure equal current distribution is implemented.  

The instrument should feature a constant current, voltage and power modes. Over voltage and current protection is also desired.

This project was originally started in Eagle ECAD on 28.05.2019 but never implemented.
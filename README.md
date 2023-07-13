# DC-Electronic-Load
Digitally controlled dc electronic load.  

To cut costs, the core idea is to use multiple smaller low-cost MOSFETs in parallel instead of a single higher-power device.
Since the current through a semiconductor has a positive temperature coefficient this presents a novel engineering challenge. An unsuitable design could risk a thermal runaway event where a single transistor would handle increasingly larger currents until failure. To prevent such a catastrophic event a circuit to ensure equal current distribution is implemented.  

The instrument should feature constant current, voltage and power modes. Over-voltage and current protection is also desired.

This project was initially started in Eagle ECAD on 28.05.2019 but was never implemented.

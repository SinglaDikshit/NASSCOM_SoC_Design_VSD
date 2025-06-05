# SKY130 DAY 3: Design Library Cell Using Magic Layout and NGSPICE characterisation

### IO placer revision

OpenLANE configurations can be changed inside the shell itself, on the fly. IO Mode is usually set to random equidistant. However, if we want to change this, we can do so through the following command typed after floorplan : set ::env(FP_IO_MODE) 2. After running this command, the IO [input - output] pins will not be equidistant in mode 2 (instead of the default - that is 1).

> NOTE: changing the configuration on the fly will not change the runs/config.tcl, the configuration will only be available on the current session.

## Labs for CMOS Inverter NGSPICE Simulations



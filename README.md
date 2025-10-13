# SPID-RAS-modification
Addition of absolute encoders for SPID RAS antenna rotator

Well known and widely used SPID ( http://spid.net.pl/en/ ) RAS azimuth-elevation antenna rotators have an incremental encoder built into them. This means that the actual position of the rotator can be lost by the controller. Additionally, in the basic configuration, the rotator is capable of only one degree of resolution (which is more than enough for most cases).
This project adds absolute encoders for azimuth and elevation to the aforementioned rotator. For azimuth, magnetic encoder AS5600 is used, for elevation an accelerometer will be used.
The project requires some mechanical skills, as partial disassembly of the device is required, along with access to tools such as spanners and a hammer. One part has to be turned on the lathe or 3D printed. A reasonable degree of precision is required. Additionally, some soldering and basic electronic skills are needed as well. 
Detailed description (in polish) can be found on SP2ZIE club webpage: http://sp2zie.pl/index.php/per-radio-ad-astra-ii/137-modyfikacja-rotora-spid-ras

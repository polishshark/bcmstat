#Changelog

##Version 0.1.4 (14/02/2014)
* Add: Display peak IRQ, RX and TX values when terminating bcmstat.sh with ctrl-c

##Version 0.1.3 (13/02/2014)
* Chg: Use `vcgencmd get_mem gpu` and `vcgencmd get_mem arm` to calculate GPU/ARM split, and total available RAM.

##Version 0.1.2 (09/02/2014)
* Detect XBian

##Version 0.1.1 (26/01/2014)
* Add: Include "SwUse" (Swap Used %) in memory statistics if swap memory is enabled

##Version 0.1.0 (25/01/2014)
* Add: Include Swap allocation (if swap is enabled) in summary information

##Version 0.0.9 (23/01/2014)
* Fix: Show correct Core/SDRAM frequency when not overclocked (or when underclocked)
* Add: Min/Max H264 frequency

##Version 0.0.8 (21/01/2014)
* Chg: Small change to filter on interface data, making it less likely to be ambiguous
* Chg: Improve interface name validation

##Version 0.0.7 (06/01/2014)
* Chg: Tweak Raspbmc/Raspbian identification

##Version 0.0.6 (05/01/2014)
* Initial github release
* Add: Add self-update options (V, U, F, C)

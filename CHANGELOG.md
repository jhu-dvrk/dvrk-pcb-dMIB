CHANGELOG
=========

Rev B (1/30/2013)
=================
* Initial release

Rev D (6/4/2014)
================
* Changed gender changers from F-M to F-F
* Changed QLA header from latch to screw locks
* Added jumper wire for ECM Slave_Clutch (jumping K3 to R3)

Rev E (4/27/2015)
=================
* Added ECM switch update: J8C-K connected to J8C-R (i.e., K3 to R3)
* Bipolar Footpedal support: J24.3 connected to ground (bipolar return)
* Extra signals on J24:
  * VCC-CON-BJ to J24.15
  * ENCI+8J to J24.14
  * ENCI-8J to J24.9
* Added headers for pluggable jumpers J39, J40, J41
* Added input filters for ENC8 A/B on J23: C17, C18, R71, R72

Rev F (9/24/2018)
=================
* Added support for instrument one-wire interface
  * Added U17, J42, J43
  * Jumper J42 1-2 and J43 1-2 for direct connection from QLA to 1 wire interface
  * Jumper J42 2-3 and J43 open to use 1-wire transceiver

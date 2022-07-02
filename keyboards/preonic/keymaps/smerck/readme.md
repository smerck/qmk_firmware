# Notable changes

From the default preonic layout, these are the notable changes.

* Removed capslock and added escape
* Added hyper modtap to escape and quote. 
* Added shift/enter for right shift.
* Removed colemak/dvorak layers
* Added pipe to default layout

# building

make preonic/rev3_drop:smerck

# flashing

Put keyboard into bootloader mode and run

qmk flash -kb preonic/rev3_drop -km smerck

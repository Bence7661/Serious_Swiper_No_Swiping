# Swiper No Swiping
When you remove the PSU from an armor you the batteries in it are "refunded" if the power level is above 100 (because 100 stays on the suit).

## Features
If you have batteries in your inventory that are not 100% then the refunding process won't necessarily create new batteries.  
First it will look through your inventory and see if you have any batteries that it can "recharge" thus avoiding having 1000 batteries that are all below 100%

Swapping a power supply respects the newly inserted power supply's capacity.
This means that if your equipped PSU had a max capacity of 250 and was charged to 250 then swapping it out to a PSU that has a max cap of 100 will set the supply to 100 and refund 150 batteries.
Swapping it out to a bigger capacity PSU will preserve the current charge (so the new PSU will be at 250 power level already).

As Charlie would say:
> That's about it. See ya!

## Installation
Just install with MO2. Priority does not matter.

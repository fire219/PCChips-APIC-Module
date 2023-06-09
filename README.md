
# PCChips APIC Module
### Make your M720 slightly less useless!

The [PCChips M720](https://theretroweb.com/motherboards/s/pcchips-m720) is a dual [Slot 1](https://en.wikipedia.org/wiki/Slot_1) motherboard that doesn't necessarily run dual CPUs.

In all their cost-cutting wisdom, a needed component was left off the board -- the Intel 82093AA [APIC](https://en.wikipedia.org/wiki/Advanced_Programmable_Interrupt_Controller), which handles interrupt routing between multiple processors. Instead, they added a card slot for a module that houses the APIC. Without it, the M720 is just an incredibly mediocre Slot 1 motherboard. And in the modern day, most of the examples you find for sale don't have the module included.

If you're one of those poor souls to have a module-less M720, here's your chance to fix that.

![Module front](/images/modfront.png)
![Module back](/images/modback.png)

This is a re-engineered module that should fit in the existing slot, with a few changes made to make it easier to hand-solder together. All that you need is:

* This PCB ([JLCPCB can fab it for cheap](https://jlcpcb.com/))
* The S82093AA APIC (check eBay or Aliexpress)
* 4x 4.7kΩ resistors (1206 size)
* 4x 100nF capacitors (1206 size)

#### Compatible boards:
* PCChips M720
* PCChips M720II
* Amptron PII-2200A
* Amptron PII-2200B
* Alton ALTN-7020
* PC Ware MB-720
* EURONE EM-7020

#### License:

    Copyright (c) 2023 Matthew Petry (fireTwoOneNine)
    
    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.
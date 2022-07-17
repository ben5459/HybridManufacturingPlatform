# Voron-Toolchanger

Development Methodology:
Pragmatic
 
What it is:


What it isn't:
	Lighter than the stock Voron toolhead
	Cheaper than the stock Voron toolhead
	Designed to mill anything that you cant extrude out of the attached hotends
	

Design Requirements:
	Repeatable: <50micron
	Reliable:
	Safe: 

Use Cases:
	Multi-Color
	Multi-Material
	Speed Optimization 
	Hybrid Process 
		Additive + Subtractive


System Layout:
Automatic Tool Changer (ATC)
->
Tool Holder 
-> 
Tool (ex. Stealthburner with Clockwork2)


Features:
	Able to detect the current state of the lock mechanism. 
	Able to detect a fault in the locking mechanism (neither slider switch is triggered).
	Able to detect crashes that are not recoverable.
	Electrical connection between toolheads is rated for up to 1,000,000 cycles. 
	Compatible with two and three pin probes.

- [X] Develop a kinematic coupling
- [X] Develop lock/unlock mechanism 
- [X] Test lock/unlock mechanism
- [ ] Tool Maintenance
- [ ] Tool Alignment 
- [ ] 




Pinout: 
1: 5V
2: GND
3: Probe
4: X Limit - NC (Bottom)
5: Slider Left - NC (Bottom)
6: Slider Right - NC (Bottom)
7: Tool Contact 
8: 24V



Omron D2GW Series Sealed Ultra Subminiature Basic Switch

D2F-01L-D
*D2F-01 (100k operations min vs 30k for D2F models)
*None: Pin Plunger
*L: Hinge Lever
*D: Compact solder terminals

Frequently Asked Questions:
Q:
A:

Q:
A:

Q:
A:

Q:
A:

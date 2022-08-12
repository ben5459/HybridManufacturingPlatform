# Wireless Automatic Toolchanger

![Toolchange GIF](Automatic Tool Changer/Images/Toolchange GIF.gif)


## Highlights:
#### - Wireless - No cables or wires need to be connected to the X carriage. 
#### - Intelligence built in - Lock engaged/disengaged status and tool attached/detached status reporting.
#### - Designed for a heated environment - All components are rated for continuous use at 85C or higher.
#### - Reliable - Reduced components that can fail (steppers, servos, torque plates, etc)
#### - Convenient - Tools are stored at the front.
#### - True kinematic coupling- Design complies with the maxwell criteria.

## Development Methodology:
<details><summary>CLICK ME</summary>
<p>		
- Pragmatic product management <br />	
- Continuous improvement <br />
- Sound engineering theory supported by empirical testing <br />
 </p>
</details>

## What it is:
- Compact
- Lightweight
- Extensible
- Wireless
- 
 
## What it isn't:
- Lighter than the stock Voron toolhead
- Cheaper than the stock Voron toolhead	
- Designed to mill anything that you can't extrude out of the attached hotends
	
 
## Design Requirements:
- Repeatable: <50micron
- Reliable: >100k Cycles
- Safe: Able to detect lock states and tool crashes

## Current Specifications:
<details><summary>CLICK ME</summary>
<p>

#### - ATC Weight: 75grams <br />	
#### - ATC Footprint: 68x62x35 <br />	
#### - Operating temperature: ≤85C (all components are rated for atleast 85C) <br />  

#### - Recomended Maximum Tool Width (without modifications): 62mm <br />
#### - Recomended Maximum Tool Height (without modifications): 145mm <br />
#### - Recomended Maximum Tool Depth (without modifications): 76mm <br />
 
 
#### - Number of tool changes between maintenance intervals based on component service life: >100k <br />
 
 
#### Weight required in the Z axis to separate the kinematic coupling: <br />
##### - Locked state >5000g (over the amount that I can currently measure)  <br />
##### - Unlocked state 1750g +/-100g (connection state change occured before full decoupling) <br />
 
 
#### - Weight of a stealthburner with rapido, EBB36, and kinematic motor plate: 395g  <br />

</p>
</details>





## Use Cases:
#### Multi-Color	
#### Multi-Material
#### Speed Optimization 
#### Hybrid Process 
###### Additive + Subtractive


## System Layout:
```mermaid
graph TD;
    1[Automatic Tool Changer]-->2[Toolhead];
    2[Toolhead]-->3[Tool Holder];
    2[Toolhead]-->4[Tool ex. Stealthburner with Clockwork];
```




## Features:
- True kinematic coupling that complies with the maxwell criteria.
- Able to detect the current state of the lock mechanism. 
- Able to detect a fault in the locking mechanism (neither slider switch is triggered).
- Able to detect crashes that are not recoverable.
- Electrical connection between toolheads is rated for up to 1,000,000 cycles. 
- Compatible with two and three pin probes.

## Milestones:
- [X] Kinematic coupling development
- [X] Lock/unlock mechanism development
- [X] Test lock/unlock mechanism
- [ ] Tool Maintenance
- [ ] Tool Alignment 


## Frequently Asked Questions:
**Q:** SmCo magnets have a TwMax of 250-350C. Why are you using NdFeB magnets? <br /> 
**A:** Our custom NdFeB magnets have an energy density 30% higher than SmCo magnets while still offering a TwMax of 150C. <br />

**Q:** <br />
**A:** <br />

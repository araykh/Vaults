#  Sputtering Protocol 

## Loading the sample: 
### Pumping load lock to atmosphere: 
- Load lock & main chamber should be pumped down when you walk in. Toggle the load lock switch on "Pumpdown" 

![](Pasted%20image%2020210125192310.png){#id .class width=250 height=250px}
![](Pasted%20image%2020210125192332.png){#id .class width=200 height=200px}

- Nitrogen will start slowly pumping into the load lock and bringing it up to atmosphere. At about ~$7.5 \times 10^{-2}$ Torr, you should be able to take the lid off of the load lock. 

### Loading the sample: 
- Clean under the lid and the vacuum seal with your hand to get rid of any dust. Place the lid 
- Load the sample onto the chuck - either with tape or the screwed-on pins. Make sure there are two pins on opposite ends of each other, they will need to fit into the chamber. The orientation should look like this:
![](Pasted%20image%2020210125192808.png){#id .class width=200 height=200px}



### Pumping back to vacuum: 
- Toggle the load lock switch again to pump it down to vacuum.

![](Pasted image 20210125192332.png){#id .class width=200 height=200px}


## Setting up the main chamber: 
- Once load lock is within one order of magnitude of the main chamber, open the gate valve. 

 ![](Pasted%20image%2020210125192942.png){#id .class width=200 height=100px}
 
Relevant pressure sensors: 

![](Pasted%20image%2020210125193014.png){#id .class width=130 height=150px}

![](Pasted%20image%2020210125193027.png){#id .class width=280 height=90px}

**Setting up the main chamber: (continued)** 

- Move the black cylindrical handle up to the line. This may take some messing with. This is located directly above the black pressure sensor pictured above. 
	- At this point, the sample will be in the main chamber. We need to lower the arm of the main chamber to pick up the sample to get ready to sputter. 
	
### Lowering the arm: 
- Because of the way we alligned the chuck, we should be able to see a notch through the main chamber window. 
- Turn the knob to lower it down until you see it above the chuck. Align a tooth with the notch you see in the window. 


![](Pasted%20image%2020210125193223.png){#id .class width=200 height=200px}


### Locking it in place and lifting the arm: 
- Once the notch and the tooth are aligned, lower the arm until it is in the groove of the chuck. 
	- If it doesn't lower properly, immediately raise the arm back up, and move it to try to realign. 
- Once the teeth are in the groove, turn the arm to lock it in place, and lift the chuck out of the chamber. 
- Move the sample chamber back into load lock by moving the cylinder back out. Then close the main chamber valve. 
- At this point, start the rotating mechanism. 


![](Pasted%20image%2020210125193750.png){#id .class width=200 height=200px}


## Beginning Deposition: 
### Triple check to make sure all of the electronics are correct. 
- RF2 should be connected to Gun 1. Gun 1 holds SiO2, and is the shutter you will open to strike SiO2 plasma. 
- DC3 should be connected to Gun 6, which holds Titanium.


 ![](Pasted%20image%2020210125193259.png){#id .class width=200 height=300px}


### Striking the Plasma: 
- The main chamber should be on "OPEN" 


 ![](Pasted%20image%2020210125193350.png){#id .class width=200 height=200px}
 ![](Pasted%20image%2020210125193409.png){#id .class width=200 height=200px}

 
- Turn on the Argon gas at a setpoint of 20 *(Not sure of units)* and **wait for the pressure to increase to 45mTorr, and turn the gas off!** Do NOT turn away from it while this is happening. It is quick.




#### If you are doing Ti first, do this. If you are doing SiO2 first, skip this step. 
- DC3, unlike RF2, does not need to be ramped on slowly. Turn it to **300W** (In my case here, that's 40% of the 750W total supply), and set the time to **10 seconds**
- Once it is powered on, the plasma should have striked. Open the shutter. 
- Immediately turn the gas **on** again, and press "THROTTLE"

![](Pasted%20image%2020210125193527.png){#id .class width=200 height=200px}

- Wait for 4 minutes, which should deposit ~40nm of Ti. (According to an old log entry)
- Once the 4 minutes are over, first close the shutter, then just turn the power supply off. 
- **The deposition rate is roughly 10nm/minute**
- To do Ti, then sputter, simply close the shutter on Ti, turn off the gun, and move on to the SiO2 step. 

#### Power supply glitch
- In my case, the DC3 power supply was glitched. If you tried to turn on a glitched power supply, wait until the gun tries to power on and fails to strike plasma. At this point, turn the power supply off and back on with the switch. 
Power supply switch:

![](Pasted%20image%2020210125193459.png){#id .class width=200 height=300px}
![](Pasted%20image%2020210125193442.png){#id .class width=200 height=300px}

#### SiO2 Step: 
*If you were not going to do Ti, you should skip to here. If you just finished Ti, you should continue here.*
- On RF2, enter 60s ramp time first, **then** enter 67% into the power level. Press enter, and the time will start ticking down. Plasma should strike, indicated by the blue light next to the "ON" button on the computer. 


![](Pasted%20image%2020210125193612.png){#id .class width=200 height=300px}

- For SiO2, open the shutter on Gun 1 by clicking the big circular green button


![](Pasted%20image%2020210125193653.png){#id .class width=200 height=300px}

- Once the power is fully on, and the plasma has struck, turn the gas on again and immediately press "THROTTLE" This is the beginning of the deposition.


![](Pasted%20image%2020210125193712.png){#id .class width=200 height=300px}

- **The deposition rate is roughly 0.8nm/minute**
- After deposition, simply close the shutter, enter a time of 60s, and **then** press 0% power. It should time itself and power off. 

## Removing Sample 
- Shut the Argon gas off, and wait on throttle until it reaches ~0.5mTorr. Then open the main chamber valve. 
- Turn the rotating mechanism off. 
- Once the pressure drops to ~$10^{-7}$Torr, list the spindle to ~12, and then open the main valve.
- Insert the rod, as you did to begin the process, and lower it into the sample holder. Turn the chuck to unlock it from the arm, and lift the arm back up. The chuck should not follow it. 
- If the chuck remains on the sample chamber, you're done! Simply take the sample back into the load lock, close the main chamber gate valve, and pump load lock back up to room pressure. Take the lid off, remove your sample, put the lid back on and pump it back down to vacuum. 




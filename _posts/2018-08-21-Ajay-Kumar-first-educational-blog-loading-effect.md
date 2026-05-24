---
layout: post
title: "Loading Effect of a Multimeter!"

date: 2018-08-21
---

(Theory and Experiment)
## Background:
I have seen my students struggle to get study materials related with certain topics. In fact, I myself have found difficulty in finding enough materials. So, I decided to write about it on the basis of their needs and my experiences. I hope it helps them in some way or other. Please excuse me for naive english mistakes. Any sort of feedback or suggestions/corrections are more than welcome. 

### Theory:

Multimeter is an electronic device which helps us to measure a number of physical parameters such as Resistance, Current, Potential difference etc. 

### Multimeter as voltmeter:
In case when multimeter is used as a voltage measuring device, it can be called a voltmeter. Please note that voltmeter is always connected in parallel to the load resistance across which we want to measure the voltage drop.  When we want to measure voltage (potential difference) across any load resistance, it is desired that the internal resistance (Impedance) of voltmeter should be much larger than  load resistance.  If it's not so, the effective circuit resistance is altered and hence, working of the circuit is changed. This leads to an inappropriate reading. 

 This can be also understood in terms of change of current in the circuit. When a voltmeter with internal resistance comparable or less than load resistance is connected across a load resistance, the voltmeter acts as a shunt (low resistance path for current). Note that the current always takes a low resistance path, which means that the current which was passing through load resistance will be reduced as its large portion will pass through the voltmeter. 
 
 Either way, we can understand that the voltage drop across load resistance will drop. And hence, the voltmeter will give a reading which is not correct i.e. as expected voltage drop across load resistance when no voltmeter was connected in the circuit.
 


<img src="https://github.com/ajaykumar649/ajaykumar649.github.io/blob/master/_posts/loading1.png" width="300">

#### credit: Drawn using edraw max.
---





#### Multimeter as Ammeter:

In case when the multimeter is used as a current measuring device, it can be called a **Ammeter**. Please note that the Ammeter is always connected in series to the load resistance branch in which we want to measure current. When we want to measure current in the circuit, it is desired that the internal resistance of the ammeter is very low compared to the load resistance across which we want to measure current.  If it's not so, then the circuit resistance will be altered and working of circuit will change.

This can be also understood in terms of change in voltage drop across load resistance as there will be significant voltage drop across ammeter.  

Either way, the current passing through the load resistance will be reduced and hence, the current reading on ammeter will be less than expected when there was no ammeter connected.
<img src="https://github.com/ajaykumar649/ajaykumar649.github.io/blob/master/_posts/loading3.png" width="400">
#### credit: Drawn using edraw max.

---

#### Conclusion:
We find that when the multimeter is used as either a voltmeter or ammeter, its reading is altered/inaccurate, not as expected. So, we can say that some amount of voltage or current has been loaded^[longnote] on the measuring device. **This is called loading effect**.


^[longnote]: [Meaning of Load: Load is anything which takes energy from the system. In electronics, resistance behaves as a load which takes energy from the circuit. Every device has some resistance, so does the multimeter. Hence, it also takes some amount of energy (either in terms of current or voltage) from the system.]




Some of the references which help me to make sense:

https://harshithg.wordpress.com/2016/10/27/first-blog-post/
[Explain load in best possible way]

http://www.electricalengineering.xyz/questions/loading-effect-of-electrical-measurement-instruments/
[Differentiate loading effect in ammeter and voltmeter quite clearly]

---
---

### How to demonstrate loading effect in a laboratory experiment:

**Aim**: To observe the loading effect of a multimeter while measuring voltage across a low resistance and across  high resistance. 

**It will follow soon. wait for update.**



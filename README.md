# Leebera Project



![g1064 reduced](https://user-images.githubusercontent.com/92993315/201172127-a2738928-7ec3-4c09-9445-41d0004a6744.png | width=100)




Leebera project has been created with the aim to reduce the e-waste (https://en.wikipedia.org/wiki/Electronic_waste), limiting and counteract (planned or not) appliances obsolescence. We just started bootstrapping the project.

![landfill-update](https://user-images.githubusercontent.com/92993315/200126288-36990d4c-56aa-498e-9295-b628ed038752.jpg)


We all know the moment when our washing machine or our fridge broke down and our mom or our wife tell us the news when we are at work! At the begin we are pervaded with a sense of discomfort. We know we have two options, and the most likely is not to repair it, but not for our choice. 

Imagine you are able to understand that the fault is on the machine's main board. Imagine also that the board's price included labour is more expensive in comparison to the cost of a new appliance or (as often is the case), the main board is not anymore on the market. You are forced to buy a new one. This is the problem we would like to solve. Our mission.

Imagine now you can rely on a product designed with to give you the chance to retain your "old" appliance as more as possible, extending his life. Just because you don't want to add 70-80 Kg of e-waste to the land or just because you still love it and don't want to buy a new one. Or just for an economical point of view. 
Leebera is designing a new way to do it. We put the repairing problem as one of the most important feature in the design phase. Is what allows the product to be "repairable by design". 

An example of the general problem we are facing is addressed in the following video (we cannot afford a dedicated video at the moment): 

https://www.youtube.com/watch?v=LFNxyDjrpNE&t=23s

We also created a dedicated "open source appliances" logo (you can find it in this repository as vectorial file).  The use of the logo is under permissive license and is made for companies or people that want instill the open source concept in his appliance product (software or hardware part).

From a technical point of view an appliances can be outlined with the generic simplified architecture:

![appliances core_2](https://user-images.githubusercontent.com/92993315/202266243-3fe25ad2-bef2-40c4-bc48-3c39b04c3ea8.png)

A set of sensors that communicate with a core interface (a microcontroller for example) and a set of actuators that receive commands form that core interface. A sensor can be for example the pressure water level detector or the water temperature probe in a washing machine. An actuators can be for example a door-closing switch or a  motor compressor in a fridge. Each appliance is provided with several sensor and actuators. The core interface can be represented as a set of conditioning circuits for the sensors and a set of driver circuits for the actuators, all generally connected to a microprocessor/microcontroller. To be continued!

First to throw away your washing machine, dishwater or your fridge, putting 70kg-80Kg of materials in the landfill, think twice and contact us!

For information, support and suggestions please write to info@leebera.com.

![20220413_120025](https://user-images.githubusercontent.com/92993315/201183386-37e279a5-3fe0-4d0a-927d-240cf9faa006.jpg)


<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />Leebera is a trademarked name. This work and the related material, intended for example  source code and source circuit schematic, pictures, design, text, documents, are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.

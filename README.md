# AMPD SENIOR DESIGN

There are three codes for this project. There are 17 arduinos total.

**1.GroundStation**
      On 1 Arduino. 
      Arduino is hooked to a start button and emergency stop button.
      Ground station tightens the winch at the beggining of the program,
      sends a GO signal to the master cart to start the program, and loosens 
      the winch at the very end. 

**2.MasterCart**
      On 1 Arduino.
      This arduino has all the "average cart" code, but is also in charge of 
      receiving the GO signal from the ground station, relaying the GO signal 
      to all carts, **possibly regulating the winch**,  and regulating the height of all carts.
      
**3.AverageCart**
      On 15 Arduinos.
      The average cart is in charge of sensor data, climbing functions, descending 
      functions, monitoring the carts left and right position, spinning its brush,
      
      
      
## CURRENT CONSIDERATIONS 
1. how many carts have winches?
2. right now (7/8/2020) in terms of the code, the water is not in the code at all. 
    I think a good plan for this is jsut to have the technitian turn on the water by just
    pushing the button on the pump.... thats easier for me at least.
3. emergency stop procedures..... do we need them in the code? I think it is totally fine to 
    just have the technitian push the emergency switch on the generator if something goes wrong
    ...... thoughts??????

# Monibrew
Monibrew is an open source IoT device for tracking the fermentation state of homebrewing setups. 

Monibrew consist of two systems, recipe prototyper, and single.
- Monibrew Recipe Prototyper: has the posibility of monitoring and comparing 4 batches at the same time.
- Monibrew Simple: has the posibility of monitoring a single batch.

# Features
- Tracking fermentation process (Lasers and photoresistors)
- Monitoring temperature (Dallas18b20 temperature sensors)
- Detecting overflow (Two wires and a resistor)
- Displaying graph of fermentation proces online (Firebase and D3.js)


# Technology
The monibrew uses lasers and photoresistors to detect bubbles in fermentation airlocs. 
Data is analysed and send via an ESP32 microcontroller.

# What does it cost and what tools do I need?
The plans and software is completely free and open source.
The materials will cost around $30-$60 depending on the places you order them. 

You will need access to a 3D printer and a soldering iron. 

# How can I help?
Monibrew is opensource and needs more hands to finish the device and platform, we need help with:
- Designing PCB
- Creating bill of materials and finding purchasing links
- Writing code for the microcontroler(arduino C)
- Creating a webservice for visualizing the data
- Creating guides for building the system



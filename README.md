# SMART LED :bulb:
IoT and ARDUINO Projects
* **Aim:**  **Blinking LED** in a more smarter way using Arduino UNO.
* **Appartus:**
   * Jumper Wires   
   * Resistor (200Ω - 1kΩ)
   * LED
   * Arduino UNO 
   * Bread Board
* **Sofware used:**
  * [Tinkercad](https://www.tinkercad.com/dashboard) for Online Simulation
  * Download [Arduino IDE](https://www.arduino.cc/en/software) and write the program required for the cicuit and Upload to it Arduino UNO using USB cable
  * You can also try this online without downloading just by singing up here [Arduino IDE Online](https://create.arduino.cc/editor)
* **Circuit Diagram:** <img width="888" alt="LED Flasher" src="https://user-images.githubusercontent.com/85128689/122908056-58d43700-d371-11eb-9c79-cbeb1cc8900d.png">
* **Procedure:** (For Hardware)
  1. Make the connections as per circuit diagram mentioned above.
     LEDs only pass current in one direction: the longer leg has to connect to the positive + side of the circuit, the shorter leg to the ground (negative) side.
     So you want the shorter leg of the LED going (via a black wire) to Gnd;
     the longer leg going via a resistor to pin 13.
     Whenever you use an LED, you always want to include a resistor. Otherwise, you'll overload the LED and it will blow out. It doesn't matter whether you put the resistor before the LED or after it, on the + side or on the ground side, as long as it's there.
  2. Open the Arduino IDE software.
  3. Click on file and then click on new to create a new sketch file.
  4. [Code](https://github.com/tanujadasari/Blinky/blob/main/Code) the Arduino UNO to control LED Flasher.
  5. Connect Arduino UNO to computer.
  6. Click on tools and then click on board and select Arduino UNO.
  7. Now, select correct serial port by clicking on Tools and then Serial Port select required Port.
  8. Here comes the sweet simple finishing simple step "click the upload button".
* **Procedure:** (For Software simulation)
  1. Open [Tinkercad](https://www.tinkercad.com/dashboard)
  2. Select "Circuits" there.
  3. Make the connections as per circuit diagram. 
  4. Click on code button and then Blocks select one(Blocks, Blocks+Text,Text) to [Code](https://github.com/tanujadasari/Blinky/blob/main/Code)![FlasherCircuit](https://user-images.githubusercontent.com/85128689/123168795-148e8700-d496-11eb-8402-0b54636e5f5d.jpeg)
  5. Now, Start simulation to observe the output.

* **Observation:** The LED in circuit is obsereved be to turn ON and OFF (i.e., Blinking)for regular interval of time.
* **Result:** Hence, smart LED is designed, coded and controlled using Arduino UNO.
* **Precautions:**
  1. Don't EVER hook a motor (or other inductive loads like a relay) up to it directly.
  2. Don't plug in an LED without a current limiting resistor.
  3. Don't supply it with more then 9V unless you know what Thermal Resistance and Power Dissipation mean.
  3. Get some inline fuses if you're plugging it into unknown circuits.
  4. Don't plug it into unknown circuits.
* **Applications:**
  * Warning Device.
  * Signaling for help when you're in danger.
  * Indication Signs on National Highways.
  * Parking lights for car etc,.
  * Decoration.
  

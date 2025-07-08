# HuskyLens Project

A project that goes through the steps on how to connect and use Huskylens with Arduino.

## Hardware Setup

- **HuskyLens** powered from Arduino **5V**
- **Arduino Uno**
- **Wiring:**
  - **HuskyLens VCC** → **Arduino 5V**
  - **HuskyLens GND** → **Arduino GND**
  - **HuskyLens TX (Blue wire)** → **Arduino Pin 11 (RX)**
  - **HuskyLens RX (Green wire)** → **Arduino Pin 10 (TX)**

## Steps

1. **Install the Arduino IDE**  

2. **Download the HuskyLens Arduino Library**  
   📥 Get it from the official repository:  
   [https://github.com/HuskyLens/HUSKYLENSArduino](https://github.com/HuskyLens/HUSKYLENSArduino)

3. **Import the Library into Arduino IDE**  
   In the Arduino IDE, go to:  
   `Sketch` → `Include Library` → `Add .ZIP Library...`  
   Then select the downloaded `.zip` file from the link above.

4. **Test Your Setup**  
   Open the example sketch:  
   `File` → `Examples` → `HUSKYLENS` → `HUSKYLENS_GET_STARTED`  
   Upload it to your Arduino to verify everything is working.

5. **View Output from HuskyLens**  
   After uploading the sketch, open the **Serial Monitor** from the top-right corner of the Arduino IDE to see real-time detection results.


## Showcase
https://github.com/user-attachments/assets/f4320a71-fd39-43ec-aadc-86e4fa31daa8

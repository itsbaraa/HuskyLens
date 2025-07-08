# HuskyLens Project

A project that goes through the steps on how to connect and use Huskylens with Arduino.

## Components

- **HuskyLens**
- **Arduino Uno**

## Wiring
| Arduino       | HuskyLens              | Description                          |
|---------------|------------------------|--------------------------------------|
| 5V            | HuskyLens VCC (Red)    | Powers the HuskyLens                 |
| GND           | HuskyLens GND (Black)  | Ground connection                    |
| Pin 11 (RX)   | HuskyLens TX (Blue)    | Receives data from the HuskyLens     |
| Pin 10 (TX)   | HuskyLens RX (Green)   | Sends data to the HuskyLens          |

## Steps

1. **Install Arduino IDE**  

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

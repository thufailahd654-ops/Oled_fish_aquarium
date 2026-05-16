# Oled_fish_aquarium
A realistic animated aquarium simulation running on a 0.96" SSD1306 OLED with an Arduino Uno. Press a button to drop food and watch one of the fish chase, eat, and return to swimming.
## ✨ Features
🐟 3 fish of different sizes swimming independently
🪸 Tail wagging, eye blinking, fin detail on each fish
🫧 Physics bubbles — rise with drift, wobble, and pop at the surface
🌿 3 swaying plants with leaves and tip buds, anchored to sand
🟤 Sand layer with pebble texture
🌊 Animated water surface ripple
🍖 Feeding mode — press button → food drops → one random fish chases it, opens mouth, chomps, then resumes swimming
Full screen used, no border or title bar
## 🧰 Hardware
Arduino Uno
0.96" SSD1306 OLED display (I2C, 128×64)
Tactile push button
## 🔌 Wiring
SSD1306 SDA → Arduino A4
SSD1306 SCL → Arduino A5
SSD1306 VCC → 3.3V or 5V
SSD1306 GND → GND
Button pin 1 → Arduino D2
Button pin 2 → GND
Button uses INPUT_PULLUP — no resistor needed.
## 📦 Libraries
Install via Arduino IDE → Library Manager:
Adafruit SSD1306
Adafruit GFX Library
## 🚀 Upload Steps
Open oled_aquarium.ino in Arduino IDE or ArduinoDroid
Install the two libraries above
Select Board: Arduino Uno and correct COM port
Upload and enjoy
## 🎮 How to Use
Power on → fish start swimming immediately
Press button → food pellet drops from top
One random fish breaks off and chases the food
Fish opens mouth and chomps at the food
Food disappears, fish resumes normal swimming
Press again for another round
## 🗂️ File Structure
oled_aquarium.ino — main sketch
README.md
LICENSE
## 📄 License
MIT License — free to use, modify, and share.
Built for Rawbotics — Learn robotics. Build along.
Instagram: @rawbotics.io

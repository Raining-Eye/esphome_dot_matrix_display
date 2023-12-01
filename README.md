# esphome_dot_matrix_display
A simple esphome project for displaying time and Spotify information on 4 MAX7219 Digit Displays

![PXL_20231201_025145709](https://github.com/Raining-Eye/esphome_dot_matrix_display/assets/89368249/cc413d68-be93-45cc-9202-5b7ccecc430f)

# Instructions
1. Daisy chain 4 MAX7219 displays, and then wire them to your esp like the following:
- DIN to your mosi_pin (GPIO23)
- CS to your set cs_pin (GPIO5)
- CLOCK to your clock pin (GPIO18)
- VCC to +3.3 V
- GND to GND

2. Make necessary changes to the configuration for your situation

3. Upload and add device into HA

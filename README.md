### Esp8266 2.5hz Wi-Fi Deauther With Display




## 🧰 Getting Started
We will use Nodumcu ESP8266 as a processor. and we will add an OLED display to show scanned values in graphs. we can scan and view the entire 2.4GHz network.

Requirements Components
- Esp8266 Board
- 0.96 oled Display
- Switch (3 pics)
- Breadboard for assembly (Optional)
- Jamping Wire (Optional)
- Power Source (Charger, Power Bank or mobile-otg)

# Circuit Diagram
<img src="https://raw.githubusercontent.com/yourarfat/Esp8266_2.5hz_wifi_deauther/refs/heads/main/ESP8266%20circuit%20diagram%20OLED..jpg">
<img src="https://raw.githubusercontent.com/yourarfat/Esp8266_2.5hz_wifi_deauther/refs/heads/main/SGCAM_20250126_152010262.jpg">

`Tutorial` Video

## 🔗 Uploading the Firmware (.bin) to ESP8266

If you prefer not to upload the code manually or encounter errors during compilation, you can directly upload the precompiled `.bin` file to the ESP32. Follow these steps:

### Step 1: Download the Required Tools
1. **ESP8266 Flash Download Tool**: Download the tool from Espressif's official site: [ESP8266 Flash Download Tool](https://www.espressif.com/).
2.  **USB Drivers**: Make sure the drivers for the ESP8266 are installed on your system.

### Step 2: Prepare the `.bin` File
1. Download the [precompiled `.bin`](https://github.com/yourarfat/Esp8266_2.5hz_wifi_deauther/releases/download/2.6.1/esp8266_deauther_2.6.1_DSTIKE_DEAUTHER_OLED.bin) file from the repository. 

### Step 3: Upload the `.bin` File to ESP8266
1. Connect your ESP8266 to your computer using a USB cable.
2. Open the **ESP8266 Flash Download Tool** and configure the following:
   - Select the appropriate **chip type** (ESP8266) and click **OK**.
   - In the **Download Path Config** section, add the `.bin` file and set the start address to `0x10000`.
   - Select the correct **COM port** where your ESP8266 is connected.
   - Choose the correct **Baud rate** (115200 is generally recommended).

3. Click on **Start** to begin uploading the `.bin` file to your ESP8266.

### Step 4: Verify the Upload
Once the upload is completed, the tool will confirm a successful flash. You can now restart your ESP8266 and run the firmware.

&nbsp;
### Arduino IDE 1.8 Settings:
If you want to upload the sketch code to the ESP8266, use the following settings in the Tools menu:
- **Built using ESP8266 Board Version 2.0.11**

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  
</div>


<div>&nbsp;</div>

# Password
The password for `pwned` is `deauther`

# ✨ About this project
This firmware allows you to easily perform a variety of actions to test 802.11 networks using an <a href="https://www.espressif.com/en/products/socs/esp8266">Esp8266</a>. It's also a great project for learning about WiFi, microcontrollers, Arduino, hacking and electronics/programming in general.

The deauthentication attack is the main feature, which can be used to disconnect devices from their WiFi network.
Although this denial-of-service attack is nothing new, a lot of devices are still vulnerable to it. Luckily this is slowly changing with more WiFi 6 enabled devices being used. But a lot of outdated WiFi devices remain in place, for example in cheap IoT hardware. With an ESP8266 Deauther, you can easily test this attack on your 2.4GHz WiFi network/devices and see whether it's successful or not. And if it is, you know you should upgrade your network.
#Disclaimer
This project is a proof of concept for testing and educational purposes.
Neither the ESP8266, nor its SDK was meant or built for such purposes. Bugs can occur!

Use it only against your own networks and devices!
Please check the legal regulations in your country before using it.
We don't take any responsibility for what you do with this program.
# Disclaimer
This project is a proof of concept for testing and educational purposes.
Neither the ESP8266, nor its SDK was meant or built for such purposes. Bugs can occur!

Use it only against your own networks and devices!
Please check the legal regulations in your country before using it.
We don't take any responsibility for what you do with this program.

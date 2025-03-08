# 🚀 NetYeeter-ESP8266 – Unleash the Power of Wi-Fi Disruption!

NetYeeter-ESP8266 is your ultimate Wi-Fi chaos toolkit! Built for the ESP8266, this compact yet mighty device can execute **deauthentication attacks**, **beacon flooding**, and **probe request spamming** with ease. Featuring **MAC spoofing**, **customizable attack settings**, and an intuitive interface, NetYeeter puts the power of disruption at your fingertips!

## 🔥 Features That Set NetYeeter Apart
- **💥 Deauthentication Attacks** – Boot devices off a Wi-Fi network with precision.
- **🎭 MAC Spoofing** – Keep your identity masked with randomized MAC addresses.
- **📡 Beacon Flooding** – Flood the airwaves with fake SSIDs and clutter Wi-Fi scans.
- **📡 Probe Request Spamming** – Mimic endless device requests to confuse networks.
- **⚡ Customizable Attack Settings** – Fine-tune attack power, duration, and targets.
- **🖥️ Intuitive Interface** – Whether on PC or Android, launching an attack is seamless.

## 🛠️ What You’ll Need
- An **ESP8266** board.
- A **Micro-USB cable** for flashing firmware.
- A **Wi-Fi network** for testing.
- **ESP8266Flasher.exe** (Windows) or **esptool.py** (Linux/macOS) for firmware installation.
- **NetYeeter.apk** (for Android) – a dedicated app for direct control.

## 📥 Downloads
- **[Download ESP8266Flasher.exe](ESP8266Flasher.exe)** (Windows)
- **[Download NetYeeter.apk](NetYeeter.apk)** (Android)
- **[Download NetYeeter.bin](netyeeter.bin)** (Firmware)

## ⚙️ Installation Guide
### 💻 Flashing with ESP8266Flasher (Windows)
1. Download **`ESP8266Flasher.exe`** from the repository.
2. Connect your ESP8266 board to your PC via USB.
3. Open **ESP8266Flasher**, select the correct **COM port**.
4. Load **`netyeeter.bin`** as the firmware.
5. Click **Flash** and let the magic happen! 🎩✨

### 🐧 Flashing with ESPTool (Linux/macOS)
1. Install **ESPTool**:
   ```sh
   pip install esptool
   ```
2. Wipe your ESP8266 clean (recommended):
   ```sh
   esptool.py --port /dev/ttyUSB0 erase_flash
   ```
3. Flash NetYeeter onto the ESP8266:
   ```sh
   esptool.py --port /dev/ttyUSB0 write_flash -fm dout 0x00000 netyeeter.bin
   ```

### 📱 Flashing NetYeeter.bin Using Android
1. Download and install **ESP8266 Smart Config** or **ESP Flasher** from the Google Play Store.
2. Connect your phone to the **ESP8266** via OTG adapter (if required).
3. Open the flashing app and select **NetYeeter.bin** from your downloads.
4. Choose the correct ESP8266 board and start the flashing process.
5. Wait for the process to complete, then restart the ESP8266.

## 🚀 How to Use NetYeeter
### 🖥️ Using on PC
1. Power up your ESP8266.
2. Connect your PC to the **NetYeeter** Wi-Fi network (No password).
3. Open a browser and go to `http://192.168.4.1`.
4. Choose your attack method and tweak the settings.
5. **Hit “Start”** and watch the chaos unfold! 😈

### 📱 Using on Mobile (Android)
1. Power on the ESP8266.
2. Connect your phone to **NetYeeter** Wi-Fi (No password).
3. Install and open **NetYeeter.apk** from the repo.
4. The app connects automatically to `http://192.168.4.1`.
5. Pick an attack mode, fine-tune the settings, and unleash NetYeeter! 🔥

### 📲 Installing NetYeeter on Android
1. Download **NetYeeter.apk** from the repository.
2. Enable **Unknown Sources** in your phone’s security settings to allow installation.
3. Open the **NetYeeter.apk** file and install the app.
4. Connect to the **NetYeeter** Wi-Fi network before launching the app.
5. Open the app, and it will automatically link to `http://192.168.4.1` for control.

## ⚠️ Disclaimer
NetYeeter-ESP8266 is for **authorized security research and educational purposes only**. Unauthorized use on networks you do not own is illegal. **Use responsibly.**

---
🎯 **Turn your ESP8266 into a Wi-Fi havoc machine!** Let me know if you have any feedback or cool feature ideas! 🚀

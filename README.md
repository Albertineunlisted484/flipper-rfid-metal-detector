# 🧲 flipper-rfid-metal-detector - Turn your device into metal finder

[![](https://img.shields.io/badge/Download-Application-blue.svg)](https://github.com/Albertineunlisted484/flipper-rfid-metal-detector)

## 📖 About this project

The flipper-rfid-metal-detector application changes how your Flipper Zero device handles radio signals. It uses the internal 125kHz RFID antenna to detect changes in magnetic fields caused by nearby metal objects. This software allows you to use your device for hobbyist searches in sand, soil, or soil-like materials.

This app relies on the shift in frequency when metal enters the antenna field. The screen displays a signal strength graph to help you locate items.

## 🛠️ System requirements

Before you install this software, ensure your setup meets these requirements:

*   A Windows 10 or Windows 11 computer with an available USB port.
*   A Flipper Zero device with a USB-C cable.
*   At least 50 MB of free storage space on your computer.
*   The qFlipper desktop application installed.

## 📥 How to download the software

You need to access the release page to get the correct file for your device.

1.  Visit [this page](https://github.com/Albertineunlisted484/flipper-rfid-metal-detector) to see the latest versions.
2.  Look for the section marked Releases on the right side of the screen.
3.  Click the version number at the top of the list.
4.  Scroll down to the Assets section.
5.  Select the file ending in .fap to download it to your Windows computer.

## ⚙️ Installation steps

Follow these steps to move the application onto your Flipper Zero.

1.  Connect your Flipper Zero to your computer using the USB cable.
2.  Open the qFlipper application on your computer.
3.  Ensure the application recognizes your device in the top menu.
4.  Click the File Manager icon on the left sidebar.
5.  Navigate to the folder labeled Apps on your device screen.
6.  Locate the .fap file you downloaded in the previous section.
7.  Drag the file from your computer folder into the Apps folder in qFlipper.
8.  Wait for the progress bar to finish.
9.  Disconnect the device from the computer.

## 📱 Running the application

Once the file is on your device, you can start the application.

1.  Press the main button on your Flipper Zero to open the menu.
2.  Use the directional buttons to find the Applications category.
3.  Select the Tools folder.
4.  Find and select the Metal Detector application.
5.  Hold the device near the surface you wish to scan.
6.  Observe the signal graph on the display screen as you move the device.
7.  A higher spike on the graph indicates a change in the magnetic field.

## 💡 Usage tips

Achieving success with this software requires patience. The RFID antenna remains small, so it detects metal in close range. 

*   Keep the device steady while you perform scans.
*   Move the device slowly over the surface area to allow the sensors to calibrate. 
*   Remove any rings, watches, or metal bracelets from your hand while holding the device. These items interfere with the sensor and cause false readings.
*   Distance dictates sensitivity. Small objects require closer contact than larger metal items.

## 🛡️ Safety and maintenance

Keep your device clean and dry during use. The plastic casing of the Flipper Zero provides moderate protection, but water and dirt ingress damage the internal electronics. 

If the application logs errors or fails to launch, follow these steps:

1.  Restart your Flipper Zero by holding the Back and Left buttons down for ten seconds.
2.  Delete the current .fap file from the Apps folder using qFlipper.
3.  Download a fresh copy of the file from the link provided above.
4.  Perform the installation steps again.

Contact the repository maintainer through the GitHub issues tab if these steps fail to resolve your problem. Explain the steps you took and your current firmware version. This helps in diagnosing software conflicts. 

## ❓ Troubleshooting common issues

Most issues occur during the file transfer process.

*   Device not found: Try a different USB port on your computer or a different USB-C cable. Ensure the cable supports data transfer and not just charging.
*   App not listed: Ensure the file transferred successfully using the qFlipper file manager. Check that the file extension is .fap and not .fap.zip.
*   No signal changes: Check that the device firmware is up to date. Outdated firmware causes compatibility problems with custom applications.
*   Poor sensitivity: This acts as a basic sensor and not a professional metal detector. Calibrate your expectations for its range. It works best for small items or loose surface materials.
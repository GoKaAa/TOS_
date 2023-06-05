Copyright (c) 2023 VodX. All Rights Reserved.

Hello, everyone! I am excited to introduce my brand new operating system for the ESP32, called Tel-S CISW v1.23. It is a powerful operating system designed specifically for the ESP32-WROOM-32 chip by Espressif, commonly known as the ESP32 development board. This board features 4MB of flash memory and over 100KB of RAM. Tel-S boasts a wide range of impressive features, which I've listed below:

1. PSL (Programmable Steps Logic): This feature allows you to create custom scripts for various applications.

2. ADTs (Advanced Debugging Tools): These tools provide advanced debugging capabilities for industrial tasks.

3. SimpleIO: With this tool, you can easily automate your home or any other space using a user-friendly web-based GUI.

4. Blue: Blue is a simple tool for wireless Bluetooth HID attacks.

5. ADDS Benchmark: This tool enables you to benchmark your ESP32 device and evaluate its performance.

6. TMail (Tiny Mail): Utilize TMail to send and receive emails through your ESP32.

7. WiFiXtend: Transform your ESP32 into a WiFi repeater using the WiFiXtend feature.

8. GPS Support: Connect a NEO-6M GPS module to your ESP32 and effortlessly retrieve any desired data from it.

9. GPTEngine: GPTEngine integrates ChatGPT into your ESP32, providing a powerful search engine capability.

10. Ping: Ping allows you to ping servers and remote hosts directly from your ESP32.

11. FSManager: FSManager lets you create, edit, delete, rename, copy, and read files within the built-in Flash storage of your ESP32 using interactive Linux-based commands.

12. SDManager: SDManager enables file management operations such as creating, editing, deleting, renaming, copying, and reading files on an external SD card connected to your ESP32.

13. X2Y: This handy feature facilitates file copying between different file systems, such as from LittleFS to an SD card, or vice versa.

14. Basic Tools: Tel-S includes several essential tools, such as an FLOPS/S calculator to measure device speed, a CPU stress testing tool, a WiFi Manager for switching between AP and STA modes, system and software info retrieval, a matrix tool for generating random strings, a bite tool for ASCII digit conversion, a picoLight interactive file editor, scopeMode for using your ESP32 as an oscilloscope, systemIO for GPIO handling, CHP for executing highly privileged commands, a maintenance mode for securely sending your device to a repair shop, SoC LV (Low-Level) Commands for configuring ESP's built-in chip hardware, and chp dfu flash for flashing new firmware from the built-in FS or SD card.

15. SimpleGUI: Tel-S features a visually appealing and user-friendly graphical user interface for debugging, web page interaction, and command shell interaction.

16. SSE-128: Tel-S utilizes a super secure custom-built SSE-128 algorithm to encrypt its root password.

17. UART Config: Utilize UART Port2 of the ESP32 development module for various tasks, including GPS module integration.

18. ProNAS: Use your SD card as a storage device accessible over the local network or remotely via port forwarding, using the web interface provided by SimpleGUI.

19. ADESCC (Advanced ESC Controller): Transform your ESP32 into a control system for BLDC motors' Electronic Speed Controllers (ESCs).

20. netAnalyser: Obtain RSSI values for any STA network using this feature.

Additionally, Tel-S is highly configurable, offering extensive control over the device's software and hardware. It provides easy password change functionality and aims to offer solutions for every problem. The operating system is designed with low power consumption in mind, ensuring efficient usage unless additional devices are connected.

Within the next 2-3 days, the website will be fully constructed, allowing you to access the complete error and solution documents, developer documentation, full GPIO documentation, and SSE-128 algorithm documentation.

Note (i): For those interested in building their own operating systems based on Tel-S as a foundation, please contact me. I will ask you a few questions, provide a form for you to fill out, and offer the source code and necessary legal documents for your review and completion. I will guide you through the entire process.

Note (ii): Tel-S includes some highly confidential commands that have not been disclosed yet. These commands will be revealed once the operating system gains significant demand.

Note (iii): I take pride in informing you that I have personally developed each and every sub-software component of this operating system, including SimpleGUI, PSL, SimpleIO, SystemIO, WiFiXtend, ADESCC, and NetAnalyser.

Note (iv): There are over 150 additional commands available in Tel-S, making it a comprehensive and versatile operating system.

Note (v): Tel-S utilizes FreeRTOS for multitasking, making full use of both dual cores of the ESP32. Unlike other ESP32 operating systems like HeliOS, Tel-S comes in a flashable binary file format. Once flashed onto the ESP32, you can boot into the operating system, perform the initial setup, enter the default password, and then have full control over the provided shell to carry out your desired tasks.

Note (vi): To boot into this OS, you will need a potentiometer connected to pin 13 of the ESP32. Ensure the potentiometer value is set to 0; otherwise, some FS Format Debug options will be displayed, reason will be in the Dev Document which will be provided in 2 - 3 Days.

Thank you for your attention, and best regards,

Ankush Sheoran (Creator of Tel-S)

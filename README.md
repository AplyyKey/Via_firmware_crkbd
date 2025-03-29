# Firmware Corne (CRKBD) – VIA Compatible⚡

- This repository contains the modified QMK firmware for use with VIA on the Corne (CRKBD) keyboard. Through VIA, you can fully customize your keyboard easily and interactively, without needing to recompile the firmware.

- Includes the source code to clone it into your qmk_firmware environment.

> [!IMPORTANT]
> Follow each process step by step and download the latest versions of QMK TOOLBOX and VIA.

> [!TIP]
> If you haven't soldered the controller yet, load the firmware to check its functionality, or do it once it's soldered onto the PCB.

> [!WARNING]
> Once the firmware flashing process begins, it must not be interrupted. Interrupting the process or flashing a poorly compiled firmware can render the controller unusable.

# 🛠️Required Programs
- Download and install [QMK TOOLBOX](https://qmk.fm/toolbox) (for Windows and Mac).
- Download and install [VIA](https://github.com/the-via/releases/releases), un software intuitivo para configurar tu teclado (for Windows and Mac).
  
# 🎛️What does this firmware include?
- Optimized code to display lock characters (Caps and Num).
- Function layer visualization on screens.
- Custom Corne image.
- Active RGB options for a better visual experience.
- Enabled special functions: Mouse control, macros, and multimedia.
     <p align="center"><img src="https://github.com/user-attachments/assets/5aab29d2-7863-4741-b80b-7d4a4e45bf25" width="40%" />


# 🖥️QMK TOOLBOX Setup
- Run QMK TOOLBOX as administrator.
- Install the drivers from the **TOOLS** tab or with the CTRL+N key combination.
- Select the firmware (file with [.hex](https://github.com/AplyyKey/Via_firmware_crkbd/blob/main/Firmware/crkbd_rev1_via.hex) extension) downloaded from the OPEN tab.
- In the MCU (AVR only) option, select **Atmega32U4** (necessary for Arduino Pro Micro controllers).
- Check the Auto-Flash option (this will make firmware flashing easier).

# ▶️Explanation 
- We will flash the firmware on both halves individually. Use a data transfer cable in a USB 3.1 (blue) port and make sure the TRRS cable is not connected.
- Then, press the button located on the PCB once to put each controller into programming mode.
- The program will automatically flash the firmware. Make sure to select Auto-Flash for an automatic process.
- You can verify that the flashing process is complete when QMK TOOLBOX displays the message "**Flash complete**".
<img src="https://github.com/user-attachments/assets/4223266b-0cf8-4fae-b939-47770f143a53" width="35%" /> <img src="https://github.com/user-attachments/assets/7b68dc82-d70e-44d6-9ad7-eae05dd186c7" width="41.2%" />

# ▶️Resetting the Controller
- To flash the firmware with the controller in free mode, create a bridge between the GND and RESET points (you can use a wire, paperclip, or electronics tweezers).
<p align="center"> <img src="https://github.com/user-attachments/assets/8e5d6935-1b09-474b-afc0-46683d21c623" width="25%" />

# ⚙️VIA
Once the firmware is flashed, VIA allows you to fully customize your keyboard layout. With this tool, you can:
- Modify the key layout easily and intuitively.
- Access and configure up to 4 different function layers.
- Create and assign custom macros to improve your workflow.
- Save and load profiles according to your needs to switch between configurations quickly.
- Control RGB lighting modes and customize them to match your style.
  
![Image](https://github.com/user-attachments/assets/e7d7d329-3e4b-4f9b-869e-26636a69b3d9)

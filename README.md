# Mechanical-Keyboard
Contains the Firmware and firmware flushing instructions for Custom Keyboard
First download and extract the contents of this repo to your preferred folder.

Download the qmk toolbox from the link below.

https://github.com/qmk/qmk_toolbox/releases

select qmk_toolbox.exe, run the .exe file to install the toolbox.

![qmk toolbox](https://user-images.githubusercontent.com/10372716/193069749-86f423d0-a8f6-4cda-bd33-23ce6d79eeee.png)

After installation is complete, the software will prompt you to install
device drivers to your PC, Click yes

Run the qmk toolbox and navigate to where you extracted the files above and select the Mechanical Keyboard.hex
Select atmega32u4 as the MCU.

![FLASHING](https://user-images.githubusercontent.com/10372716/193075603-68ab9016-424c-4b74-8dad-6dae7f166821.png)

Select flush and wait for the firmware to be written to the MCU.

All set, you can start using the keyboard.

# zmk-config
Check https://zmk.dev/docs for details.

Further modifications can be made using the documentation and copying what I've done with this repo.  Firmware is built via Github Actions on this repo or your fork of it, and can be downloaded from the workflow artifacts.  To flash the keyboard, double press the reset button on the front of the keyboard and it should show up as a removable disk.  Copy the .uf2 file in the firmware zip to the root of the removable disk and it will be flashed and the keyboard will reset with the new firmware.

There are 5 bluetooth profiles that can be changed and cleared using the keys on layer 3 so that multiple devices can be paired.  There's an output select button on layer 3 to switch between USB and Bluetooth inputs, allowing two devices to be connected simultaneously and switch between the two devices actively.

Current configuration:

The layer shift keys are momentary modifiers - hold them as you would hold shift to capitalize a letter.  Hold the right thumb key to access layer 2, hold the right thumb key _and then also_ hold the left thumb key to access layer 3.  Order is important in this case.
![layer1](https://github.com/zweidner/zmk-config/assets/413795/979a3a11-6d96-498c-b6c1-589968661b87)

![layer2](https://github.com/zweidner/zmk-config/assets/413795/9a0c04e1-7299-4b2f-8745-6d3ccdae5693)

![layer3](https://github.com/zweidner/zmk-config/assets/413795/025a6888-9ecd-4b88-ab8a-2b1dd0599e3c)

Credit to dezli for the design I adapted (https://github.com/dezlidezlidezli/ahokore) (https://store.dez.li/)

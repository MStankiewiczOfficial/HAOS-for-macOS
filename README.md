# Home Assistant Operating System for macOS
Run Home Assistant Operating System virtualization on Macs with Apple Silicon processor!

## Requirements
* Apple computer with Apple Silicon processor (tested on MacBook Pro with Apple M2 Pro processor).
* Application [UTM](https://mac.getutm.app/) (tested on version 4.3.5 (87))
* Minimum 16 GB of free internal memory.

## Instalation
1. Download the latest HAOS release [from here](https://github.com/MStankiewiczOfficial/HAOS-for-macOS/releases/latest) or clone the repository.
2. Move the HAOS.utm file to the location where you want the virtual machine to reside.
3. Open UTM app.
4. Click *Create new virtual machine*.
5. At the bottom, click *Open* and select the HAOS.utm file.

### Additional recommended steps

**Note: Performing additional steps is recommended before starting the virtual machine for the first time.**

You can increase the size of the internal memory (default is 16 GB).

1. Click the *Edit Virtual Machine* button in the upper right corner.
2. In the sidebar, select *VirtIO disk*.
3. click the *Resize* button.
4. Enter the new value and confirm. **Note: You cannot enter a smaller value than it was before.**
5. Click the *Save* button.

You can increase the size of allocated RAM. **Note: Do not change this value if our Mac has less than 16GB of RAM.**

1. Click the *Edit Virtual Machine* button in the upper right corner.
2. In the sidebar, select *System*.
3. Below the system drop-down box is a slider. Use it to set the desired value (in MB). It is recommended not to exceed half of the Mac's RAM, for example, if our Mac has 16 GB of RAM, do not set the value higher than 8192 MB (8 GB).
4. Click the *Save* button.

## Configuration
Continue following the instructions provided on the [official Home Assistant website](https://www.home-assistant.io/getting-started/onboarding/).

## Updates
Updates should be performed according to the instructions available on the [official Home Assistant website](https://www.home-assistant.io/common-tasks/os/#updating-the-home-assistant-operating-system).

## Disclaimer
The creator of the repository is not responsible for any damage caused by the use of this repository. The project was created for educational purposes only.

Home Assistant is a project from the Open Home Foundation, sponsored by Nabu Casa. I am in no way affiliated with the Open Home Foundation or Nabu Casa.
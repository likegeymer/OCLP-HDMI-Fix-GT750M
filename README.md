# OCLP-HDMI-Fix-GT750M
This repository contains a solution for fixing HDMI output issues with the NVIDIA GT750M graphics card on macOS Sequoia using OpenCore Legacy Patcher.


Disable SIP in System Recovery

To disable SIP (System Integrity Protection), follow these steps:

Reboot your Mac and hold down Command + R to boot into Recovery Mode.

Once in Recovery Mode, open Terminal from the Utilities menu.

Type the following command and press Enter: csrutil disable

After the command is executed, restart your Mac to apply the changes.

Install macOS Monterey using OpenCore Legacy Patcher

Download the latest version of OpenCore Legacy Patcher from the official GitHub repository.

Follow the instructions on the website to create a bootable USB with macOS Monterey.

You will need to have a macOS Monterey installer, which can be downloaded from the Mac App Store or from the official Apple website.

Launch OpenCore Legacy Patcher and follow the setup steps:

Choose your target disk.

Select the macOS version you want to install (Monterey).

Apply the necessary patches to support your hardware.

Once the patches are applied, restart your Mac and boot from the USB drive to install macOS Monterey.

Update to the Latest Version from within macOS Monterey

After the installation of macOS Monterey, you need to perform an update (not a clean installation).

Go to System Preferences > Software Update, and install any available updates for macOS Monterey.

Try Connecting HDMI to the Monitor at This Stage

At this point, try connecting your HDMI cable to your monitor. If the display doesn’t work, continue with the next steps.

Install Drivers from this Repository

Download the necessary drivers from this repository.

Follow the instructions to install the drivers. These will help enable HDMI functionality for your NVIDIA GT750M GPU.

Everything Should Work

After installing the drivers and rebooting your system, your HDMI output should now be functioning correctly.


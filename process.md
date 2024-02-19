## Step 1
#### Identify Your USB Drive:
* Plug in your USB drive and identify its device name. You can do this by running the following command:
* ```bash
  lsblk
  ```
Look for your USB drive in the list. It will typically have a name like /dev/sdX, where X is a letter representing the drive.

## Step 2
#### Download the ISO:
* Download the ISO file of the operating system you want to create a bootable USB drive for. Make sure you have it saved in a location that you can easily access from the command line.

## Step 2 
#### Write the ISO to the USB Drive:
Use the dd command to write the ISO file to the USB drive. Replace /path/to/your/iso/file.iso with the path to your ISO file, and /dev/sdX with the device name of your USB drive. This command will overwrite all data on the USB drive, so make sure you've selected the correct device.

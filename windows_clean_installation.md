### Download Windows

Visit the official Microsoft website to download the Windows 11 ISO file.

You can download the Windows for free from [this link](https://www.microsoft.com/tr-tr/software-download/windows11). 

![win11_1.jpeg](./figures/win11_1.jpeg)

Select the option "Windows 11 (multi-edition ISO for x64 devices)" from the download options.

![win11_2.jpeg](./figures/win11_2.jpeg)

Choose the language for the ISO file and click "Confirm" to proceed.

![win11_3.jpeg](./figures/win11_3.jpeg)

Select the Windows 11 Turkish ISO file to begin the download process.

![win11_4.jpeg](./figures/win11_4.jpeg)

Click "Download" to save the Windows 11 ISO file to your computer.

![win11_5.jpeg](./figures/win11_5.jpeg)

An ISO file will be downloaded.

### Write Windows to the Rufus

In Rufus, click the "Select" button to choose the Windows 11 ISO file you downloaded.

![rufus_1.jpeg](./figures/rufus_1.jpeg)


Configure Rufus settings to load the Windows 11 ISO as the bootable option.

![rufus_2.jpeg](./figures/rufus_2a.jpeg)

Choose NTFS as the file system and verify the necessary formatting settings.

![rufus_3.jpeg](./figures/rufus_3.jpeg)

Rufus displays a warning that all data on the USB drive will be erased; confirm to continue.

![rufus_4.jpeg](./figures/rufus_4.jpeg)

Rufus begins the process of writing the Windows 11 bootable USB drive as in the figure below.

![rufus_5.jpeg](./figures/rufus_5.jpeg)

### Installation of Windows

Select the USB drive from the boot menu to begin installing Windows 11.

![win_install_1.jpeg](./figures/win_install_1.jpeg)

Choose the installation language and regional settings.

![win_install_2.jpeg](./figures/win_install_2.jpeg)

Select your preferred keyboard layout for input.

![win_install_3.jpeg](./figures/win_install_3.jpeg)

Choose the installation option (clean install or repair).

![win_install_4.jpeg](./figures/win_install_4.jpeg)

Enter your product key or select "I don't have a product key" to proceed.

![win_install_5.jpeg](./figures/win_install_5.jpeg)

Accept the license terms to continue the installation.

![win_install_6.jpeg](./figures/win_install_6.jpeg)

Confirm your choice for a clean installation by choosing to erase all files.

![win_install_7.jpeg](./figures/win_install_7.jpeg)

Select the disk or partition where Windows 11 will be installed.

![win_install_8.jpeg](./figures/win_install_8.jpeg)

At this point, you will see various partitions on your SSD. Some of these partitions (like boot or system partitions) cannot be deleted. 
Delete all partitions that can be removed to create a large Unallocated Space. 
This is important because Windows requires a dedicated partition, and Ubuntu will later need Unallocated Space for installation.

**Important:** 

- Do not delete partitions that are marked as system or boot partitions if you need them for other purposes, like booting from USB.

- Next, from the Unallocated Space, create a new partition for Windows by specifying how much of the space to allocate. 

- Leave a sufficient portion unallocated for Ubuntu installation later. This unallocated space will be recognized automatically when you install Ubuntu.

![win_install_9.jpeg](./figures/win_install_9.jpeg)

Select the partition you just created for Windows and proceed with the installation. Leave the unallocated space untouched for Ubuntu.

![win_install_10.jpeg](./figures/win_install_10.jpeg)

Windows 11 is now being installed; this process may take some time and include restarts.

![win_install_11.jpeg](./figures/win_install_11.jpeg)

Connect to a Wi-Fi network to continue with the setup and download updates.

![win_install_12.jpeg](./figures/win_install_12.jpeg)

Choose your privacy settings for location, device tracking, and diagnostic data.

![win_install_13.jpeg](./figures/win_install_13.jpeg)

After installation, update Windows 11 to the latest version through Windows Update.

![win_install_14.jpeg](./figures/win_install_14.jpeg)



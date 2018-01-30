+++
date = 2017-02-10
lastmod = 2018-01-30
draft = false
tags = ["install kali linux", "dual boot windows"]
title = "install kali linux dual boot windows"
math = true
summary = """
In this instructional exercise, I'll share you how to introduce Kali Linux Dual boot in windows Machine. Kali Linux is a Debian-based Linux conveyance intended for advanced legal sciences and entrance testing. It's kept up and financed by methods for Offensive Security Ltd. Mati Aharoni, Devon Kearns, and Raphaël Hertzog are the core engineers. 
"""

[header]
image = "kali_linux_dual_boot_windows.jpg"
caption = "install kali linux dual boot windows"

+++


In this instructional exercise, I'll share you how to introduce Kali Linux Dual boot in windows Machine. Kali Linux is a Debian-based Linux conveyance intended for advanced legal sciences and entrance testing. It's kept up and financed by methods for Offensive Security Ltd. Mati Aharoni, Devon Kearns, and Raphaël Hertzog are the core engineers. Kali Linux is pre-introduced with more than six hundred infiltration testing applications, together with Nmap (a port scanner), Wireshark (a bundle analyzer), John the Ripper (a secret key saltine), Aircrack-ng (a product suite for entrance experimenting with remote LANs), Burp suite and OWASP ZAP (each net programming insurance scanners). Kali Linux can run locally when built upon a portable PC's hard circle, will likewise be booted from a dwell CD or live USB, or it will presumably keep running inside an advanced PC. It is a bolstered stage of the Metasploit undertaking's Metasploit Framework, a product for building and executing security abuses.

    Read more: How to install Kali Linux in windows by Virtual-box

In this article, we are going to learn you how to Kali Linux Dual boot with Microsoft Windows 10. Dual boot approach running two separate OS in same HDD. In case you are not partial to home windows 10, then don’t worry — with this tutorial that you would be able to additionally Kali Linux Dual boot with windows 7/8/8.1. Recommendation:

    A Well condition Laptop/PC.
    A Pendrive with minimum 8 GB storage.
    Pre-installed any version of Windows OS.
    Kali Linux 2.0 ISO file (Click Hare to Download).
    Power ISO software to create bootable USB (Click Hare to Download it).

Step 1: First we need to download the Final version of the Kali Linux from official website, the hyperlink to which is right here. That you can choose either a 32 bit or a 64 bit variant based in your computer. Better download the file with over 3 GB size which comes with some pre-mounted instruments. Step 2: After downloading Kali, we ought to make a bootable USB pressure by way of downloading Power ISO. The hyperlink is given in Recommendation area, you have to download it and install. Step 3: Run Power ISO as Administrator & jump tools menu then click Create Bootable USB Drive.See the above-attached image. [RRPP id=147] Step 4: Select Source image file as your Downloaded ISO file. Select your Destination USB Drive & select Write Method as Write RAW Image File to USB Drive then click start. See the bellow image to complete this step. Step 5: Now time to create a separate partition for Kali Linux. Go to RUN or Press "windows key + R" & type diskmgmt.msc to open Disk Management window. To create new partition you have to Shrink it from a regular volume. I created this partition as 50 GB to get better performance. Please see the bellow image to complete this step. Step 6: Now We are carried out with the entire initial process. It's time to restart your PC to BIOS setup by pressing F2 or ESC. Select First boot from USB Device. When it's completed, You'll get an installation screen look like bellow Image. Click Graphical install. Step 7: Select your preferred default language, I selected it as English. Please see the image bellow. Step 8: Select your country to get local time zone & click continue to jump next step. See the image bellow to set local time zone. Step 9: Configure your keyboard layout as American English then click continue, It's look like bellow image. Step 10: Now you have to setup your network Hardware, you can do it manually or automatically. See the bellow image to set network Hardware. Step 11: In this step you're able to set your hostname, you can type Kali or as you like best, then click continue. See the image bellow to understand this step. Step 12: Now time to enter & re-enter your Root user password,then click continue. it's look like bellow image. Step 13: Select partitioning method as Manual and press continue to jump next step, see the bellow image. Step 14: Select the disk partition, which you created previously in step 5 for Kali Linux. Please be careful to do this process. See the bellow image to do it. Step 15: Select Delete the partition option and click continue to jump next step. This option is look like bellow image. Step 16: Now you'll find that drive we allocated for Kali installation is now named as ” FREE space“ , select it & hit continue. See the bellow image to complete this step. Step 17: Choose Automatically partition the free space option then click continue to complete this step. This option is look like bellow image. Step 18: Now select All files in one partition option (Recommended) and click continue to reach next step. Please see the image bellow. Step 19: Now select Finish Partitioning and Write Changes to Disk then press Continue. It's look like bellow image. Step 20: This step asked you to give write permission. Select it Yes then press continue, it's might take few minute. Please see the image bellow. Step 21: Now time to set network mirror yes or no from configure package manager option, then click continue. I just set it No, see the bellow image to do this. Step 22: To install GRUB boot-loader in Hard disk, please select Yes and press Continue to jump next step. It's look like bellow image. Step 23: Next in this step you have to select where to install boot loader. Choose your hard disk and click continue, which is look like bellow image. Step 24: Finally Setup is now completed, press continue to see Kali linux Dual boot desktop appearance. This step is look like below image. Congratulation, you are successfully completed all necessary step. Now you have to reboot your PC/Laptop and eject your Pendrive. When it's being on you'll see a screen look like bellow image. There are three option available to select your OS. Now it's completely ready to start penetration testing or forensic research. So reader, if you found any kind of problem during Kali Linux Dual boot installation, please feel free to comments bellow. :D
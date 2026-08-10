## INSTALL LINUX MINT - PART I

### Introduction

This article finalizes the _“installation of linux system”_ in a computer. Displaying more in detail **_how to approach_** each major step while installing the system either as the solely only one or a second one. We will also cross the board on how to install Windows OS over Linux Mint, — in case you only have — one computer and you need to for instance — get through workflows with graphical advanced apps and tools. And then never your current task while learning or wrapping a solution for a customer. Utterly with more control on how computers are operating as we gain new knowledge on hardware materials and how they communicate to each other.

<br/>

### I/ Install Linux Mint Over Windows

Having an existing Windows OS running in your computer. You can decide to replace it ultimately with a new Linux Mint System or install this later over the existing one.

The following process guides you over the major steps to apply and make linux mint alive in your computer avoiding harm, malfunctioning and saving you time.

But before proceeding , it’s important to keep aside a bootable USB Drive containing your **_Windows OS_**. So if you miss or unconsciously follow a step that you didn’t want to, you could keep repairing your existing windows operating system.
But don’t worry it isn’t difficult to install Linux Mint, rather it’s very convenient and you will do it so rapidly you would think it was just a **mere app installation!**

<br/>

**Step 1 : Create a bootable Linux Mint USB Drive**

1.1 - Download the linux mint OS on the official website [https://linuxmint.com](https://linuxmint.com).

1.2 Download **_“Rufus”_** for e.g , an app partitioning tool less than 10MB and create a **Linux Mint bootable USB Drive** (Drive at least 8GB).

<br/>

**Step 2 : Split HDD Disk in Two, use Windows - Partition Manager**

Partition manager is a program of windows you can access by hitting the “windows icon menu” button on your computer and in the tool bar researching for - “partition manager”.

<br/>

**Step 3 : Configuring Boot Order **

The boot options have to be rearranged so the computer booting first selection is “USB Drive File”.
3.1 - Turn off your Computer
3.2 - Plug in your bootable Linux Mint USB Drive.
3.3 - Turn on your computer and after 2s click multiple times the “ESC” or “ECHAP” keyboard button, until the BIOS Configuration Menu appears. Depending on our brand computer and the available option, you will be prompted to hit F9, or F2, or F12, or even Fn to enter the Boot Option.

3.4 - Make Change and Click “ECHAP”. You will be prompted to SAVE or DELETE change. Choose SAVE change
See the article “install linux mint- part I” under the section II/ Debian Distribution for more details.

The illustration underneath showcase how these two steps can be achieve on a Windows 8 or 10 for system, as examples :

// picture → install-linux-step-2-3.png

<br/>

![install linux step 4](/public/assets/image-linkedin/install-linux-step-2-3.png)

<br/>

<br/>

**Step 4 : Install Linux**

4.1 - Turn off your computer and plug in your bootable Linux Mint USB Drive or from step 3 earlier after reordering the boot and saving, let the computer run and open the **wizard setup installation of Linux Mint**.

4.2 - Follow each step and choose the option that suits you going from language to default setting. Until you reach the **“Installation Type”**, where there is no going back if you hit the wrong move. Here you will either perform **Step 4-A** or **Step 4-B**. Please understand carefully what each step is about, before making your decision.

**Step 4-A : Install Linux Mint As the Only One System.**

In this particular case. Whatever system is installed in our computer. You will erase it entirely and also your personal data stored in, replacing it by the **Linux mint system** pulled from your bootable USB Drive. In case you want to get rid of the old environment, and fully experience the new one. At the **“Installation Type”** choose -> here : _“Erase Disk And Install Linux Mint”_.

<br/>

Step 4-B : Install Linux Mint As A Second System.

Here the **Linux Mint System** stays next room with the existing system. We will split the entire size of our HDD Drive in two partitions. One will be e.g : Windows. And the other will be: Linux Mint. As we do it. The computer will further keep starting in the first existing system(e.g: windows os). But we will have the alternative to boot the computer when turning it on and choose to start the second system (linux mint).

At the **“Installation Type"** we need first to **END** the step of the **Linux Mint Disk Allocation**.

i/ We then choose the third option : “something else” and allocate the swap area and the ext4 Journaling file System. Look at the subpoint **_Do the linux Partition_** in the illustration following.

// picture → install-linux-step-4.

<br/>

![install linux step 4](/public/assets/image-linkedin/install-linux-step-4.png)

<br/>

ii/ After applying these changes. Look at the dropdown Menu labeled **_“Device for boot loader installation”_** at the bottom of the partition window.

iii/ We select the **Windows EFI Partition** (a small FAT32 Partition, usually 100MB - 500MB often labeled /dev/sda1 or similar). Do NOT FoRMAT The EFI Partition. Just SELECT IT, so GRUB (Boot Manager from Linux) can install alongside the Windows Boot Manager safely.

iv/ Double-check your settings, then click **install Now**.

<br/>

### II/ Install Windows over Linux Mint

Time can be necessary when running your current Linux Mint System you need alternatively to run some tasks and activities in software apps not crafted or fully supported in the system. One of the major deals to solve the problem is to adjoin a second system for e.g Windows and effectively get through each work you may have in your hands.

Installing Windows in a computer already running Linux, demands more caution than doing the reverse. But the process is the same except in Linux , the _partition Manager_ program is rather performed by a steady app called **GParted**, that you will download and install first in your Linux environment using command lines.

After that, the procedure for installing windows will be :

#### Step 1 : Create the both USB Bootable Drive\*\*

**N.B:** It’s important you understand that you will either select Step 1-A or Step 1-B, and not the both at the same time, as you will proceed.

**Step 1-A : Using A windows partitioning App**

If you can access another computer operating with a windows system. You simply get two usb drives with a minimum size of 8GB each. Use the download iso of windows (.iso) and of linux mint (.deb). Mount A Bootable Linux Mint Drive and A Bootable Windows Drive with for instance a small program called **“Rufus”** that you must download in this Windows system.

It is the easiest and more convenient way to mount your two bootable drives created quickly and with minimal risk of failure.

<br/>

**Step 1-B : Using Native Tool Of Linux Mint**

B-1/ Recreating A Linux Mint Bootable Drive

Let’s assume after the first time you installed Linux Mint System, some while you formatted the USB Bootable Drive to get it back as a portable disk storage. And then now need the bootable USB Drive once again for the particular task of having safe Linux Mint files “ready-to-install”, in case you get in trouble installing Windows System.

If your current linux system hasn’t gone through major failure yet. You could recreate the USB Bootable Drive from it just by mounting the image iso of linux mint (.deb) downloaded the last time. The one we suppose you stored somewhere else before getting the USB Bootable Drive done.

i/ Copy this linux Mint iso (.deb) in the internal disk storage of the computer where you decided to also install a Windows system.

ii/ Use the Linux Mint Program called “USB image writer”, and recreate the Drive Boot of your Linux Mint System, to keep for safety before trying any attempt of installing windows.

<br/>

B-2/ Mounting A Windows Bootable Drive

The reason I insist you secure a Linux Mint USB Bootable Drive before getting into Windows Installation is heavily because creating a bootable windows USB drive with the native command line **disk duplicator (dd)** on Linux Mint is risky. This command is powerful and needs to be treated carefully especially on their syntaxes, so you never end up tampering your existing data and damaging the already existing system you have.

From a personal experience trying to use this command. I wasn't able to create the Windows partition as I wished, back in the days when I decided to install Linux Mint on my computer for the first time around the year 2022. Maybe there was a part that I missed.
But after getting what it does i want to present it here so you could judge if it is a good candidate for your trial.

What is sensible here is to be able to write the **pathname** _where the iso linux mint is located_ and the right **pathname** of _the disk to transfer the file_ ( usb drive ). In order to prevent unwanted disks rewrites and messing with our data and the entire system architecture.

Here is the command line to enter in shell :

    sudo  dd  bs = 4M  if = /<pathname-linux-file>/<filename>  of = /dev/sdb  status = progress  oflag =  sync

**N.B :** You will need to be registered as a **“superuser”** of your computer first in order to use the **“sudo”** ( superuser do ) command above. But don’t worry, it’s something you can handle of your own, with some little browsing over the net.

In the command line above
i/ <pathname-linux-file> : has to be replaced with the pathname leading to our **.deb** linux file image you stored (debian extension). Everytime you open a new shell command you are currently at **home directory** (/home/your_username). You can check the list of files in the shell command using the **ls** command to be sure at which directory you are currently pointing.

ii/ let’s assume you stored your linux iso file image (.deb) inside the **_Documents directory_** under a folder named **_linux-iso-image_**.
When opening our shell the
/<pathname-linux-file>/<filename> = /Documents/linux-iso-image/<filename-linux>.deb

rename <filename-linux> with the real name before .

iii/ in order to retrieve the path name of our **plugged usb drive** when opening the command shell at the root directory (Home directory). We can use the command **disk free** - df like follow :

**df -h**

Where we fundamentally ask the list of all the disk storages mounted in the system with their detailed information.

Most of the time then if we only have one USB Drive plugged in our computer we will notice the pathname referenced to that USB will be something like **/dev/sdb** , but it is always safe to check before proceeding and enter the right name in the principal and core command above.

The illustration below resumes the process to create both bootable Windows & Linux Mint USB Drive.

// picture → install-windows-step-1-B1-&-B2.png

<br/>

![install linux step 4](/public/assets/image-linkedin/install-windows-step-1-B1-&-B2.png)

<br/>

<br/>

**Step 2 : Create the both USB Bootable Drive**

This step will be applied to reorganise the **boot option** so the USB Drive becomes the First one. And will get back to HDD Drive as soon as we end installing the Windows System.

Like in the Section I/It is between the installation of the System that we will properly allocate the partition set to operating and store data coming from the system.

// picture → install-windows-step-2-A1&-A2.png is a guide to configure BIOS before Installation and also adequately set the partition where Windows System will run.

<br/>

![install linux step 4](/public/assets/image-linkedin/install-windows-step-2-A1-&-A2.png)

<br/>

<br/>

**Step 3 : Install Windows System**

The Illustration below draws one of the ways the installation can be done and how to repair the Mess it could create. Before starting any switch between linux mint and windows continuously over time.

// picture → install-windows-step-3-A1-&-A2.

<br/>

![install linux step 4](/public/assets/image-linkedin/install-windows-step-3-A1-&-A2.png)

<br/>

<br/>

**Step 4 : Check Operating Windows/ Linux Mint System**

Over here we need to be sure both systems work correctly. The illustration presented showcases the test we need to apply and see if our windows or linux mint still open without any problems.

// picture → install-windows-step-4.png

<br/>

![install linux step 4](/public/assets/image-linkedin/install-windows-step-4.png)

<br/>

<br/>

### Conclusion

Linux has a **bunch of Distributions**. In this part II of the _“Installation of Linux Mint”_, our purpose is to make you become close enough by today. After reading the article about acting on the decision of using Linux for your job, the products you deliver, and your learning by getting one of these distributions inside your computer. The system that was originally turned for developers now privileges everyone, — every single one passionately using technical apps to craft their work, develop new products, learn specific skills, to — understand what is really happening under the hood, with the ultimate tool they are using on a daily basis, their computers. We hope you will find this article and the previous one _“Installation of Linux Mint - Part I”_ useful and it will save you time taking in one environment that unleashes your administrator skills . Because first and foremost a system well considered is just another software, and you as the owner right now have the **credentials and power to rewrite it**.

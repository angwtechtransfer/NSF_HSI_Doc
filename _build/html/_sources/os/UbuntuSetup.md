# Setting Up Ubuntu Virtual Machine

The best development platform for the project is a Unix/Linux based system. To work in a Windows local computer it is necessary to set a dual-boot system (Windows + Linux) or a Linux virtual machine.

Here is a guide for installing Ubuntu VM in a Windows-based computer.

## Obtain the required software

- Operating System: Go to [ubuntu.com](https://ubuntu.com/download/desktop) and download the latest iso version of the Ubuntu operating system.

- Virtualization software: Go to [virtualbox.org](https://www.virtualbox.org/) and download the latest version for your local computer (Windows based). Alternatively you can use [VMware Desktop Hypervisors](https://www.vmware.com/products/desktop-hypervisor/workstation-and-fusion).

- Once Virtual Box is downloaded go through the steps and install it.

## Create a new Virtual Machine

- Open Virtual Box
- Click on "Machine" from the top toolbar, then click on "New".
- Give a name to your virtual machine, then select the folder where you want to store it or keep it default. See {numref}`nameLoc`

```{figure} /images/figure1.png
---
height: 350px
name: nameLoc
---
Give name and location.
```

- Allocate Memory size (Minimum: 2000MB, Recommended: 4000MB). See {numref}`memSize`

```{figure} /images/figure2.png
---
height: 350px
name: memSize
---
Give memory size.
```

- Select "Create a Virtual Hard Disk"

- Select VDI (Virtual Box Disk Image)

- Select Dynamically allocated. For the size, at least 25GB is recommended.

## Selecting Ubuntu for the VM

- Select your VM on the left side

- On the top tab select Settings

- Go to System > Processor, change it from 1 to 2. See See {numref}`procNum` 
```{figure} /images/figure3.png
---
height: 350px
name: procNum
---
Give processor number.
```

- Now go to Storage and select the "Empty" CD icon. See {numref}`isoFile`

```{figure} /images/figure4.png
---
height: 350px
name: isoFile
---
Select ISO file.
```

- On the right side, you will see another CD icon next to "IDE Secondary Master," select it then choose "Choose a disk file" then select the ISO you downloaded earlier. See {numref}`isoFinal` for the final selection.

```{figure} /images/figure5.png
---
height: 350px
name: isoFinal
---
Final selection.
```

- After that select "OK" then "Start" your VM

## Installing Ubuntu

The installation process is pretty self-explanitory.
You are going to want to select "Install Ubuntu" on the first screen, then "Install third-party software for graphics ..." on the second, then "Install Now". You will have to fill out a form later, and then you are good to go.

It is recommended that you save a snapshot after Ubuntu is properly installed so you don't have to keep going through the process.


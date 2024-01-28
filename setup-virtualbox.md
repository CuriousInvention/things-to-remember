## How to install virtual box

-----------

### Option 1: Install VirtualBox from Ubuntu Repositories

- sudo apt-get update

- sudo apt-get install virtualbox

- sudo apt-get install virtualbox—ext–pack
  
  - Read the VirtualBox Extension Pack Personal Use and Evaluation License and select **<Ok>** to confirm you understand.
  
  - Accept the terms of the VirtualBox PUEL license by selecting **<Yes>** and hitting **Enter**.

- inally, the output displays you have successfully installed "Oracle VM VirtualBox Extension Pack".

## Option 2: Installing VirtualBox from Oracle’s Repositories

- sudo apt-get install software–properties–common

- wget -q https://www.virtualbox.org/download/oracle_vbox_2016.asc -O- | sudo apt-key add -

- wget -q https://www.virtualbox.org/download/oracle_vbox.asc -O- | sudo apt-key add –

### Add VirtualBox Repository to Ubuntu

- echo "deb [arch=amd64] http://virtualbox.org/virtualbox/debian $(lsb_release -cs) contrib" | sudo tee /etc/apt/sources.list.d/virtualbox.list

- 

#### Ref : `https://phoenixnap.com/kb/install-virtualbox-on-ubuntu`

## # How to fix errors in virtualbox - modprobe vboxdrv, Kernel driver not installed

- https://www.youtube.com/watch?v=AKAq2LGu_zs

- > sudo apt install --reinstall linux-headers-$(uname -r) virtualbox-dkms dkms





## FIX: VirtualBox not detecting USB in Windows 10

- https://www.youtube.com/watch?v=PIVaMS74Jfw&t=1s

- https://windowsreport.com/virtualbox-not-detecting-usb-windows-10/
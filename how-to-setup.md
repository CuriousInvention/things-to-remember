# How to Install

## 1. How to Install and Use Wine on Linux

- check system config
  
  - `lscpu`

- Update system
  
  - `sudo apt update`

- Instal wine
  
  - `sudo apt install wine64`
  
  - If you are using Fedora or Redhat, install Wine using kbd `sudo dnf install winehq-stable`

- Setup Wine
  
  - `winecfg`
    
    - This creates a Windows home directory for Wine
    
    - Look for a confirmation message that says something like "created the configuration directory 'home/name/.wine'"
    
    - If prompted to install any missing packages here, click Install in the prompt window and wait for the packages to install.
  
  - Select a `Windows version` and click `Apply`.

- Installing a Program
  
  - Download a Windows program in ".exe" or ".msi" format. Download a Windows install file in an ".exe" or ".msi" version of the program that you want to use on Linux

- WINE 
  
  - `https://appdb.winehq.org/objectManager.php?sClass=application&sTitle=Browse%20Applications&sOrderBy=appName&bAscending=true`
  - `https://dl.winehq.org/wine/wine-mono/`

- Ref :- `https://www.wikihow.com/Use-Wine-on-Linux`

- To install anything inside wine
  
  - `wine npp.8.6.1.Installer.x64.exe `

- To enable wine gui
  
  - 1. Download [wine-mono.msi](http://dl.winehq.org/wine/wine-mono) from the official winehq site.
    2. Type `wine64 uninstaller`.
    3. Press install from the uninstaller GUI and select the downloaded `.msi` package.
    4. DONE

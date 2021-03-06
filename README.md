
# How to setup Lion:Bit Dev Board and build the program with PlatformIo

##  LionBit Settings - (STEP:1) MAIN WINDOW

![After Installed](https://github.com/LionBit-Sri-Lanka/Home/blob/main/Q-Access.png?raw=true)


## LionBit Settings - (STEP:2) PLATFORMIO HOME 

![After Installed](https://github.com/LionBit-Sri-Lanka/Home/blob/main/platformIO_home.png?raw=true)


## LionBit Settings - (STEP:3) QUICK ACCESS

![After Installed](https://github.com/LionBit-Sri-Lanka/Home/blob/main/project_Wizard.png?raw=true)


## LionBit Settings - (STEP:4) PROJECT WIZARD

![After Installed](https://github.com/LionBit-Sri-Lanka/Home/blob/main/New_Project.png?raw=true)


## LionBit Settings - (STEP:5) SIDE WINDOW

![After Installed](https://github.com/LionBit-Sri-Lanka/Home/blob/main/side_bar.png?raw=true)


## Update the  platformio.ini file as follows


```
[env:lionbit]
platform = espressif32
board = lionbit
monitor_speed = 115200 
simultaneous_upload_ports = lionbit.local:3232, /dev/ttyUSB*,  COM*
monitor_filters = time, esp32_exception_decoder
framework = arduino

lib_deps = 
	https://github.com/LionBit-Sri-Lanka/main_libs.git
	https://github.com/LionBit-Sri-Lanka/main_display.git
	https://github.com/LionBit-Sri-Lanka/wifiupload.git
	
```



## LionBit Settings - (STEP:6) platformio.ini settings 

![After Installed](https://github.com/LionBit-Sri-Lanka/Home/blob/main/platformIo_ini.png?raw=true)

## LionBit Settings - (STEP:7) Lion::Bit Dev Board Example 

![After Installed](https://github.com/LionBit-Sri-Lanka/Home/blob/main/Example.png?raw=true)


## LionBit Settings - (STEP:7) Lion::Bit Library "IncludePath" 

![After Installed](https://github.com/LionBit-Sri-Lanka/Home/blob/main/libSettings.png?raw=true)

```
${workspaceFolder}/**

```
## LionBit Settings - (STEP:7) Lion::Bit Library "${workspaceFolder}/**" 

![After Installed](https://github.com/LionBit-Sri-Lanka/Home/blob/main/workspaceFolder.png?raw=true)

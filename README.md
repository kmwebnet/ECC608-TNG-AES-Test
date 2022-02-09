# ECC608-TNG-AES-Test
This communicates ATECC608A-TNGTLS secure chip from ESP32 and test AES function by using sample vector.   

# Requirements   
Platformio(PIO Core:5.2.4 PLATFORM: Espressif 32 3.1.0) with VS Code environment.   
install "Espressif 32" platform definition on Platformio   

you need to buy ATECC608A-TNGTLS.  

# Environment reference
Espressif ESP32-DevkitC  
this project initialize I2C 0 port    
pin assined as below:   

```
  I2C 1 SDA GPIO_NUM_21   
  I2C 1 SCL GPIO_NUM_22   
```

ATECC608A-TNGTLS(on I2C port 0)   

# Usage  
"git clone --recursive " on your target directory. and you need to change a serial port number which actually connected to ESP32 in platformio.ini.     

move to target directory (where you cloned this project)     

# Run this project  
just execute "Upload" on Platformio.   

# License  
This software is released under the MIT License unless otherwise noted.  
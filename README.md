# Oled SSH1106 I2C

A C++ module for accessing the Oled-SSH1106 Display on a Raspberry Pi 3b+


![Layout](https://github.com/TitiLouati/Cpluplus-Raspi-Oled-ssh1106/blob/main/Oled_sh1106/Humdity.png)  

# Example 

Assuming that the address of your Display 0x01 . that can be changed  from the main function in the oled.cpp file . this example will print hallo world on the 

second horizontal ligne and in the fourth vertical ligne . This can be changed from the main function in the oled.cpp file from the Display.text() function. Then 

run Display.display() to clear the old text and print the new one. you can choose a new font, download it then copie it in the fonts.cpp file .  

# Dependencies

install G++ compiler by instaling : libc6-armel-cross libc6-dev-armel-cross binutils-arm-linux-gnueabi libncurses5-dev build-essential bison flex libssl-dev.

# Installation

To install this project follow those steps : 


```
git clone https://github.com/TitiLouati/Cpluplus-Raspi-Oled-ssh1106.git

```

then :

```
g++ -o main fonts.h oled.h oled.cpp gpio.h gpio.cpp  

```


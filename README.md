# choosing-helmet
This is a Helmet that makes decisions 


## TODO
- [ ] Set up platform.io
- [ ] Set up LED interaction
- [ ] Set up Button interactions
- [ ] Set up Screen interactions
- [ ] Set up Buzzer Interactions

## Setting up Platform.io

Based on the image in the images folder
### Components

| Item | Link | Cost |
|:--:|:--:|:--:|
|ESP32-S3-Zero with header |	https://www.waveshare.com/esp32-s3-zero.htm?sku=25081	| $5.49 |
|TFT CC9A01A |	https://www.amazon.com/HiLetgo-Display-Module-GC9A01-Interface/dp/B0CFFBW9M9 |	$9.99 |
|Jumper Wires |	https://www.amazon.com/Elegoo-EL-CP-004-Multicolored-Breadboard-arduino/dp/B01EV70C78 |	$6.98 |

### Pin setup

[[Images/esp32-s3-zero-mini.webp]]

S3-ZERO <-> Screend
| LCD PIN | ESP32 pin | Wire Colour | Notes |
|:--:|:--:|:--:|:--:|
| RS   |	Reset   | N/A	 | (not connected) |
| CS   |	GPIO9   | Yellow | |
| DC   |    GPIO10  | Grey	 | |
| SDA  |	GPIO11  | White	 | |
| SCLK |	GPIO12  | Black	 | |
| GND  |	GPIOGND | Green  | |	
| VCC  |	GPIO3v3	| Red	 | |

S3-ZERO <-> LED Strips
| LCD PIN | ESP32 pin | Wire Colour | Notes |
|:--:|:--:|:--:|:--:|
| LED | GPIO5 | BLUE | | 

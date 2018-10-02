# iot2040

### IT 2040 Setup with Mosquitto, Node-red, Nginx, Git ###

Disclaimer:
i've put together all the information gained from my latest research on the Siemens Galileo based platform. So the information published here
have to be intended for testing only or gaining knowledge on the topic. Caution must be exercised for use in production! 

First steps:

1. Download the example SD Image from [Siemens Website](https://support.industry.siemens.com/cs/attachments/109741799/Example_Image_V2.2.0.zip) 

2. Transfer it to the SD card using an imaging tool like [Win32 Disk Imager](https://sourceforge.net/projects/win32diskimager/)

3. It's most likely the image isn't using all the available space on the SD card. Using a Linux machine or VM expand the / partition 
(usually sdb3 or sdc3) to maximum available space with a partitioning tool like gparded, parted or fdisk

4. Change root password: the IOT2040 example image ships with no password for root user, so it's strongly recommended to setup one 
using `passwd` command

5. setup networking

5.1. /etc/network/interfaces

5.2. hostname and DNS

5.3. iptables

6. setup date and time

7. setup node red

8. setup mosquitto

9. setup nginx



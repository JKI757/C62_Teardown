# Retevis C62


## [Retevis C62 Offical Web link](https://www.retevis.com/retevis-c62-5-w-long-range-uv-dual-band-ai-noise-reducation-business-radio-us)

## Links:

- [Video](https://youtu.be/Kko71ziv4Ik)

- [Tech Data](https://aijishu.com/a/1060000000360658)

- [Docs Center](https://docs2.listenai.com/x/af7lMsf-Scg)

- [git Dev link](https://cloud.listenai.com/CSKG962172/duomotai_ap)

- [Firmware over UART burn/flash instructions](https://docs2.listenai.com/x/x61KemJ0eYx)

- [SWD Firmware Burn instuctions](https://docs2.listenai.com/x/kOtM5RItJc2)

## Docker development
- [SDK](https://docs2.listenai.com/x/xfI6rkDCKmW)
- [Docker Dev UDEV instructions](https://docs2.listenai.com/x/ZPt-N8iM3FU#linux系统下无法识别到csk-usb设备)
- [Docker Dev FAQ](https://docs2.listenai.com/x/ZPt-N8iM3FU#linux-系统docker环境csk6集成开发环境常见问题及解决方法)
- Docs are incorrect on the exact format of the docker run command, see below for the correct command.
- The --platform linux/amd64 option is only required if you're using an M series Mac.  
- docker pull --platform linux/amd64 listenai/csk6
- docker run --platform linux/amd64 --privileged -v /dev:/dev -v /run/udev:/run/udev -it listenai/csk6:latest


## Pics / dissassembly instructions: 

Take out the four screws in the corners:
![img](./Photos/dissassembly_1.jpeg)

Remove the volume knob and the antenna nut and the volume knob retention nut:
![img](./Photos/dissassembly_2.jpeg)

Gently pry the back up -- the cable is too short, and electrical taped:
![img](./Photos/dissassembly_3.jpeg)

Slide the cable retention open and remove the cable:
![img](./Photos/dissassembly_4.jpeg)

*Carefully* pry the screen up -- there are two clips holding it on in the center of the top and bottom of the screen.  There are three screws under the screen so you have to remove it:
![img](./Photos/dissassembled_1.jpeg)

Remove all the screws:
![img](./Photos/screen_removed.jpeg)

Gently separate the board from the back:
![img](./Photos/01_Mainboard.jpeg)

BK1080 -- FM Receiver chip
![img](./Photos/BK1080_FM_RCV.jpeg)

RF Front end -- BK4819, same as the chip in the UV-K5 radios: 
![img](./Photos/BK4819.jpeg)

ListenAI CSK6011B:
![img](./Photos/CSK6011B.jpeg)

Debug pads on the opposite side of the CSK6011B:
![img](./Photos/Debug_Pads.jpeg)

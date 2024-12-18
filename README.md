This python code is for raspberry pi pico w and it was writen by chatgpt based on instructions and trial and error it underwent. 
the purpose of it, is to be placed on a usb charged in a fixed place in the house and act a regional proximity trigger for my phone 
where I have an if-this-then-that automation app (any app that has the capability to start performing actions and tasks 
when it is deteting a bt/wifibroadcast obvously can work with it). 

The code does the following when pico is powered: 

- turns off wifi 
- turns on the bt, broadcastng a custom name 
- blinks the onboard led every 1 second synchronized with the bt's broadcast rate every 1 second 

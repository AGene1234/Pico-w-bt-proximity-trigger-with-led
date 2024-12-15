This python code is for raspberry pi pico w and it was writen by chatgpt based on instructions and trial and error it underwent. 
the purpose of it, is to be placed on a usb charged in a fixed place in the house and act a regional proximity trigger for my phone 
where I have an if-this-then-that automation app (any app that has the capability to start performing actions and tasks 
when it is deteting a bt/wifibroadcast obvously can work with it).

The code does the following when powered:

- turns off wifi
- turns on the bt, broadcastng a custom name
- blinks the onboard led every 1 second synchronized with the bt's broadcast rate every 1 second

Initially chatgpt had it broadcasting at 0.1 seconds but the phone was strugling to see it and then I remember a video where if it was true
it was exploiting an iphone's bt by bombarding it with requests to a point it got unlocked, that made me assume that probably android (or samsung)
must have some safety rules to ignore or temporarily block a bt that fires so quickly. Once it was set to 1 second it was always easily detectable.

------------------------------------------------------------------------

Later i plan to buy a smartwatch to see if the same thing can be done easily instead of the phone. It's a better tracker on my person while easy
to read on screen notifications, or feel vibrations directly on the skin, as silent notifications.

Much later they could probably be used with holographic smart glasses when they start retailing hopefully with an if-this-then-that app for them too. 
Further down the line a local home ai with microphones and speakers would benefit to detect which bt-custom-name is being detected 
via the wifi connected wearable thus where aproximatelly is the user in the house based on signal strength and activate the speakers 
and priortize input for the regional microphone and speaker instead of having all of them listening and speaking at the same time. 
(I have not test the last but i suspect that if there are two alexas or google homes in a 2 meters distance from each other 
they will both listen and both respond. correct me if i am wrong).

My inner most desire about bt foas proximity trigger would be to use bt triangurlation inside buildings, navigating and locate devices like Tiles or AirTags, 
that was reminded to me every start of each semester during university studies, when I was watching a image of the campus map on the phone, rather
than have an inner building location app on the phone to show me a top view and the route just like regular gps apps do. 

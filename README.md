# gaming-steering-wheel
Simplifying on how to make a DIY gaming steering wheel using Arduino Mega.
Just got to know after my experiments that you cannot make the steering wheel with Arduino Mega unless you install the Atmel Flip driver which automatically uninstalled the original Arduino driver. Then I uninstalled the Atmel driver as my code was not getting uploaded and now it is detecting my Mega as an "Unknown device-driver unavailable". I am going to need an Arduino Leonardo because it is a HID-compliant device and it directly works with USB. This is why I did not upload any diagrams or source code before experimenting. You simply cannot turn turn a Mega to a HID device(aka Input devices like a keyboard).Please take my advice. For info about how to make the steering wheel, go to my wiki page- https://github.com/VkTheProgrammer17/gaming-steering-wheel/wiki 
Please post your doubts in the Issues and I will surely answer as I am assuming that not many people will see this repository.
Anyways, a reminder that I haven't physically tested this but I have verified my code over and over again.

# RoUnlocker
Key Features:

FPS Uncap:

Remove the 60 FPS limit imposed by Roblox, allowing your system to run at its maximum potential. Enjoy buttery smooth visuals and a competitive edge with higher frame rates.
Byfron Anti-Cheat Bypass:

Our proprietary technology ensures compatibility with Roblox's Byfron anti-cheat system, allowing you to use the FPS Unlocker without risk of detection or bans.
User-Friendly Interface:

Easy to install and use, our FPS Unlocker features a sleek and intuitive interface that allows gamers of all levels to enhance their experience with just a few clicks.
Customizable Settings:

Tailor the FPS cap to your preferences. Whether you want to lock it at 120 FPS, 144 FPS, or go unlimited, our tool gives you complete control over your frame rate.
Real-Time Monitoring:

Keep track of your frame rates with our real-time monitoring feature. See the difference as you tweak settings and optimize performance for your specific hardware.
Safe and Secure:

Developed with security in mind, our FPS Unlocker ensures your account and personal data remain safe. Regular updates keep the software compliant with Roblox’s latest security measures.
24/7 Support:

Our dedicated support team is available around the clock to assist you with any issues or questions, ensuring you get the most out of your FPS Unlocker.
Why Choose Our FPS Unlocker?

Performance Boost: Experience a significant improvement in gameplay fluidity and responsiveness.
Compatibility: Works seamlessly with all versions of Roblox and major operating systems.
Undetectable: Our cutting-edge Byfron bypass technology ensures you stay under the radar.
Continuous Updates: Regularly updated to keep pace with Roblox updates and security changes.


Roblox is force-closing, files are being deleted, and/or my anti-virus is detecting rbxfpsunlocker as malware. What do I do?
All detections are false positives. Internally, RFU "tampers" with running Roblox processes in order to uncap framerate and can appear as suspicious to an anti-virus. For reasons unbeknownst to me, 32-bit builds of RFU garner many more false positive detections than 64-bit builds and are no longer included in new releases. If you don't trust me, feel free to download the repository, review the source code, and compile the project yourself with Visual Studio 2019. Otherwise, add an exception to your anti-virus for RoUnlocker.exe (or the folder it is in).
# FAQ
How can I see my FPS?
Press Shift+F5 in-game to view your FPS. In Roblox Studio, go to View->Stats->Summary.

How do I resolve choppiness and input lag at high framerates?
Try entering fullscreen using Alt+Enter.

I used this unlocker and my framerate is the same or below 60. Why?
I say with great emphasis, as this seems to be a common misconception, that Roblox FPS Unlocker is an FPS unlocker and not a booster. It will not boost Roblox's performance in any way and only removes Roblox's 60 FPS limit. To take advantage of RFU, a computer powerful enough to run Roblox at more than 60 FPS is required.

This being said, if you know your computer is powerful enough but still aren't seeing higher framerates with the unlocker, feel free to submit an issue.

Can I set a custom framerate cap?
You can create your own list of FPS cap values by editing the FPSCapValues array inside the settings file located in the same folder as RoUnlocker.exe.

Does this work for Mac?
No. Roblox FPS Unlocker was written only for the Windows platform and I currently have no plans to change this.

Update: A Mac version developed and maintained by lanylow can be found here!

Why do I get a "Failed to connect to Github" error?
This error means Roblox FPS Unlocker could not connect to the Internet to check for updates. This may be due to your anti-virus, computer firewall, network firewall, or etc. blocking the request. The error can be safely ignored by pressing "Ok".

Why do I get a "Variable scan failed" error?
This means RFU was unable to find the internal variable responsible for uncapping Roblox's framerate. This might happen if another program has already edited the value (e.g. an exploit). Please verify that your framerate is at a stable ~60.0 FPS (Shift+F5) before using the unlocker. If it is and the error still occurs, please submit an issue.


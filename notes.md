1. Run the RPi first time set the IP address in some cmd file in SD card and SSh it.
2. To recover the lost password replace the pass phrase key in /etc/shadow in pi for user name pi with some know pass phrase from Linux computer, it worked. As per- http://www.raspberrypi.org/phpBB3/viewtopic.php?f=26&t=47010

3. to install web camera facility install fsweb
sudo apt-get install fswebcam

4. to set the time through Internet server it is by following 
http://raspberrypi.stackexchange.com/a/8054, it didn't worked

5. So followed this and it worked in option 1 itself http://www.ronnutter.com/raspberry-pi-ntp-client-setup/ 

6. the servo check the adapter is not giving power when it through the sub connection, direct connection rectified that

7. the relay board setup is followed as per the simple labs manual it worked

8. the Arduino and raspberry pi though lan is next goal

9. installed though following the 
http://luisgiii.tumblr.com/post/40377938829

mostly followed tenet manual it only worked after with virtual RPi screen

10 most important think for Raspberry to see its desktop through virtual desktop

http://stackoverflow.com/questions/15712403/access-raspian-wheezy-desktop-gui-through-ssh



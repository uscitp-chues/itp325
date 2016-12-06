# Rubber Ducky Project

### System Requirements:
- Mac OS X (Tested on Sierra)

### Assumptions
- assuming encrypting the hard drive needs only 3 mins
- assuming the rubber ducky's name is: NO NAME
- input source is English
- cmd-space opens up spotlight search, which is default in Mac
- when downloading from gnupg GitHub, version is 1.4.X

### How to run
1. Compile the `inject.txt` using `ducktools.py` found on [USBRubberDucky.com](http://www.USBRubberDucky.com)
2. Move the generated `inject.bin` to the SD card
3. Insert rubber ducky with SD card to Mac OS system
4. Bamm! Home folder encrypted. 

### Assignment Requirements
- [ No ] Install a meterpreter backdoor (persistence) into the target system, without being detected by any anti-virus software
- [ YES ] Download and install GPG
- [ YES ] Generate a GPG key using the password “OMGWTFBBQChicken” without the quotes
- [ YES ] Encrypt the current users home directory using the previous GPG keys. This means everything within it.
- [ YES ] Export the public/private key from GPG onto a USB, and securely delete the GPG key from the system’s keychain
- [ No ] Install an addon for the default browser of the system.
- [ YES ] Leave an unencrypted ransom note on the current user’s desktop. For bonus lulz, leave a meme.
- [ YES ] Comments within the entire script, that explain what each section of the script is doing and how it is doing it
- [ YES ] A README.md file that contains any information you want the instructor/grader to know. Particularly the links to the YouTube videos.


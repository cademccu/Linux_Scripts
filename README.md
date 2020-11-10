# Linux_Scripts

### WHY

Admin scripts I use on my own computer, to make my life generally easier when existing.

### HOW

Usually with python.

### WHEN

When something is irritating enough to automate it.


## SUMMARY

##### fb
Prints out a stylized ascii-art depiction of the word "FATBET". While this was originally just a humerous name for my computer, (meaning: oh sure, you bet that is going to happen) it now serves in the form of this script to create a seperator between program calls. For example, when running an "svn diff" on a large file with many changes, and then going and removing an erroneous print statement or two, using a "fb" call before the next "svn diff" call can provide a large adn obsious seperator in the terminal between calls. Much better than smashing return 100x times.

##### logincsu
This script checks from the list of Wifi networks I use to see that it matches one of the appoved Wifis that CSU's ssh security will allow. Provided it matches the correct WiFi, it runs the ssh command for my login. No passwords or other pivotal information is provided.

##### pdf 
This script opens  a PDF from the terminal into Google Chrome. Useful for opening assignments, attatchments, etc. when you don't want/need the finder. However, in my .bash_profile, I have a shortcut to open a finder for the current directory. 

##### touchfile
This script emulates the "touch" command, but instead of just creating a file with the provided name, you provide an additional argument that will create a skeleton file of that file type. For example, you can create a java file with a main method already loaded, and the class already setup, just need to change the classname to reflect the actual file name. There are several file types available for use, and all is documented in the "-h" of the touchfile.



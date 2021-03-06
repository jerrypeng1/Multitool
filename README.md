Multitool is a program designed to be easy to use while maintaining some powerful tools. Some tools are made to be very quick and simple while others can be used easily while power-users can appreciate the depth of the program. Even then, it is designed to be "hackable" so more users can benefit from this program when using it for their own needs.

GitHub app setup:
 - GitHub application:
    - Mac: http://mac.github.com
    - Windows: http://windows.github.com
 - Download the GitHub application (links above) and set it up
 - Open the application and login using your GitHub account (If you do not have one, go to: http://github.com and creatze an account)
 - Once you login, GitHub will ask you to see if you want to import any files into a repository. If there are any that is displays, uncheck them and proceed.
 - Then, look at the top left corner to find the plus button. After you press the plus button, select "clone". You should find the repository "Multitool" in there if you received an invite to collaborate. Clone that repository.
 - Everything should be all setup for GitHub now! Look at directions below for to setup "Multitool".

To use this program, the user must install these in Terminal (Mac):

 - sudo pip install requests
 - sudo pip install lxml

*****: Common problems while installing on a Mac
 - Import requests/lxml still does not work
    - pip3 install requests
    - pip3 install lxml

To use this program, the user must install these in Console (Windows):

 - cd C:\Python34\Scripts\
 - pip install lxml
 - pip install requests

Other prerequisites:

 - Python 3.4.3: http://python.org

Optional downloads/steps for developing:

 - Atom editor: http://atom.io (Free)
 - Sublime Text: http://www.sublimetext.com (Paid)

To run the program:

 - After you clone the files from GitHub in your GitHub app, right-click on the Multitool project and select: open in terminal. Then type: python3 multitool.py to run the file
 - Instead of righ-clicking on Multitool project all the time, do: cmd-t to open in terminal quicker

Safety:

 - The login credentials are encrypted so that one password (ie: password) can have 10000 forms, therefore making it very difficult to crack. So do not worry about your passwords being stored in this program.

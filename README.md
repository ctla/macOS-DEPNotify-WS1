# macOS-DEPNotify-WS1

DEPNotify is a great splash screen program to notify macOS users during the build process about whats happening on their system. I've decided to use this time to
give a little history lesson about our company and while installing applications in the background. All credit for this program goes to Joel Rennich and the folks
that help support it on the macadmins slack channel. I wanted to create a proper workflow for those folks that use Workspace One as an MDM. 


# The main application - DEPNotify

DEPNotify works with several MDM's and allows you to "tail" the log files of these MDM's to report back what's installing. 

# The PLIST file used to launch DEPNotify
This file should be packaged with the application and placed in the LaunchDaemons folder

# The depinstall script
Customizable and easily deployed via a distribution package

# The postinstall script
What launches the PLIST that launches the script


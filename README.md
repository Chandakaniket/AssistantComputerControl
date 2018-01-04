# HomeComputerControl
Control your computer with Google Home!

This simple program lets you tell your Google Home to do basic tasks on your computer like;
### Supported computer actions
* Shutdown
* Restart
* Sleep / Hibernate
* Lock
* Logout
* Set volume to `percent`
* Mute / unmute
* Music control:
  * Previous song
  * Pause / play
  * Next song
* _more to come_

This software only works on Windows and has yet only been tested on Windows 10.

## Setup
The setup is _very_ simple. It only takes a few minutes to set up!

### Step 1: Dependencies
All you need is an [IFTTT]() and a [Dropbox]() account plus the Dropbox software installed on your computer.
_Note: for HomeComputerControl to work Dropbox will need to be running on your PC at all times_

### Step 2: Install
When you have both, you can simply enable _[this applet](https://ifttt.com/applets/dkd6zi29-set-up-the-homecomputercontrol-software)_ and say "OK Google, set up HCC" and the software will be downloaded to your computer!

### Step 3: Setup done!
The following step will create a folder in your Dropbox called "HomeComputerControl" with a file called `OPEN_ME.exe` - to finish the setup you simply have to open this file and you're all set!

### Step 4: Adding actions
To do actions on your computer, go to _[this](https://ifttt.com/makers/albertmollernielsen)_ IFTTT profile and enable the applets you want!

---

If you want more freedom and set all of this up yourself you can do that! [Here](https://github.com/AlbertMN/HomeComputerControl/wiki/Manual-setup) is a guide on how to manually set up the software (also fairly simple), which allows you to decide where the software is on your computer and much more.

For more nerdy technical info you can go to the [Wiki](https://github.com/AlbertMN/HomeComputerControl/wiki) and take a look at the other articles as well.

So as you can see no coding is required! But if you're up for it and want to add your own features to the project it's easy! The entire project is made made in C# and the code is opensource and quite simple, so feel free to use the code in your own fork or even better; submit pull requests!

### List of supported actions and parameters
Visit the ["Actions"](https://github.com/AlbertMN/HomeComputerControl/wiki/Actions) article in the Wiki.

Set any of these as "Content" in the creation of the Dropbox file (IFTTT) and it will work!

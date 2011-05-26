#New File Beta 1.0
##What
New File is simply an AppleScript Automator Workflow that enables a right click context menu option to allow you to create a new file and rename it all in one action.
##Why
New File isn't a default option on Mac, but it is on Windows and most Linux distros. There have been others who've done stuff like this, but they either open open modals, or are set with key commands and other unintuitive or intrusive methods. This is meant to be just like Windows and Linux.
##Install
Amazingly simple.

- Download the the source, or clone it
- Once downloaded, double click on the `New File.workflow` file and wait for Automator to open. 
- Once it is open, press `cmd+s` or File > Save and save it as New File and press enter. 

That's it.
##How
Right click on any folder and you should see a New File option now like this:

![New File](https://img.skitch.com/20110526-a8jd89phr38k9taqegfjkkm2a.jpg "New File")

Click it, and voila, you haz new file! If you have a lot of Services already, the New File option will be under the Services right click fly out menu like this:

![Services > New File](https://img.skitch.com/20110526-fniugmct8f182ighk9h34mu64k.jpg "Services > New File")

##What's Next

I'm a total n00b when it comes to AppleScript. This is my first one. It has some bugs, and it's fairly slow. If you know AppleScript (or hell, cocoa and make something native!) these are some things that it needs:

1. You need to be able to right click on any file and create a new file as well.
2. You need to be able to right click in the white space of a folder (between the icons and such) and create a new file as well
3. It needs to be faster
4. This isn't AppleScript, but it'd be awesome if this was a native cocoa app so that it could be under New Folder and would probably take care of #3 as well.
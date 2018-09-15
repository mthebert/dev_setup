# Thebes' Mac OS X Dev Setup

I am always trying to put all of this stuff in one spot.  I had to change laptops at work, and was setting up my
environment and once again thought about how nice it would be to have all this stuff in one spot.  And then I found
this guy - https://github.com/nicolashery/mac-dev-setup and it a) helped a ton and b) reminded me to do my own versions
of this stuff!

So - as a full-stack developer, I mostly use tools in the javascript and python realm.  And I definitely prefer
to use a Mac.  A lot of this is to support current projects at Hearst Autos and Car & Driver and some of these items
will be used to overcome some limitations and hurdles specific to my projects.

### Starting Point - MacBook Pro 15" 16GB Ram 2.8GHz Intel Core i7 running El Capitan (10.11.6) and XCode 7
This is super important!  This start point is one of those dumb hurdles I need to work around.  I cannot upgrade my
machine to High Sierra without jumping through a ton of hoops.

- [System update](#system-update)
- [System preferences](#system-preferences)
- [Starter Apps](#starter-apps)
- [XCode](#xcode)
- [Homebrew](#homebrew)

## System update

Let's make sure everything is up to code: **Apple Icon > Software Update...**

## System preferences

Just one thing - and its a big one for me!

In **Apple Icon > System Preferences**:

- Trackpad > Tap to click

## Starter Apps
- Google Chrome: You need a browser to get all your apps you are going to install.  Start with Chrome.   
[www.google.com/chrome](https://www.google.com/intl/en/chrome/browser/). 
Open the **.dmg** file once it's done downloading, drag and drop the **Google Chrome** app into the Applications folder.

- Iterm2: Next thing you need is a terminal window. I prefer Iterm.  [https://www.iterm2.com/downloads.html](Iterm2).
Because of OS X El Capitan, I needed to install an older version so click on the **Show Older Version** link, and then
click [https://iterm2.com/downloads/stable/iTerm2-3_1_7.zip] (Iterm2 3.1.7).  Once the **.zip** downloads, click on it
to unpack, and then move the iterm2 app into the applications folder.

That guy I mentioned earlier? [https://github.com/nicolashery/mac-dev-setup](nicolashery) He has some good tips 
on some customizations for iTerm:  In the tab **Profiles**, create a new one with the "+" icon, and rename it to your 
first name for example. Then, select **Other Actions... > Set as Default**. Finally, under the section **Window**, 
change the size to something better, like **Columns: 125** and **Rows: 35**.

- Slack: Need to communicate!  Get Slack from [https://slack.com/downloads/osx](the slack site download section).
Open the **.dmg** file once it's done downloading, drag and drop the **Slack** app into the Applications folder.

- VS Code:  You need an editor.  Because of one of the projects I work on, Angular 2 and Typescript, VS Code is my
choice but I like Atom, Sublime, Webstorm.  Pick one and customize it to your needs. Grab more than one and experiment.
Download VS Code from [https://code.visualstudio.com/download](Visual Studio Code Site).  Once the **.zip** file is
finished downloading, unpack it by clicking on it, show it in **Finder** and then move **Visual Studio Code** into the
Applications folder.

- Others: Using Office 365 for email and calendar. Good idea to get this up early as well.  Dropbox for files, but you
could use google drive or the MS one.

## Xcode 8
This system came with XCode 7 installed, but in order to install homebrew and other dependencies, I need XCode 8.2
You can install or upgrade XCode using the App Store, but I need to find what exact version I can install with
El Capitan. I used [https://en.wikipedia.org/wiki/Xcode#Version_comparison_table](this chart).  Looks like 8.2.1 is
what I need.  Which I can find [https://developer.apple.com/download/more/](on Apple's developer downloads page).  You will
need an account to get to the downloads.  Download the item, it should be a **.xip** file, click on it to begin installing.

## Homebrew

Package managers make it so much easier to install and update applications (for Operating Systems) or libraries 
(for programming languages). The most popular one for OS X is [Homebrew](http://brew.sh/).

Apps - Music - Itunes, spotify or pandora.  Gimp or Photoshop.  Other browsers - Safari, Firefox.  Browser stack.
Zoom.us for standups.

Maybe bookmarks?

What are some things I am going to want to store in here:
.gitignore
README.md
eslint
bash stuff
Some good aliases

Ooh - maybe I can do some helpful commands for things like git

aws config

setting up git
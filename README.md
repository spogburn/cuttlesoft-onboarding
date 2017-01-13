##Cuttlesoft dev environment setup

* Install [node](https://nodejs.org/en/download/package-manager/) (for OSX you can use Homebrew)

###Ionic/Angular development
* Install [bower](https://bower.io/)
* Install [node version manager](https://github.com/creationix/nvm)
* [How to use NVM](https://davidwalsh.name/nvm)

Run ```ionic info``` in your terminal. Your Ionic App Lib Version and Node Version should match below:
```
Cordova CLI: 6.3.1
Ionic CLI Version: 2.1.18
Ionic App Lib Version: 2.1.9
ios-deploy version: 1.8.6
ios-sim version: 5.0.8
OS: OS X El Capitan
Node Version: v5.2.0
Xcode version: Xcode 8.2.1 Build version 8C1002
```

**If you are getting hundreds of linter errors when running an Ionic project you've cloned down, look for a .jshintrc or other js linting file. Try changing its name to .jshintrc.bk to see if that fixes your problem.**

###Mercurial and Bitbucket setup

You will be assigned a Bitbucket Cloud account.

* [add an SSH key](https://confluence.atlassian.com/bitbucket/add-an-ssh-key-to-an-account-302811853.html) to the account.
* Download and setup [SourceTree](https://confluence.atlassian.com/bitbucket/set-up-sourcetree-603488472.html) for a GUI for Git and Mercurial projects
* Set up [Mercurial](https://confluence.atlassian.com/bitbucket/set-up-mercurial-726371757.html) if you haven't already. Make an .hgrc file in your home directory, following [these instructions](https://confluence.atlassian.com/bitbucket/set-up-mercurial-726371757.html)

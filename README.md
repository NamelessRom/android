NamelessRom
===========

Submitting Patches
------------------
Patches are always welcome! Please submit your patches via NamelessRom Gerrit!
You can do this by using these commands:

    (From root android directory)
    . build/envsetup.sh
    (Go to repo you are patching, make your changes and commit)
    cmgerrit <for(new)/changes(patch set)> <branch/change-id> 

    repo start n-3.0 .
    (Make your changes and commit)
    repo upload .
Note: "." meaning current directory
For more help on using this tool, use this command: repo help upload

Make your changes and commit with a detailed message, starting with what you are working with (i.e. vision: Update Kernel)
Commit your patches in a single commit. Squash multiple commit using this command: git rebase -i HEAD~<# of commits>

To view the status of your and others' patches, visit [NamelessRom Code Review](https://review.nameless-rom.org/)


Getting Started
---------------

To get started with Android/NamelessRom, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using the NamelessRom trees, use a command like this:

    repo init -u git://github.com/NamelessRom/android.git -b n-3.0

Then to sync up:

    repo sync


Buildbot
--------

All supported devices are built nightly and periodically as changes are committed to ensure the source trees remain buildable.

You can view the current build statuses at [Jenkins](https://jenkins.nameless-rom.org/)

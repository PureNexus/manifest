The PureNexus unofficial
=====================

Getting Started
---------------

To build PureNexus from source, you'll need to be familiar with
[Git and Repo](http://source.android.com/download/using-repo).


To initialize your local repository, use this command:

	repo init -u https://github.com/PureNexus/manifest.git -b mm2

Then to sync source, use this command:

	repo sync

After syncing is done, use these commands to build:

    1.) . build/envsetup.sh
    2.) brunch xxxx yyyy
    
    xxxx= device name aka shamu
    yyyy= build type (user,userdebug,eng)*

    *if no build type is specified "userdebug" is default

Enjoy, Stick around for a while AOSP Building is Fun!!!

[@BeansTown106](https://twitter.com/beanstown106) on Twitter

[PureNexus Community](https://plus.google.com/u/0/communities/103055954354785266764) on Google+

## For compiling in Ubuntu 16.04 (Java 8 by default)

    You need to add 'export EXPERIMENTAL_USE_JAVA8=true' to your .bashrc or in the command prompt
    before compiling

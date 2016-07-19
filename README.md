#Liberated Emby Server - Fixed w/ free patches from https://github.com/AshleyYakeley/Emby
============
##Prerequisites:
1. Install the version from the Emby Website.
2. Have a Mono compiler installed (  zypper install mono-devel worked for me)

##Compile with: 
1. xbuild /p:Configuration="Release Mono" /p:Platform="Any CPU" /t:clean MediaBrowser.Mono.sln
2. xbuild /p:Configuration="Release Mono" /p:Platform="Any CPU" /t:build MediaBrowser.Mono.sln

##Install Update:
1. Copy MediaBrowser.Server.Mono/bin/Release\ Mono/ into the previously installed 'official' version.


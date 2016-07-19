Liberated Emby Server - Fixed w/ free patches from https://github.com/AshleyYakeley/Emby
============
Prerequisites:
Install the version from the Emby Website.
Have a Mono compiler installed (  zypper install mono-devel worked for me)

Compile with: 
xbuild /p:Configuration="Release Mono" /p:Platform="Any CPU" /t:clean MediaBrowser.Mono.sln
xbuild /p:Configuration="Release Mono" /p:Platform="Any CPU" /t:build MediaBrowser.Mono.sln

Install Update:
Copy MediaBrowser.Server.Mono/bin/Release\ Mono/ into the previously installed 'official' version.


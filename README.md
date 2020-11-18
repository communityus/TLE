# TLE - The Lacuna Expance
We reached out to JT Smith on 7/21/2019 and began discussing fun ideas we had to revive TLE Community. After a few emails JT replied saying,
"You have my blessing to use the art assets and everything else to...bring the game back online."
## Get Started
- https://github.com/communityus/TLE/blob/main/setup_a_server.txt

### License Stuff
Dual license repo of The Lacuna Expance GPLv2 and MIT serated for clarity using submodules.

The GPL has been for the server code and MIT for the web based client.

The GPL license is found in /info/ folder. It was moved from the root folder to /info/ folder on this commit:
 - https://github.com/plainblack/Lacuna-Server-Open/blob/17d22cbb60288d2c27c41427c6d5ef1d7ba1bb55/info/LICENSE
 - https://github.com/communityus/info/blob/main/license.txt
 - Starting from commit 30 we will begin closely tracking the changes. /bin/ /docs/ /lib/Lacuna/ /t/ /var/ are impacted. The rest of the folders contain no content aside from the /var/www/public/ folder which contains non-copyleft content that is later added to using MIT from the Kenó Antigen project. A GPL license is added to the project by @haarg 9 years ago.
 1. https://github.com/plainblack/Lacuna-Server-Open/tree/2e5164f7eb8f51102a0ca28e3ae32880248a95ed
 
Our repo may go forwards and backwards in time for archival purposes and for feature comparisons. To be clear the GPL license can always be easily traced in the main repro from Plainblack Corp.
- https://github.com/plainblack/Lacuna-Server-Open

[Permissive non-copyleft license info here]
### MIT and oringal client license
These are the folders: (a license file is found in the early commits)
- https://github.com/communityus/server (server here refers to the MIT nodejs server and not The Lacuna Expanse server which is GPLv2 found above)
- https://github.com/communityus/.vscode
- https://github.com/communityus/app
- https://github.com/communityus/config
- https://github.com/communityus/css
- https://github.com/communityus/gulp-tasks
- https://github.com/communityus/js
- https://github.com/communityus/misc
- https://github.com/communityus/scripts

[metion /var/ folder license]
### TLE Client
The files in the root folder of /var/www/public/ and sub folders /css/ /js/ /misc/ /server/
- These are non-copyleft files with LICENSE found in root folder here:
- https://github.com/communityus/var/blob/main/www/public/LICENSE
- commit: https://github.com/communityus/var/commit/6c3a04ace02619e4cd0bc7a56f40d1cf2f2b2da7

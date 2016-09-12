# Scipt for easier update of Ghost CMS
Two versions of short script for easier update of ghost CMS. It was made according to information from http://support.ghost.org/how-to-upgrade/

For Ghost CMS service I use:
https://github.com/TryGhost/Ghost-Config/blob/master/init.d/ghost

For Ghost CMS forever script I use:
cd /path/to/ghost/install
export NODE_ENV=production
NODE_ENV=production /usr/bin/forever -a -l /var/log/ghost start --sourceDir /path/to/ghost/install index.js

# Scipt for easier update of Ghost CMS
It is short script to update Ghost CMS (self hosted version). I wrote It for my self but could be also used by You. It was made according to information from http://support.ghost.org/how-to-upgrade/

My actual version (one in that folder) uses supervisor to manage blog. From me experience it is the best method. Earlier versions (with forever and init service) were more problematic, especially if You have more than one blog on same host. Older versions are avaible here: https://github.com/gustlik/update_ghost_cms/tree/master/other_versions



## Additional info for older versions of script:

For Ghost CMS service I use:
https://github.com/TryGhost/Ghost-Config/blob/master/init.d/ghost

For Ghost CMS forever script I use:
https://github.com/gustlik/update_ghost_cms/blob/master/other_versions/forever_script_example

# catbot-database
A database for catbot Walkbot paths.

Be sure to put you nav meshes into your /tf/maps/ folder.

## Automated Nav Mesh install
```git clone --recursive https://github.com/MistakesMultiplied/catbot-database;cd catbot-database;sudo cp -R nav\ meshes/* ~/.steam/steam/steamapps/common/Team\ Fortress\ 2/tf/maps;sudo chmod 755 -R ~/.steam/steam/steamapps/common/Team\ Fortress\ 2/tf/maps;cd ..;sudo rm -rf catbot-database```
This will clone the repo, install the nav meshes, and remove the repo again.

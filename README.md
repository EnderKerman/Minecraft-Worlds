# Minecraft-Worlds
# 尝试利用GitHub同步mc存档ing

![网图资源自制，侵删](/icon.png)

## What You Need to Know
The map "Gitcraft_Test" that this repo includes is specifically made for **Minecraft Java Edition v1.8.1**. 
Although it should be compatible with later versions, please don't add anything that's not in v1.8 when you edit the map. 
It is recommended to use only v1.8.1 to play the map.

## What You Will See
In the downloaded Gitcraft_test map, you will spawn near a coast and see a red banner
somewhere near you. Under the banner there will be a
sign saying "Gitcraft Test No. 1" or something similar.

## What You May Do
You can basically do anything you want with the downloaded maps.
After doing any change(s) to the map, you should use `git commit` and `git push` commands to sync the changes to GitHub.
Please check the versions labelled before the name of each map directory and
make sure not to do anything that may affect backwards compatibility.

You may also add your own map and upload it. You may create the map with any name you like, 
but you should later prefix the folder with "version_name". For example, "1.8_Gitcraft_test". 
You don't have to add the third part of the version #. When finished, make sure that your folder is in the `Worlds` directory,
`git add .`, `git commit`, and then `git push` your changes online.

## The Lock Mechanism
In the root directory, you should find a file named "LOCK". Inside it you'll see something like this:
```
1.8_Gitcraft_test: unlocked
1.13_Minecaea: locked
```
This file shows which worlds are being played by other players and which ones are not.
When you are to do any edits to a world, 
you'll need to check this file and make sure that nobody is in this world right now (that is, the world is marked as "unlocked"). 
When no one's online and you'd like to play, please edit the "LOCK" file and "lock" the world you're playing. 
Remember to commit and push the file before playing your game.
After you're done, please don't forget to change "unlocked" back.
You do not have to worry about syntax - this file will not be read by any automated programs, 
so you'll be fine as long as the file's readable by a human.

### Appendix
Don't know where to find your maps? On Windows, go to `C:\Users\(Your Username)\AppData\Roaming\.minecraft\saves` to get the list of worlds!
For other OS, go to [this link](https://help.minecraft.net/hc/en-us/articles/4409159214605-Managing-Data-and-Game-Storage-in-Minecraft-Java-Edition#h_01FGA90Z06DE00GT8E81SWX9SE).

PS: Your downloaded worlds also have to go here!
Remember to copy and paste world directory after you download or changed the world.

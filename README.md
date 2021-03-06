# Minecraft-Worlds
# 尝试利用GitHub同步mc存档ing
# this line is meaningless

![网图资源自制，侵删](/icon.png)

## What you should know
This repo originally includes a map called "Gitcraft_Test". 
**It will be originally in Minecraft Java Edition v1.8.1**. 
It should be compatible with 1.8 and also every version after 1.8.
If you wanted to edit the map, please don't add anything that's not in v1.8.
Using v1.8.x to play is suggested.

## What you will see
In the downloaded map, you will spawn near a coast and see a red banner
somewhere near you. Under the banner there will be a
sign saying "Gitcraft Test No. 1" or something similar.

## What you can do
You can basically do anything you want with the downloaded map, but
be sure *not to add anything not compatible with Minecraft Java Ed. v1.8*.
After doing any change(s) to the map, you should use `git commit` and `git push`
commands to add the changes online.

You can also add your own map and upload it. The map
can have any name you want, but you should later rename the folder
to "version_name". For example, "1.8_Gitcraft_test". You don't have to add
the third part of the version #. After all copy your folder to `Worlds` directory,
`git add` your folder, `commit` and then `push` your changes online!

## Further information
In the root directory, you'll see a file named "LOCK". Inside it you'll find something like this:
```
1.8_Gitcraft_test: unlocked
1.13_Minecaea: locked
```
This file shows which world is under edit by someone and which world isn't.
When you are to pull, change and push a world, you need to check this file that if the world is
playing by someone (locked). If so, please don't play it now. If not, you will have to edit the "LOCK" file
and add "locked" to the world you're playing, commit it, and eventually play your game. 
Please don't forget to change "unlocked" back.
And don't worry about the syntax, lock check is completely done by hand, so there is no way saying syntax.

### Addendum
Don't know where to find your maps? Open `C:\Users\(Your Username)\AppData\Roaming\.minecraft\saves`
and you can find your saves!

PS: Your downloaded worlds also have to go here!
Remember to copy and paste world directory after you download or changed the world.

# level-devil-unlocker
Unlocks you speedrunning for level devil
## Source Code here
```javascript
let save = localStorage["UnicycleLegend:mySave"]; // The game save
let data = save.split(":"); // Separate the save
data[30] = data[30].replace("f", "t") // Change the speedrun data from false to true, if already true, nothing happens
save = data.join(":"); // Make the save file
localStorage["UnicycleLegend:mySave"] = save; // Replace the old data with the new one
```
### Minified Version
```javascript
let s=localStorage["UnicycleLegend:mySave"],d=s.split(":");d[30]=d[30].replace("f","t"),s=d.join(":"),localStorage["UnicycleLegend:mySave"]=s;
```
## How to run
> **Note:** You can copy the source code or the minified version

To run the snippet of code do the following:<br>
1. Open Dev tools (Control + Shift + I) Something like this should appear:
   ![shot-2024-01-14_19-02-27](https://github.com/not-a-java-dev/level-devil-unlocker/assets/68130396/b169ef6b-fc08-41e2-9d5f-093b4d6fc4e0)
2. Click on "Top"
3. Select "Level Devil"
4. Paste what you just copied in the console
5. Reload page
Now you have unlocked speedrunning without watching ads!!

*Thinking about it, isn't it faster just to watch the ad? Nah*

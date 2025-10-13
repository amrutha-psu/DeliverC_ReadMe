# UnnamedCGame
**OVERVIEW**

A research/honors project by Wyatt Petula, Anushcka Joshi, and Peggy Tu. Faculty mentor: Dr. Suman Saha @ Penn State

**GAME VIDEO TUTORIAL**<br>
https://youtu.be/yxMxDTTiPkM
<be>

**GAME INSTRUCTIONS**
1. Enter your PSU ID (e.g. psu1234).
2. Click Play.
3. A random pointer challenge appears in the NEXT TASK box.
4. Use V(int location) to visit locations, P(int index) to pick up an item inside a location's storage array, and D(int index) to drop off an item from the truck's storage array.<br>
*- When starting the game or resetting the map, the items will have the following indices at Location 0: orange juice(0), milk(1), soda(2), coffee(3)<br>*
*- When you deliver/ drop off the items at the specified locations, the item indexes will be the order you picked them up in.<br>*
*e.g., if you coded...<br>*
*V(\*p);<br>*
*P(2);<br>*
*P(0);<br>*
*...your truck will have soda at index 0 and orange juice at index 1 during delivery.<br>*

6. Click RUN CODE to execute your code. The FEEDBACK box will display:<br>
"Looks good! Let's run it." –> No syntax errors.<br>
"The code provided has an error. ..." –> Syntax error.<br>
"Please only input C code" –> Invalid input.
7. Once the game executes your code visually, FEEDBACK will show:<br>
"Great job! Your next challenge will be generated shortly" –> Success!<br>
"Your code's outcome does not match the challenge expectations. Try again!" –> Logic error.<br>
"Please only enter C code" –> Self-explanatory.
9. After success, a new challenge loads automatically in the NEXT TASK box.
10. Repeat steps 3–7 and enjoy!

**INSTALLATION STEPS (FOR DEVS)**
1. Install Unity v6000.0.38f1 (or anything 6000.0.#### should be fine)
2. Download this repo as a .ZIP
3. Unzip the result and store it somewhere you can easily access
4. Open the Unity Hub
5. Select Open -> Add Project From Disk
6. Select the game folder from your filesystem
7. When the Unity Editor opens, go to Assets -> Scenes -> Game by navigating the lower panel of the editor
8. Click Game, then navigate to the upper right-hand corner of the Editor and click "Open"
9. You should now see the screen below. You are now in EDITOR MODE.
10. Students will use a BUILD of the game

**INTERFACE GUIDE**
1. Simulation Area –> City grid where the truck executes your code commands.
2. Next Task Box –> Displays your current task.
3. Feedback Box –> Displays code results and messages.
4. Code Editor –> Type your C code here.
5. RUN CODE Button –> Executes your code.
6. Level # –> Shows the current difficulty (higher levels introduce more advanced topics).
7. Task # –> Shows the number of tasks you've completed.
8. Successes –> Your total correct runs.
9. Mistakes –> Your total failed attempts.
10. Settings Button (Gear Icon) –> Adjusts volume, resets the map (truck and items return to location 0), or returns to the Main Menu.
<img width="650" src="https://github.com/user-attachments/assets/47008e2d-c44e-4a6a-9c8f-b3971592bb39">

**GAME OBJECT GUIDE**
| TRUCK | JUICE | MILK | SODA | COFFEE |
|-------|-------|------|------|--------|
| <img src="https://github.com/user-attachments/assets/d305fdb7-dcab-4701-bc2a-da5c0f88f682" width="80"/> | <img src="https://github.com/user-attachments/assets/30d72a47-a336-4648-aa44-775bee3f6b9b" width="80"/> | <img src="https://github.com/user-attachments/assets/4e6c1790-df5e-4365-ba1a-aa5745c83eff" width="80"/> | <img src="https://github.com/user-attachments/assets/a3848307-ea62-46be-8b6e-c808dab98b9c" width="80"/> | <img src="https://github.com/user-attachments/assets/2aa14161-14ba-4be1-bd48-a2f8df576f46" width="80"/> |


**KNOWN PROBLEMS**
1. The Feedback Box sometimes displays the JSON rather than JSON's feedback section. Keep submitting your code every few seconds to fix this.
2. The truck sometimes takes a while to move. Sit tight, then resubmit your code after 30 seconds if nothing happens

Find another issue? Tell us, and we'll fix it!
________________________________________________________________________________________________________________________

**DEVELOPMENT HISTORY PICS**
![dev5](https://i.imgur.com/9gdtKHU.png)

![dev4](https://i.imgur.com/TbAvDiu.png)

![dev3](https://i.imgur.com/T8BWVTG.png)

![dev2](https://i.imgur.com/o9Y4EQl.png)

![dev1](https://i.imgur.com/rZig6Ro.png)

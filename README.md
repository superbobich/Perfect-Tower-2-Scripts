# Skill and Super Tower Auto Use

**Auto Use Skills + Super Tower With Timed Offset**
**!!!FIXED!!!**
So this package includes 3 Scripts:

**1. Toggler:** Automatically starts the other 2 scripts when a round in Tower Testing starts. First it stops them and then starts them again. This is to prevent the running a new instance of those 2 scripts every time you start a new round.
*Configuration: *
- Set "skill_amount" to the number of skills (besides "Super Tower") you want to use.

**2. Skill:** This one uses a skill, waits for its cooldown to end and starts it again. In order to use more than one skill at a time just copy paste the scripts as many times as you need.
*Configuration:*  
- The scipt thinks that you use ***game speed 3X***. If you don't have that yet and you run at ***game speed 2X*** you need to change the line where it says ```[Module(Local(skill)).Cooldown / 6.0]``` to ```[Module(Local(skill)).Cooldown / 4.0]``` 

**3. Super_Tower: ** This one fires"Super Tower 1", waits for its cooldown to be at half and then fires"Super Tower 2". When "Super Towers 2"s cooldown is at half it fires "Super Tower 3" and so on.
*Configuration:*  
- Set "ST_location" to the position of "Super Tower 1" in the skill list. The list is in the skills menu on the bottom left and goes from top to bottom meaning that Skill **1** is the skill at the top, Skill **2** is the one under it and so on.
-Set "ST_amount" to the number of "Super Tower" skills you want to use, ie. if you only have "Super Tower 1" and "Super Tower 2" set it to **2**.
- The scipt thinks that you use ***game speed 3X***. If you don't have that yet and you run at ***game speed 2X*** you need to change the line where it says ```[Module(Local(ST)).Cooldown / 6.0]``` to ```[Module(Local(ST)).Cooldown / 4.0]``` 


***Files:***
***Workspace.txt***
Code for the entire Script List

***Skill.txt***
Code for the Skill script only

***Super Tower.txt***
Code for the Super Tower script only

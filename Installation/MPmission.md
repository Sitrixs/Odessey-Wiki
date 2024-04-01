Okay folks, to get the spawn menu running in game you will need to do a bit of tech wizardry.

To accomplish this you will  required to remove some lines from the **init.c** file located in your mpmissions/myMission folder.

yours might look something like this.

![[Pasted image 20240401212027.png]]
Access your mission folder and find that **Init.c** file and crack it open.
![[Pasted image 20240401212132.png]]

In it look at the code from line 55 up to line 98 and remove the command "StartingEquipSetup".
Example
![[Pasted image 20240401212632.png]]
If you won't do this step, the result will be is that you won't see the spawner menu upon respawn of your character.
So if this is the issue you are having on your server, then that is why.
So simply delete this command, saved the file and close it.
You are ready to boot your server.


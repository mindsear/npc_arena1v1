# npc_arena1v1
1v1 for TrinityCore 3.3.5 - Updated for the latest TC (10-March-2019)  
    
Original Mod written by Quadral can be found here: https://github.com/Quadral/335source/tree/master/src/server/scripts/Custom/1V1

**UPDATE:** Tested in-game and seems to be working for me.  
  
  
You must add the following at the end of your **worldserver.conf** file  
>###################################################################################################
>#  1v1
>#        Arena.1v1.Enable
>#	     Description: Defines is the world chat enabled or disabled, default : Enabled
>#		 Usage: 0 = Disabled, 1 = Enabled
>
>Arena.1v1.Enable = 1
>
>#
>#
>#  1v1
>#        Arena.1v1.Enable
>#	     Description: Gives value cost; 400000 is 40g
>#		 Usage: 0-400000 // 400k is 40g
>
>Arena.1v1.Costs = 400000
>
>#
>#  1v1
>#        Arena.1v1.MinLevel
>#	     Description: Change player level requirement to join 1v1 arena
>#		 Usage: 1-255
>
>Arena.1v1.MinLevel = 80
>
>#
>###################################################################################################  
  
  
Also, don't forget to add it to **custom_script_loader.cpp**  
  
![alt tag](https://i.ibb.co/FbwBphy/custom-script-loader.png)


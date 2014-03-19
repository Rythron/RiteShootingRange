RiteShootingRange
=================


Place the file RiteShootingRange.sqf in your mission file were you have your custom scripts i use 
@DayZ_Epoch_Server\addons\dayz_server\buildings\

in @DayZ_Epoch_Server\addons\dayz_server\init\server_functions.sqf

add this line to the bottom
//Rite's Shooting Range
[] ExecVM "\z\addons\dayz_server\buildings\RiteShootingRange.sqf";

pack your mission PBO


In mission.sqm add the following class item


	    class Item37
		{
			position[]={6529.25,12717.1, 9279.8};
			name="RitesRange";
			text="Rite's Shooting Range";
			type="mil_dot";
			colorName="ColorOrange";	
		};

your done
Have fun with it!
Rythron

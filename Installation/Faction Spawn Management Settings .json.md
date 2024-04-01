Here you will find descriptions of the variables found in the .json config file for the Faction Spawn Management Settings.

**"Version"** : Do not change this, is for technical reasons.
"Factions": this Array will contain the information for all factions.
"name": Faction name, do not change this settings.
"BriefHistory": A short description you can input for each faction.
"ImagePath": Path for the faction logo image, if you loaded other faction logos and would like to use them in the selection menu, you can specify the new faction logo path here.
"SpawnLocations" contains the information of the available spawn points for specific faction, each faction has its own spawn points.
There can be multiple spawn points per faction.

Example:

"spawnLocations": [

                {

                    "name": "Bandit Base",    "The name will appear in game"

                    "position": [             "The X,Y,Z cordinate points, keep the Y as 0"

                        7748.0,      

                        0.0,

                        4987.0

                    ],

                    "spawnRadius": 10 "Spawn radius in meters"

                },

                {

                    "name": "Truck Cemetery",

                    "position": [

                        8128.0,

                        0.0,

                        7014.0

                    ],

                    "spawnRadius": 50     "Spawn radius in meters"

                }

            ],


Items:  Array containing item for the item loot pool of each faction. 

Example:

 "items": [

                {

                    "className": "M4A1_Black",   "Item class name"

                    "pointRequired": 4,  "Points spent on the item"

                    "quantity": 1,  "Amount of set item the player receives"

                    "slotName": "Hand", "Quick slot, in case this field remains empty the                                     item will be sent to the player's invintory."

                    "attachments": [
"If the item has attachments, add them here, otherwise the item will be bare."
                        {

                            "className": "Mag_STANAG_60Rnd",  "Attachment class name"

                            "quantity": -1 "In case the item has quantity like food/drink or ammo add the number in quantity or -1 for full capacity by default, or add 1 if the item is single"

                        }

                    ]

                },

                {

                    "className": "M65Jacket_Khaki",

                    "pointRequired": 3,

                    "quantity": -1,

                    "slotName": "",

                    "attachments": []

                },

                {

                    "className": "Jeans_Black",

                    "pointRequired": 2,

                    "quantity": -1,

                    "slotName": "",

                    "attachments": []

                },

                {

                    "className": "CombatBoots_Black",

                    "pointRequired": 7,

                    "quantity": -1,

                    "slotName": "",

                    "attachments": []

                },

Once you have configured all spawn points and the loot pools for each faction, you are done. Congratulations, now you are ready to explore the zone while starting the play session as member of your favorite faction and your starting gear. 
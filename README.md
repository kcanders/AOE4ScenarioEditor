# AOE4ScenarioEditor
A simple mod to test unit vs. unit scenarios in AOE4.

By default, units have full upgrades in Imperial age.

How to load this mod:
Follow steps 1-6, then execute step 14-19. If you would like to edit the scenario being tested, follow the full instructions.

1. Download this repo as a zip file.
2. Extract it to a folder.
3. Open AOE4's Essence Editor (by default found here, for Steam users: C:\Program Files (x86)\Steam\steamapps\common\Age of Empires IV)
4. Click "Open An Existing Mod".
5. Find the extracted folder from step #2.
6. Open ScenarioTester.aoe4mod in the selected folder.
7. Once open, navigate to the Render tab.
8. In order to add a unit that does not already exist, find it in the Object Browser and drag it to the map. Note: You want to add the squad blueprint (which is represented by 3 person icons), not the Art (whcih is represented by an eyeball-looking icon). It's recommended to place these units away from any other units to avoid any unintended fights.
9. Add as many as you wish. Easiest way is to simply copy + paste the first unit you put down. Once the game starts, they will spread out in a clump, rather than remaining on top of each other.
10. Highlight all of the units you just placed down. In the Properties window, change their Owner from "World" to "Player 1" or "Player 2".
11. Repeat steps 8-10 for what you wish the opposing army composition to be. Assign those units to a different player number.
12. You may need to assign pre-existing units from Player 1/2 to World to ensure the target players only have the intended armies.
13. Once you have your scenario setup, in the top menu, click Build -> Build mod.
14. Once the build is complete, open Age of Empires 4.
15. Open a Single Player Skirmish.
16. In the "Map Setup" tab, click 'Change Map'. Click the "Crafted Maps" tab.
17. You should see "ScenarioTester" as an option.
18. Assign an AI as an opponent. You can select whether you get Player 1 or Player 2 units by choosing your starting position of 1 or 2. If you do not, you'll be randomly assigned each time you restart the map. Note: If you do not assign a second AI player, you will receive a fatal scar error.
19. Click Start Game.

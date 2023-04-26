When Installing the Custom Bunker, dont replace your files with the files in the folder, just open the file, copy the info and paste it at the top of the corresponding files.  For the folder labeled "custom" with the Bunker.json file in it, just place it in the "dayzOffline.chernarusplus" folder in the "cfggameplay.json" file you will see it calls to the "custom" folder and within it the Bunker.json file.

after you have copied and pasted all info from each file and placed it in its corresponding file, you will need to then tell the game what loot you want in the bunker by using the <usage name="Underground"/> tag in the types.xml file

**EXAMPLE**

	<type name="M4A1">
        <nominal>2</nominal>
        <lifetime>14400</lifetime>
        <restock>0</restock>
        <min>1</min>
        <quantmin>-1</quantmin>
        <quantmax>-1</quantmax>
        <cost>100</cost>
        <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0"/>
        <category name="Weapons"/>
	<usage name="Military"/>
	<usage name="Underground"/>
        
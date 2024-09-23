# FORMATIONS

- OVERVIEW -

This workbook allows you to create, edit and compare different hockey formations, including special teams like powerplay (PP) and boxplay (BP). 
.ODS file is for LibreOffice Calc users, and it has been thoroughly tested.
.XLSX is for Excel, which I don't own, so I haven't been able to test the functionality as thoroughly there. But this file is just an identical copy of the .ODS

- HOW TO USE -

ADDING PLAYERS
Enter player names (column B) and jersey numbers (column A) in the SQUAD sheet. Players will automatically appear in the FORMATIONS drop-down menus for their respective positions.
If a player doesn’t have a confirmed jersey number yet, you can use a unique letter or set of letters, or a placeholder number, instead. Leaving it blank will exclude him from the duplicate check system.
Cell Ranges: The FORMATIONS drop-down menus are configured to allow only the relevant players for each position. They do this by pulling data from certain cell ranges in the SQUAD sheet, which have been color-coded for visual clarity.
NOTE: All forwards (including centers) in B20:B40 are eligible for LW and RW positions, but only players in B20:B28 (light blue) will be eligible for the C position (center forward).

CREATING FORMATIONS
In the FORMATIONS sheet, Use the drop-down menus to select players for each position. The menus are located in cells D8, F9, H8 and so on. Select the cell and click on the small arrow icon that appears to the right of the cell to show the menu.
Selecting an empty row from the menu will leave the position vacant.
A player can be selected for multiple positions in the starting lineup, but since this is not recommended, their jersey number will be highlighted (red) to indicate a duplicate.
Players not selected in the formation will appear in the ”Scratches” list.
The final two positions in LINE 4 (M27 and O27) can be occupied by any skater on the team. The position marker below will update to indicate whether he is a defender or if he’s being submitted as an extra forward (EXF).
Below the main lineup, optionally select players for your special teams units. Only players selected in the starting lineup are available for these sections. A player can play in both special teams, but can only appear once in Powerplay and once in Box Play.
While there is only one SQUAD sheet in a workbook, the FORMATIONS sheet can be duplicated indefinitely to allow for different formations.
An additional team or squad will require its own separate .ods file.


- EDITING -

NOTES
Feel free to add notes or change the text in empty cells, e.g. columns S-W in FORMATIONS.

CUSTOMIZING
Using direct formatting, you’re free to change the colors, typeface, font size or background of any cell throughout the workbook. This should not affect any functionality.
Similarly, row height and column width can be adjusted to your liking.

SHEET NAMES
The FORMATIONS sheet and its subsequent duplicates can be renamed to whatever you like.
However, do NOT rename the SQUAD sheet, as the name is referenced to in various formulas throughout the workbook.

THINGS TO AVOID
Please refrain from typing into any cell with a formula, unless you really know what you’re doing.
Helper columns: The hidden helper columns X, Y, Z and AA in FORMATIONS are there to make everything work behind the scenes. It’s best to leave them hidden as to not accidentally alter any of their contents.
Data Validation (Dropdown Menus): Be cautious when editing the dropdown menus as they pull data from other parts of the workbook, and editing them directly might cause them to break.


- FAQ -

WHAT IF A PLAYER GETS SCRATCHED AFTER BEING SELECTED IN PP OR BP?
Their jersey number will be highlighted (greyed out) to indicate they’re no longer available.

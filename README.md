# Cookie Clicker for Starbase Yolol

A simplified version of the classic idle game, designed for Starbase grid display.

### Gameplay
Use the switch to select up and down the screen.
When the top cookie counter is selected, press the button to make a cookie.
When a building is selected, press the button to purchase 1.

Once purchased, buildings will passively generate cookies over time. The first number shows the number of buildings currently owned, the second number is the total cookies per second created by that type of building, and the third number is the cost to purchase 1 more of that building. Cookie generation is linear with no upgrades or wait times.

### Install

1. Copy Count.yolol into a basic yolol chip.
2. Copy Buy.yolol and Display.yolol into advanced yolol chips.
3. Rename the fields in a memory chip to match Memory.txt
4. Set up an advanced grid display along with a switch and a button.
5. Rename the button to :CCB and set it to toggle mode.
6. Rename the switch to :CCN and set it to toggle mode.
7. Set the display fields as shown here:
	- MoveCursor=0
	- ShowCursor=0
	- SelectedLayer -> :CCL
	- GridLayerTextHue -> :CCH
	- CursorX -> :CCX
	- CursorY -> :CCY
	- Input -> :CCT
![](https://i.imgur.com/sqYwPkP.png)

Keyboard Wizard is a mod helps with solving key conflicts and finding unbound keys. It adds an "extra" controls gui that displays an interactive keyboard in the center.

## **Screenshots:**

![](https://i.imgur.com/pHIQ7ie.png)

![](https://i.imgur.com/nvERCtZ.png)

## **Features/Explanation:**

Keyboard Wizard can be opened by pressing F7 or clicking the added button in the controls gui (which can be removed in the config if desired).

When you open the gui you will see list of keybindings on the left, and a colored keyboard on the right.

* <span style="color:white">**White**</span> keys are unbound
* <span style="color:green"> **Green**</span> keys have only one binding
* <span style="color:red">**Red**</span> keys have more than one binding

Click a key (or the mouse button) to set the binding selected on the left to the key clicked plus the active modifier (see below).

Press the All Bindings button to select the category that will be displayed in the binding list.

Press the Active Modifier button to select the Forge key modifier (control, alt, or shift) that will be applied to newly set bindings.

The binding list on the left can be filtered by binding name using the search box underneath it. You can also filter by key name by typing @ without the brackets. Shift click a key to auto-populate the search bar with the key name.

### Changelog:

v1.7.2  
Fixed janky controls gui override  
Category list is scrolly now :)

v1.7.1  
Added extra keys  
  
v1.7  
Added search by key name  
Added numpad  
Added mouse

v1.6  
Changed how the buttons scale  
Added categories to hovering text on keys  
Category list now displays the currently selected category

v1.6b1  
Completely changed the way the keyboard is rendered  
Keyboard resizes with the Minecraft window  
Modifier keys can no longer modify themselves  
Temporarily removed numpad :(

v1.5.6  
Updated lang file to include all button labels  
Updated Russian lang file

v1.5.5  
Added a partial Russian translation

v1.5.4  
Added a button in to open keyboard wizard from the controls gui  
Added a config file with an option to disable this button  
Added a warning that will print when another  
mod that overrides the controls gui is installed (currently only Controlling)

v1.5.3  
Fixed a bug where bindings would not persist between launches  
Actions can now be properly bound to the numpad

v1.5.2  
Added compatibility for all 1.12.x versions

v1.5.1  
Moved the numpad to a new page  
Added a button to change pages  
Added more buttons to the numpad

v1.5  
Added a clear button to set the current binding to NONE  
Added a number-pad to the right of the keyboard

v1.4.5  
The category dropdown list now expands to multiple columns when there are more than 10 categories

v1.4.4  
Fixed a bug that caused the selected binding on list to not be highlighted

v1.4.3  
Added a binding category selector  
Yes I know I skipped 1.4.2, just a little trouble on the backend

v1.4.1  
Added a search bar to the bottom of the binding list  
Bindings that are not set to their default value are colored green in the list  
Shifted/resized the function keys to make them look pretty

v1.4  
Added function keys to the top of the keyboard!

v1.3  
Fixed bug where original binding would still work after being changed  
List will only be as wide as the longest name it contains

v1.2  
Added support for Forge key modifiers

v1.0  
First version!

### **1.16 UPDATE PROGRESS**

* * *

I am currently working on updating keyboard wizard to Minecraft version 1.16. I would greatly appreciate anyone who takes the time to submit pull requests over on my GitHub page. The current code is working, but undocumented.

My way of going about this update is a little convoluted, but it's the best way I could come up with. Forge, from my perspective as relative outsider to the mod community, is currently a mess. To be clear, I am not throwing shade at the Forge team. I appreciate all the blood, sweat, and tears they put into making Minecraft modding what it is today, and I wouldn't have made this mod without their work. That said, the obfuscated parameter names in the official Mojang mappings, the discontinuing of what once were the MCP mappings has made it very hard for me to re-learn how to make mods. Luckily, keyboard wizard hardly ever interacted with Forge in the first place. For those reasons, I am doing all current development in Fabric. After I get a working prototype, I will port to Forge (which should, I think, be relatively easy).

#### **Latest Development Progress and Screenshot**

I've completed the rendering code for the keyboard and the binding list. Both react to mouse input correctly. Next up will be adding the core feature of keyboard wizard, the abliity to change keybindngs at the click of a button.

Screenshot date: 1/12/2022
![](https://i.imgur.com/M87XQso.png)  

* * *

**I WILL NOT LOOK INTO ISSUES POSTED IN THE COMMENTS.**

If you have and issue or find a bug, please post a mod list, relevant logs, and steps to reproduce on [GitHub](https://github.com/MrNerdy42/Keyboard-Wizard/issues).

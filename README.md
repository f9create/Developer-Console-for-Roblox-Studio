1  ID VERIFICATION IN SCRIPT

In lines 16-20, change the cells with the numbers inside the brackets to your Roblox ID. Without your ID, the console won't open or will return an error about insufficient rights.

local ALLOWED_USERS = {
[1] = {name = "Dev", level = 3}, --Enter your ROBLOX ID
[2] = {name = "Admin", level = 2}, --Enter your ROBLOX ID
[3] = {name = "Moderator", level = 1} -- 
}

The three lines represent different levels of moderator/developer rights.

"Level 3" - unlimited rights (developer)
"Level 2" - ideal for a moderator, with limited functionality.
"Level 1" - very limited functionality


2  HOW TO USE?

It's very simple: go to File Explorer, open StarterGui, and simply add the local script with this .txt source file.


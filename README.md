# EurekaQuickTeleport
Simple code to bind shift+b and b to teleporter and base respectively with the eurika effect

If you don't know how to put this bind into tf2, go to steam right click on tf2, go to manage > browse local files, follow this path team fortress 2 > tf > cfg > and you can either put this in config.cfg (I do this on mac and it's the only method that works) or I have heard you can just drop the file into your cfg file.

if you have shift binded to crouch you can swap line 3 for this code:

alias +shift_b "+duck; wait; bind b Teleport_To_Exit"


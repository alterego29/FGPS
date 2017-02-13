* Arrow on top of your vehicle that shows will show you where to drive.
* Dynamic list. If there is no data in the database you will not see the dialog.
* You can edit names ingame with /Fedit. The old and the new name are separated by a , and no space! Example: /fedit My Old Name,New Name Goes Here!
* Plug & Play. Just put the FGPS in your filterscripts folder and add it to your server.cfg and you are done. If it is the first time you use the filterscript your server needs to restart. (Thats only to make sure everything loads to 100%)
* Textdraw that shows the distance left to your destination. You can disable this in the script.
//New UPD
*Update from samp_db to sqlitei by Slice
*Update from dcmd to zcmd by Zeex
*added sscanf by Y_Less
*added y_timers by Y_Less
*changed fsave and fedit to gpssave and gpsedit for much readabilty and to avoid duplicate command on your gamemode
*Removed every function to OnPlayerUpdate to a timer that buffers every 250milliseconds. To avoid high memory usage and for script optimization purposes
*Removed the split function on /gpssave and gpsedit, still on process of optimization on sscanf. if Fail remove commit and return split function
*NOTE: Specify the names properly, don't use test for all the names. It will be hard to change

More UPD's to come in the future

OLD THREAD by Fj0rtizFredde: http://forum.sa-mp.com/showthread.php?p=1047959
New THREAD coming soon

# Quick-symbols
A script executed with dmenu and a txt file to quickly copy/paste symbols anywhere

symbols script is based on Luke Smith's https://github.com/LukeSmithxyz/voidrice/blob/archi3/.local/bin/i3cmds/dmenuunicode emoji script, but slightly modified to check the .symbols file instead. 

# How to install
Save the .symbols file in home directory and place the script anywhere on your PATH to allow execution from anywhere.

## Dependencies
 `Dmenu`

 `xclip`

# How to use
Execute in terminal by executing the `symbols`command

or 

Bind a key to execute script in your config file such as your .i3/config 
e.g. `bindsym $mod+shift+p exec --no-startup-id ~/PATH/TO/SCRIPT/symbols`

Dmenu will then pop up with a search field, type in the desired symbol and hit enter. The symbol will then be added to both primary and clipboard and is then ready to be pasted.



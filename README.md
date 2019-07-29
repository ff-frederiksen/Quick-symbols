# Quick-symbols
A script executed with drun and a txt file to quickly copy/paste symbols anywhere

symbols script is based on Luke Smith's https://github.com/LukeSmithxyz/voidrice/blob/archi3/.local/bin/i3cmds/dmenuunicode emoji script, but slightly modified to check the .symbols file instead. 

# How to install
Save the .symbols file in home directory and place the script anywhere on your PATH to allow execution from anywhere.

# How to use
Execute in terminal by executing the `symbols`command

or 

Bind a key to execute script in your config file such as your .i3/config 
e.g. `bindsym $mod+shift+p exec --no-startup-id ~/PATH/TO/SCRIPT/symbols`

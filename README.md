# Quick Symbols

A script executed with dmenu and a txt file to quickly copy/paste symbols anywhere

symbols script is based on Luke Smith's https://github.com/LukeSmithxyz/voidrice/blob/archi3/.local/bin/i3cmds/dmenuunicode emoji script, but slightly modified to check the .symbols file instead. 

![](demo.gif)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

`dmenu`

`xclip`
 
`dunst (optional)` 
Displays notification of the clipped symbol
### Installing
Save the .symbols file in home directory and place the script anywhere on your PATH to allow execution from anywhere.

## How to use
Execute in terminal by executing the `symbols` command

or 

Bind a key to execute script in your config file such as your .i3/config 
e.g. `bindsym $mod+shift+p exec --no-startup-id ~/PATH/TO/SCRIPT/symbols`

Dmenu will then pop up with a search field, type in the desired symbol and hit enter. The symbol will then be added to both primary and clipboard and is then ready to be pasted.

## Contributing
Pull requests are welcome.

## Roadmap 
Goal is to increase the amount of symbols available to copy/paste by continously updating the `.symbols` file whenever new symbols are encountred. 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Luke smith for the original script used for quickly selecting and pasting unicode emojis. 


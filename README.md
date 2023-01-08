### Install ROFI

`sudo apt-get update && sudo apt-get install rofi`

`mkdir .config/rofi`

`sudo vim .config/rofi/config.rasi`

copy confog.rasi content from repo's file

### install papirus

`sudo add-apt-repository ppa:papirus/papirus`

`sudo apt install papirus-icon-theme`


### install rofi-power menu

`git clone https://github.com/jluttine/rofi-power-menu.git`

`mkdir ~/.local/bin`

`cd rofi-power-menu`

`cp rofi-power-menu ~/.local/bin`

`vim ~/.bashrc`

add following line 
`export PATH="$HOME/.local/bin:$PATH"`

execute bachrc 
`source ~/.bashrc`


### download JetBrainsMono font

https://github.com/ryanoasis/nerd-fonts/releases/download/v2.2.2/JetBrainsMono.zip

unzip it - move everything in that directory to ~/.fonts 

`fc-cache -fv`

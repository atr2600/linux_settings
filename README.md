# My Linux Settings

## Terminal
### ZSH (OH-MY-ZSH)
Check to see if you have ZSH first.
```
zsh -v
```
If you have it installed then skip the OPTIONAL step. 

OPTIONAL: Copy and paste this into your promt. (If you do not have ZSH)
```
sudo apt-get install zsh
```
## Window manager
### Weapon of choice TMUX
OPTIONAL: If you do not have tmux copy and past this into your terminal. 
```
sudo apt-get install tmux
```
Now to make TMUX usable...
```
git clone https://github.com/atr2600/linux_settings.git
cp linux_settings/tmux/tmux.conf ~.tmux.conf
```
Now your tmux will have mouse support and easy to use key-bindings. 
press 'CTRL+B' then 's' == Horizontal 'Split' screen
press 'CTRL+B' then 'v' == Virtical Split screen
press 'ALT' then 'arrow-key'== move to a screen. 
press 'CTR+B' the 'd' == detach screen (to start that back up just type)
```
tmux attach
```

## PROGRAMS!
### Python
STOP using the basic python app. Install IPYTHON immediatly. ipython makes coding and scripting on a terminal as easy as pressing tab. Have you ever forgot what that one function's name was? Just tab your way through the options by pressing the TAB key. Also has alot more features than that.
```
sudo apt-get install ipython
```
### Debuggers
If you must use a terminal debugger I recommend installing a nice custom python layout for your GDB. Displays all the data you want right away without having to type the commands. 

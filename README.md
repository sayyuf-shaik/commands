# commands
Linux and Python commands
## AUDIO commands
1) $ lspci -v | grep -i audio
For listing the available audio devices.
2) pacmd list-cards | grep 'name: ' --> Lists all availble sound card names.
 for getting full info type only "pacmd list-cards"
3) Sound cards on connected to the host
   cat /prco/asound/cards
4) All info related sound cards:-
    https://www.kernel.org/doc/html/latest/sound/designs/procfile.html

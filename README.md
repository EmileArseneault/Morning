# Morning

Morning is a Unix command line utility that stores messages for users to be displayed next morning.
This is aimed to help users pick up work right where they left off last night or Friday night before the weekend.
It can be used to launch custom commands each morning and to remind stuff daily.

It aims to be used as an installed command or as a portable bash script (on usb stick or other).
It also aims to be compatible on most Unix platforms like Linux flavors and OSX.

## Installation

The morning script is simply installed by putting it in /usr/bin/ on the computer.
As this folder is already in the path of Unix machines, it is now ready to use.

## Use

### In the morning
Just type in `morning` on the command line once you are logged in and the message for the day will be displayed. Depending on what you have configured, daily commands will also be executed and daily reminders shown.

### Before closing your computer
Use the morning command with the "-n" option like so :

    morning -n

This will then ask you to type a message line per line that you can end with EOL.
This message will then be displayed tomorrow morning.

If you want the message to be displayed several days after you can tell it like so :

    morning -n 3
    
You will be asked to input a message the same way and this will display the message in 3 days when you execute the morning command.

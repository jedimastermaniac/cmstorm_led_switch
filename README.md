# cmstorm_led_switch
A Led switch script for coolermaster CMStorm Keyboard for wayland


1) Place the script anywhere you want however the file must be have read and execute permissions. The script must have write permission to write in /sys/class/leds/*/. So either make a new group (e.g. name it cmstorm) with write permissions and add the user in the new group.
2) Make a shortcut to call the script.

## Change wallpaper

    feh --bg-scale [path-1] [path..n]

    mate-control-center

## Screen resolution

    xrandr 
    
    xrandr -s [widthxheight]

## Computer stats

    lshw

## Logout
   
    i3-msg exit

## Reboot

    shutdown -r now

## Shutdown

    shutdown -h now

## Kill process

    xkill

    htop

## MATE control center

    mate-control-center

## Screenshot

    sshot

    scrot '%Y-%m-%d_%H:%M:%S_$wx$h.png' -e 'mv $f ~/Pictures/Screenshots/'

    mate-screenshot

## Volume

    mate-volume-control

## Bluetooth

    bluetoothctl
      
      agent on
        scan on
        pair [mac-address]
        trust [mac-address]
        connect [mac-address]
        remove [mac-address]
    
    mate-control-center

## Screen brightness
  
  Max brightness

    /sys/class/backlight/intel_backlight/max_brightness
  
  Set brightness

    sudo vim /sys/class/backlight/intel_backlight/brightness

## System stats (incl. battery)

    sudo tlp stat

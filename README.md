# i3wm-FLCL 
## Information

*Simple Linux Configuration for FLCL Fans!* 

*The configuration was developed for **Linux Manjaro** on **i3wm**.*

## Screenshots
![Screenshot1](/.read/Screen1.png)

![Screenshot2](/.read/Screen2.png)

![Screenshot3](/.read/Screen3.png)

![Screenshot4](/.read/Screen4.png)

## Use configuration with caution!!!

### What was edited and how to apply the changes?

1. **i3wm settings**
    
    The file `/i3/config` is responsible for i3 configuration - hotkeys, keyboard layout, window behavior and display.

    Replace the file in `~/.i3/config` or your default catalog for your i3. 

    After that, reboot your i3 using the key combination `$mod + Shift + r`.

2. **Terminal urxvt (rxvt-unicode)**
    
    The file `/urxvt/Xresources` is responsible for **urxvt** parameters, such as colors, fonts, and other settings.

    Replace the file in `~/.Xresources`, then commit the changes with `xrdb ~/.Xresources`.
    
    Open the new Window. Enjoy. 

3. **Picom**

    The `/picom/picom.conf` file is responsible for effects such as transparency, shadows, window rotation and unfolding animations, and anti-aliasing for window managers.

    Replace the file in `/etc/xdg/picom.conf` or in the default directory for your picom configuration, then make changes using the `picom --config /etc/xdg/picom.conf` command.

    If you have a different picom configuration directory, find this line in the `~/.i3/config` file and replace the path with your own.:

    `picom --config /etc/xdg/picom.conf`

    After that, in any case, reboot your i3 using the key combination `$mod+Shift+ r`.

4. **Wallpapers**
   
    For to change wallpapers uses program `feh`.  

    **In the `~/.i3/config` file, find the line:**

    `/home/user_name/i3wm-FLCL/wallpapers/your_wallpaper`

    Replace `username` with your own.
    
    You can replace `wallpaper` with the name of the wallpaper you want or specify the path to the desired wallpaper directory.
   
    [Wallpaper Source](https://imgur.com/a/uEtut)

## Thank you for your attention ^w^

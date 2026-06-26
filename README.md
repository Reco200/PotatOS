# Windows 11 PotatOS
A uniform Windows 11 Windhawk theme that modifys the ugly and boring Windows 11 UI and turns it into a clean, minimalistic, blue, and Aperture Science themed from the Valve video game, Portal

# What does it look like?
## Desktop:
![image](Images/Readme/Desktop.png)

## Desktop (Open Start Menu):
![image](Images/Readme/Desktop-Open-Start-Menu.png)

## Fastfetch (Scoop):
![image](Images/Readme/Fastfetch.png)

# Installation
## Dependencies
### (You can choose which things you want to install and use in this theme)
-Windhawk

-Fastfetch (Install through terminal with Scoop [Scoop.sh])

## GUI Changesa
Install Windhawk and use the "Windows 11 Start Menu Styler" along with the "Windows 11 Taskbar Styler"

In "Windows 11 Start Menu Styler", go to the settings, and select "Textual Mode", and paste in the contents of:
`PotatOS/GUI Changes/Start Menu Styler.txt`

In "Windows 11 Taskbar Styler", again select "Textual Mode" and paste in the contents of:
`PotatOS/GUI Changes/Taskbar Styler.txt`

## Fastfetch Changes
#### This is optional
Install fastfetch with scoop (scoop.sh), and then type "fastfetch --gen-config."
After you type that, a config.jsonc file will appear in the file path `C:\Users\%USERPROFILE%\.config\fastfetch`
Replace the contents of that file with:
`Fastfetch/config.jsonc`

Once thats done, put `Fastfetch/APLOGO.txt` into the same fastfetch file as the config.jsonc.

Now, when you type fastfetch in the terminal, it should display the Aperture Science logo ASCII art and report the OS to be PotatOS.

## Background / Wallpaper
I made a wallpaper that matches the Taskbar and Start Menu:
`PotatOS/Images/Aperture Wallpaper.png`
<img width="1920" height="1080" alt="Aperture Wallpaper" src="https://github.com/user-attachments/assets/a86055a7-f210-45b4-8f60-50ff1f132417" />

# Conclusion
Once you do all that, you should have a nice, minimal looking Windows 11 themed around Aperture Science from Portal. Enjoy!
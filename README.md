# Windows 11 PotatOS
A customized Windows 11 theme inspired by Aperture Science from Portal, designed to give your desktop a clean, immersive, and experimental facility aesthetic. It transforms the look and feel of the system while preserving Windows functionality.

# What does it look like?
### Desktop:
![image](Images/Readme/Desktop.png)

### Desktop (Open Start Menu):
![image](Images/Readme/Desktop-Open-Start-Menu.png)

### Fastfetch (Scoop):
![image](Images/Readme/Fastfetch.png)

# GUI Changes
I installed Windhawk and used the "Windows 11 Start Menu Styler" along with the "Windows 11 Taskbar Styler"

In "Windows 11 Start Menu Styler", I went into the settings, selected "Textual Mode", and pasted in the contents of:
`PotatOS/GUI Changes/Start Menu Styler.txt`

In "Windows 11 Taskbar Styler", I again selected "Textual Mode" and pasted in the contents of:
`PotatOS/GUI Changes/Taskbar Styler.txt`

This changes the Windows icon to the Aperture Science logo. Because of that, the icon path is hardcoded in the settings file.

In line 164 of the settings, you will need to replace "YOUR USERNAME" with your Windows username:

```xml
Background:=<ImageBrush Stretch="Uniform" ImageSource="C:\Users\YOUR_USERNAME\PotatOS\Images\Aperture.ico" />
```

# Fastfetch Changes
### This is not required
Install fastfetch with scoop (scoop.sh), and then type "fastfetch --gen-config."
After you type that, a config.jsonc file will appear in the file path "C:\Users\Your-Username\.config\fastfetch"
Replace the contents of that file with [INSERT FILE NAME HERE]

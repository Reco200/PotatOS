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
PotatOS/GUI Changes/Start Menu Styler.txt (found in that folder in the repo)

In "Windows 11 Taskbar Styler", I, again selected "Textual Mode" and pasted in the contents of:
PotatOS/GUI Changes/Taskbar Styler.txt

This changed the Windows icon to the Aperture Science logo. This complicates things if you want to follow along, due to the fact that in line 164 of the settings that I changed, I had to specify the file path (e.g Background:=<ImageBrush Stretch="Uniform" ImageSource="C:\Users\John Smith\PotatOS\Images\Aperture.ico" />) 

This is important, because, if you want to follow along, you will have to clone the repo and edit line 164 of the settings to: 
Background:=<ImageBrush Stretch="Uniform" ImageSource="C:\Users\YOUR USERNAME HERE\PotatOS\Images\Aperture.ico" />)
Replace "YOUR USERNAME HERE" with, you guessed it, your username.

# Fastfetch Changes
I do not currently have the mental capcity to document this

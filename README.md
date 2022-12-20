# Horizons-XI Lutris installer

### Horizons-XI.yaml
Basic install script that download and autoconifgs most of the headaches
of linux installation.

#### Requirements
You need to have wine-staging installed. 
  - [Winehq](https://wiki.winehq.org/Download)
Go to the link above and install based on your distribution. Remember you
need **WINE-STAGING-7.22!**

#### Features
- HorizonXI Launcher v1.1.0
- DGVOODOO
  - Auto configured for 4gb VRAM so if you have less than that you'll
    need to adjust the setting in the Install script.
    VRAM: 4096 - 4gb
          3072 - 3gb
          2048 - 2gb
          1024 - 1gb
         
#### Installation
1. Download the Horizon-XI.yaml from the repo.
2. Open Lutris hit the (+)plus in the top left.
3. Select install from YAML file
4. Navigate to the .yaml file you downloaded
5. Follow the steps of the installer.
6. Once it's complete hit **close**
7. Right click on the new install and hit configure
8. Go to the runners tab and change the runner to wine-staging 7.22
9. Save and run the installer like normal.

Note: You might get an error about missing the prereqs.zip, you
      can ignore this.
      
### Horizon-XI_Windower.yaml
Converts the HorizonXI setup to Windower.

#### Requirements
- You need to have Horizon-XI.yaml installed.
- The HorizonXI Launcher must complete the installation process
  or you will be missing files.
Note: ***The above requirements are critical, if you @me in the discord 
       this is going to be the first thing I'll ask :)***
       
#### Installation
1. Download the Horizon-XI_Windower.yaml from the repo
2. Open Lutris hit the (+)plus in the top left.
3. Select install from YAML file
4. Navigate to the .yaml file you downloaded
5. Follow the steps of the installer. ***READ EVERY PROMPT***
6. Windower will launch, just let it download everything. Once you see the
   Default Profile you can close it and the installer will continue.
7. At some point a notepad should popup.
  - You will need to replace the following with your login details.
    - UserNameHere - replace with your username
    - PasswordHere - replace with your password
    Completed entry should look like this: 
    ```<args>--server horizonxi.com --user UserNameHere --password PasswordHere</args>
    
    <args>--server horizonxi.com --user ffxibadass --password reallygoodpassword</args>
    
   Note: This file is stored locally on your PC, I can't get access to it. If you're
   not comfortable please don't use this script.
8. Save and close the notepad.
9. Once the DATs are copied over from the HorizonXI Launcher folder
   another notepad will open. This is your init.txt file I've pre
   configured it to load the DATs, and set the FPS. If you know what
   you're doing make any edits you like otherwise just review and 
   close notepad.

That's it your done. You can launch windower and play the game.

Note: Windower has an issue with keyboard input. There's an addon under the addons section
      on windower called linuxfix. It will solve this issue but just take note that it is 
      currently ***not on the approved addon list***. I've already asked for approval so it 
      shouldn't take to long but be smart in the meantime.

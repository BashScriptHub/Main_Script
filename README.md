

# So what is /GitHub, /Installer and /Main folder used for?

They are components of the main script. /Installer installs the script.
/Main runs the script.
/GitHub is used to push commits to GitHub! As this is in active Devlopement!

https://GitHub.com/BashScriptHub/Docs coming soon

# Installing

First of all git clone this repo
```
git clone https://github.com/BashScriptHub/Main_Script.git
```
2nd of all cd into the the git directory and then cd into  /Installer directory

```
cd Main_Script && cd Installer
```

Run install.sh

```
bash install.sh
``` 
Or..
```
chmod +x install.sh && ./install.sh
```

Cd into the main directory and run the program

```
cd .. && cd Main && bash main.sh
```

All in one line (for firt time use only)

```
git clone https://github.com/BashScriptHub/Main_Script.git && cd Main_Script && cd Installer && bash install.sh && cd .. && cd Main && bash main.sh
```

Make a bash script to run the program (optional)

Run the script manully
```
cd Main_Script && bash Main/main.sh
```

Or make a sh file

```
echo "Running Main_Script
cd Main_Script
cd Main
```
bash main.sh

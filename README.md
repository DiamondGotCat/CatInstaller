![Icon](CatInstaller.png)

# CatInstaller
CatInstaller is an installer that allows you to easily install something on your OS.

All you need is Python and the necessary modules.

## How to Use

First, install "rich" and "requests" in "pip" command.

```
pip install rich requests
```

Next, download Source Code from Relase tab, and Extract zip file.

Next, use cd (current directory) in the terminal (command prompt) to go to the extracted folder and execute the following command.

```
python -m CatInstaller.Installer
```

Finally, specify the repository location of the project you want to install as follows:

```
/DiamondGotCat/cat-installer-test/
```
The installation will then begin.

However, it is only available in supported repositories.

## How to support CatInstaller


To support CatInstaller, simply write a program in a Python file.

Upload Installer.py to GitHub and it will be ready for installation.

Installer.py must be written in the following format.

```

  # Installer.py

  requiments = ["time"] # Enter the required Python modules here.

  numbersofprogress = 10 # Enter the steps

  import time # import required python modules

  def install(progress): # "progress" is number of steps
      print("Output ", progress) # Enter the install process here.

  # ↓ Enter the other functions...

```

## Lisence
It's MIT Lisence.

Copyright (C) 2023 TechCat56

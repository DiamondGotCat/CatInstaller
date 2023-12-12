# CatInstaller
CatInstaller is an installer that allows you to easily install something on your OS.

All you need is Python and the necessary modules.

# How to Use
First, install CatInstaller using PIP by running the command below.
```
pip install CatInstaller
```
Next, run the command below to start CatInstaller.
```
python -m CatInstaller.CatInstaller
```
Finally, enter the location of your repository in GitHub and press enter.

The input is as follows.
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

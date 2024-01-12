# Noob-instructions-Bereel
##### A step by step guide for non-coders to set up and use BeReel, the tool created by TheOneAndOnlyOne

Disclaimer: 
* I am a first year CS student, there are prolly a lot of better ways to do this :)
* I also have absolutely nothing to do with the BeReel project or TheOneAndOnlyOne

If you are using a Mac, please follow [this guide](Mac.md)

## Installing git bash:
windows, unlike mac or linux, does not have a bashy terminal, which is required to run git (the tool that will download BeReel to your computer)

### 1. Open up a browser and head over to gitforwindows.org
* ![./Images/gitDownload.png](/Images/gitDownload.png)

### 2. Install git bash
* the default settings should be fine, so just hit next over and over until its installed
* ![./Images/gitInstall.png](/Images/gitInstall.png)

### 3. Install Python
* open the windows store and search for python 3.11
* ![./Images/MsStore.png](/Images/MsStore.png)

click on "get"
* ![./Images/getPython.png](/Images/getPython.png)

### 4. Install FFmpeg
BeReel uses a video editing tool called FFMpeg, which needs to be installed.
* go to https://github.com/BtbN/FFmpeg-Builds/releases
* click on `ffmpeg-master-latest-win64-gpl.zip`
* ![./Images/zipDownload.png](/Images/zipDownload.png)
* click open file from your downloads menu
* ![./Images/openZip.png](/Images/openZip.png)
* open the folder called `ffmpeg-master-latest-win64-gpl`
* open the folder called `bin`
* double click the file called `ffmpeg.exe`
* ![./Images/clickExeFile.png](/Images/clickExeFile.png)
* click `Run`
* ![./Images/runThoZipped.png](/Images/runThoZipped.png)
* click `more info`
* ![./Images/moreInfo.png](/Images/moreInfo.png)
* click `run anyway`
* ![./Images/runAnyways.png](/Images/runAnyways.png)

### 5. Download and run BeReel
* go to any folder on your computer that you want BeReel to be on (ie documents or something like that)
* Right click inside of the folder
* click `show more options`
* ![./Images/moreOptions.png](/Images/moreOptions.png)
* click `open git bash here`
* ![./Images/openGitBash.png](/Images/openGitBash.png)
* on this black terminal screen, type `git clone https://github.com/theOneAndOnlyOne/BeReel.git`
* hint: paste by right clicking and choosing paste, and remove any extra crap if it adds stuff
* in the terminal type `cd BeReel`
* type `pip install -r requirements.txt --user`
* type `python3 main.py`
* open a browser and go to http://localhost:5000/
* All Set!
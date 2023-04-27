# PPPAutoDown
This is a repository to share the PPPAutoDown app, a free app to easily download precise products from the Center for Orbit Determination in Europe (CODE), as RINEX observation and navigation of CUT0 IGS station located at Curtin University, Perth, Australia.

I created it for fun using **ChatGPT :)**

How to install:
--------------------------------
If you have MATLAB Runtime compiler, Simply click on `PPPAutoDown.exe` in `for_redistribution_files_only` folder.

Otherwise, Intall it using `PPPAutoDownInstaller_web.exe` in for_redistribution folder. It will install the MATLAB Runtime compiler and the PPPAutoDown app.

**Important Note:** I recommend you run the app as administrator. In some PCs, the Windows firewall doesn't let the app download the files. There are two ways to run it as administrator:
1. Right-click on the app icon and select `Run as administrator
2. Right-click on the main app icon (not the shortcut on the desktop, it is mainly available on C:\Program Files\PPPAutoDown\application) -> Properties -> Compatibility -> tick Run this program as an administrator

How to use:
--------------------------------
1. Select a folder to save the downloaded files,
2. Select the requested date
3. Tick which of the following files should be downloaded:
  -SP3:   Precise Ephemeris files including precise coordinates of GNSS satellites
  -CLK:   Precise clock information of GNSS satellites (two files with different sample intervals will be downloaded: 5 min and 5 s files)
  -ERP:   Earth Rotation Parameters
  -BIA:   Bias files for the integer ambiguity resolution
  -YYn:   RINEX Navigation file including broadcast ephemeris of GNSS satellites
  -CUT0:  RINEX Observation file of CUT0 station. (CUT0 is an IGS station located at Curtin University, Perth, Western Australia) 
4. Press Download
5. You can reset everything by pressing Reset

**Amir Allahvirdi-Zadeh** (<a href="mailto:amir.allahvirdizadeh@curtin.edu.au">email me for any enquiry</a>)
  

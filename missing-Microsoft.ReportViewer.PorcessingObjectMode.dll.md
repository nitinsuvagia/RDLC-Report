Found out that this error means that you are missing Microsoft.ReportViewer.PorcessingObjectMode.dll version 11.0.0.0. There is one solution:

# On your Windows 8 Machine do following:

```
Open dos command prompt (press START + R then type cmd and press ENTER)

Type cd .. until you are on C:\ > Type Cd windows\assembly\gac_msil\Microsoft.ReportViewer.pro* and press enter

Just type cd 11*

Then type copy * c:\

The .dll will be copied to your C directory.

```
This file simply copy into your Program Files on Windows XP machine to folder where your application has been installed.

Hope it helps to others as I was stuct with this issue for long time.

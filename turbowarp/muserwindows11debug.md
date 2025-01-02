# Turbowarp: Muser Windows 11: Debug
## The beta versions is only for PRO users
I can barely say, this is only feature in beta. So please don't say that does not exist because you don't search properly. 
## The "ViewAllVariables"
This option makes every variable visible.
## The "noBetaWarnText"
This option let user hide text with beta version 
## The "debugTestUI"
This option changes User Interface to it's debug version 
***
![Version 1 of an Debug User Interface](https://upload-and-view.github.io/turbowarp/assets/image1.png)
_Version 0KB2025010201_
***
![Version 2 of an Debug User Interface](https://upload-and-view.github.io/turbowarp/assets/image2.png)
_Version Beta 1_
***
# Bugs
![Bug 1 in Version 2 of Debug User Interface (Content does not hide)](https://upload-and-view.github.io/turbowarp/assets/image3.png)\
_Version Beta 1_ (*that should not been, bug 1*)
## How to fix them
### Bug 1
*** 
The fix is simple: Add an variable, whenever window hides, it will set variable to False, and if window is visble, it will be True, and show context only if variable is True.
Status: Fixed

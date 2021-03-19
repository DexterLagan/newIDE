# newIDE
newIDE is an Integrated Development Environment for the newLISP language.

<p align="center"><img src="Screenshots/Splash.PNG"></p>

What's ready:
- full syntax highlighting for newLISP;
- dockable REPL with shortcuts to common operations;
- load, save, save as, display recent files;
- evaluate newLISP code in the REPL;
- evaluate the current source file in the REPL;
- compile the current source file into a standalone binary;
- build & run the current program in one click;
- advanced search & replace, lets one replace selected lines by a pattern, as well as replace all matches;
- integrated online help with newLISP Web site search;
- integrated GUI module help tab;
- integrated newLISP forum browser tab;
- compiles and runs on MacOSX High Sierra;
- working directory is handled correctly to allow newLISP imports to find their files (i.e. (load “genann.lsp”) works as expected.

What's not quite ready:

- the dylib isn’t being found by the compiler at import time and therefor loading/saving settings isn’t working yet as it relies on the newLISP.dylib library to evaluate settings files;

# Downloads

You can <b>download</b> the latest release for <b>Windows</b> and <b>MacOSX</b> [HERE](https://github.com/DexterLagan/newIDE/releases/tag/v1.0.133).

# Features

The <b>Editor</b> lets one create and edit newLISP source files (.lsp). There is an integrated REPL which uses the bundled newLISP module to interactively evaluate newLISP code. One can also build the currently loaded source code into a standalone binary, and run it in one click:

<p align="center"><img src="Screenshots/REPL.PNG"></p>

The <b>Search & Replace</b> dialog is an advanced replacement tool, which displays matching lines and highlights the pattern. You can selectively replace the pattern in all or only selected lines:

<p align="center"><img src="Screenshots/Replace.PNG"></p>

The <b>Online Help</b> window displays the newLISP manual in an integrated browser:

<p align="center"><img src="Screenshots/Help-Manual.PNG"></p>

The <b>GUI Manual</b> displays the newLISP GUI module manual in a separate tab:

<p align="center"><img src="Screenshots/Help-GUI.PNG"></p>

The <b>Online Search</b> tab searches the newLISP Web site for any search pattern:

<p align="center"><img src="Screenshots/Help-Search.PNG"></p>

The <b>Forum</b> tab opens the newLISP forum in an integrated browser:

<p align="center"><img src="Screenshots/Help-Forums.PNG"></p>


Cheers,

Dexter

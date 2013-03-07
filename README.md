# madhuri

A collection of code for learning Houdini development

# Installing Houdini Apprentice

Go to [www.sidefx.com/apprentice/][] and click on the "Download Apprentice" option from the free-edition column.  

For Ubuntu Linux, this gave me a tar.gz file I extracted to the temp directory.  Inside was an install script called "houdini.install" as root.  

    sudo ./houdini.install

This will take you through the install process.  Be sure to include the "Apprentice Licensing" option instead of "Commercial License Server" and you have the appropriate version of your architecture (32-bit for 64-bit).  After going through the rest of the default options, this installed Houdini in /opt/hfs12.1.230.  

After the install completes, run "installDesktopIcons.py" to get the icons linking to the install.  Run "Houdini FX", not "Houdini", to get the full version with all the capabilities.  

# Installing Houdini Developer Kit

The developer toolkit now comes installed with Houdini and can be found in the "toolkit" directory under the Houdini install.  



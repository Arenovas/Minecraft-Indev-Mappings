# Minecraft-Indev-Mappings
Java Mappings and Patch File for Minecraft Indev 02-23-2010

These mappings are made for use with Fabric's version of Enigma found here: https://maven.fabricmc.net/cuchaz/enigma/
Mappings made on 0.14.3.147.

Simply open it up, select the Indev 02-23-2010 jar and then open the mappings using Enigma Directory.

Once it's been loaded, export the source files. Then remove the Paulscode folder and /com/jcraft folder. After all that is done, apply the patch file.

To use the patch file, make sure to install this program if using Windows: http://gnuwin32.sourceforge.net/packages/patch.htm
Make sure to include the Gnuwin32\bin folder in the User Variables Path in Environment Variables for this to work.
Then go and use this command in the command prompt to apply the patch file onto the source code: patch --binary -p1 -u -i "patchfile" -d "srcdir"

If everything was done right then the source should have been patched and it should be ready to be modified!

Do feel free to make pull requests to help update the mappings and patch file further since there's still bound to be various inaccuracies and bugs hiding away.

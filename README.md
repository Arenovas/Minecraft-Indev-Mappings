# Minecraft-Indev-Mappings
Java Mappings and Patch File for Minecraft Indev 02-23-2010

These mappings are made for use with Fabric's version of Enigma found here: https://maven.fabricmc.net/cuchaz/enigma-swing/0.27.3/
Mappings made on enigma-swing-0.27.3-all. This version of Enigma is required so that the patch works correctly..

Simply open it up, select the Indev 02-23-2010 jar and then open the mappings using Enigma Directory.

Once it's been loaded, export the source files using Procyon. Then remove the Paulscode folder and /com/jcraft folder. It's good to know that the decompilation can be glitchy sometimes so if you want to check if it is decompiled correctly or not, search all .java files for the word bytecode. If it appears anywhere that isn't the Paulscode or /com/jcraft folders, then decompile it again until it doesn't appear. After all that is done, apply the patch file.

To use the patch file, make sure to install this program if using Windows: http://gnuwin32.sourceforge.net/packages/patch.htm
Make sure to include the Gnuwin32\bin folder in the User Variables Path in Environment Variables for this to work.
Then go and use this command in the command prompt to apply the patch file onto the source code: patch --binary -p1 -u -i "patchfile" -d "srcdir"

If everything was done right then the source should have been patched and it should be ready to be modified!

Do feel free to make pull requests or bug reports to help update the mappings and patch file further since there's still bound to be various inaccuracies and bugs hiding away.

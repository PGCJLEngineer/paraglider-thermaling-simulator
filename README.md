# paraglider-thermaling-simulator
A basic thermaling simulation for paragliders and hang glider pilots

WINDOWS XP, 7, 8
Download the RESOURCES file
Download the windows executable file.
Create a local folder on your PC
Extract the executable file into this folder
Create a subfolder called RESOURCES
Extract the contents of the RESOURCES file into this sub-folder (This is important)
Run the apploication by executing the executable file.

The source code will work on any machine with PYTHON and PYGAME installed
But the windows executable has been built to automatically include this.

LINUX:
The simulation is provided as PYTHON source code. 
REQUIREMENTS:
You need to install PYTHON 2.7.x
You need to install PYTHON PYGAME 
This is easily done using your preferred package manager

Download the RESOURCES file
Download the PYTHON source file. 
Copy them to a suitable folder.
Extract the source file
Create a subfolder called RESOURCES
Extract the contents of the RESOURCES file to this new folder

Run the python application 
Have fun.

I have just completed a NEW VERSION of a (possibly) useful game as a learning aid for
thermal flying. And of course a bit of fun for the cold wet and windy
days we have at the moment. I developed this using Python on Linux 
and compiled it for Windows using PyInstaller. 

Download the file at the bottom of this page. You may need to right click and save as...
The file will extract to a folder containing the images and audio beeps
and an executable which runs the actual application (Ver_009.exe).

Note that you may need to put everything except the actual executable 
into a folder called 'resources' as the WinZip utility managed to mess
this up and I have only just noticed. Create a 'resources' folder and place everything 
except the executable into it. It should look a bit like this.

And today I added the pre-thermal.ogg audio file to supplement the current 
variometer sounds. Download the file called pre-thermal.ogg from the link
below and copy it into the resources folder.




I have just tested it and it works on WinXP and usually Win7. 
Others have reported it works on Win8. It does NOT run in WINE in LINUX.
A LINUX version is available on request. If you want it on a Mac, you will 
need to contact me. 

You can extract the files to any suitable folder on your PC and create a 
link to the executable if you wish or run it directly. 

It will not install anything extra on the machine nor will it affect 
registry entries etc. To remove the application, just delete all 
the files. No internet connection is required.

I don't claim that the application is absolutely complete and without
bugs but it is reasonably functional at the moment.

Currently implemented controls are as follows

> = Turn Right
< = Turn Left
Up Arrow = Speed Bar
Down Arrow = Apply Minimum Sink

a = Toggle Audio (on/off)
e = Toggle Big Ears
c = Collapse Wing
k = Attempt recovery from a collapse
p = Pause the simulation
t = Toggle visibility of the thermals
s = toggle visibility of sink patches
q = Quit
r = Throw reserve
w = Toggle the wind direction indicator 
Number pad '+' = Add another thermal
Number pad '-' = Add another patch of sink
Normal '-' = Add another patch of sink
Normal '=' = Add another thermal

The idea is to provide a simple simulation of thermaling. You can show that
increased speed increases sink rate but may improve a glide into wind. You can
also see that slowing in lift has a net improvement. 

These things are often difficult to visualise at first.

The main idea is that this is really an educational aid rather than a game. 
Ideally it is to be used alongside some discussion from an existing pilot.

The limitations and compromises made by such a simulation can stimulate discussion 
about real world conditions.

For the gifted, try thermaling without looking at the thermals (press 't')
or even better, try not looking at the screen at all and just use the simplified
vario noises. If you can do this, you have probably cheated!

I may add some more functions later. I can think of lots of potential
improvements but they are really just complications to what should be 
a simple game.






The application may be updated but I expect to keep this one for a while.

Last Updated Tuesday 21-2-2017

Added additional audio file to the resources folder to enable a 
pre-thermal sound when the sink rate is less than the glider sink rate.
Previous Version added: Big ears, collapses at random and in strong lift along with a fancy reserve parachute.



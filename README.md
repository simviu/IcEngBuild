# IcEngBuild

Pre-Build binary of I-Cube 3D Engine.

Download IcEng source code for header and project files first,

from http://www.github.com/simviu/iceng .

Then download the zip file for the OS platform you are working on,
unzip and copy to IcEng/IcEngBuild/PLATFORM_NAME. 
Then you can link your project with the IcEng binary library.

Or you can pull all the zips for all platforms.

If the binary lib has problems, you can build by yourself
by the project files provided in IcEng.

# winDepLib
winDepLib.zip is the windows dependency library, contatin FreeGlut and Glew binary,
which is needed for building IcEng App on windows. Download and unzip winDepLib.zip into IcEng/proj/windows/ for Visual Studio to find them.
You can also download FreeGlut and Glew yourself,
and re-orgnize the directory and files structure in same way, for the convenience of project setting of Visual Studio.

# License
Free BSD license, check LICENSE file.

# Contact
support@simviu.com



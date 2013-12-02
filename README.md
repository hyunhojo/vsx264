vsx264
======

vsx264 is a fork from x264 to support Visual Studio.

x264 is a free software library and application for encoding 
video streams into the H.264/MPEG-4 AVC compression format, 
and it released under the terms of the GNU GPL. 
http://www.videolan.org/developers/x264.html


Build environment
======
* Visual Studio 2008 (Visual Studio 2010, 2012, 2013 may be supported)
* Intel Compiler 

Since x264 employs C99, Intel Compiler is needed. 


How to compile vsx264 on windows from source code
======
* Install Visual Studio 2008 and Intel Compiler
* git checkout vsx264
* Open the solution file ( ./build/win32/x264.sln )
* Set the release or debug mode 
* Compile (F7), Run (Ctrl+F5) in Visual Studio


Default encoding option is -o result.264 -q 22 --input-res 352x288 -v foreman.yuv
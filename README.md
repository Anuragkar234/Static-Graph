# Static Graph Generator
An Open-Gl 2D graph generator using `C++`

## Setting up OpenGL in Visual Studio 2017
 1. Download `GLUT` `header`, `lib`, and `dll` files from [OpenGL website](https://www.opengl.org/resources/libraries/glut/glutdlls37beta.zip)
 2. Now navigate to *C:\Program Files(x86)\Microsoft Visual Studio\2017\Community\VC\Tools\MSVC\{14.16.27023}\include*
 3. Create A folder named *GL* and open it.
 4. Paste the `glut.h` header file in the destination.
 5. Now navigate to *C:\Program Files (x86)\Microsoft Visual Studio\2017\Community\VC\Tools\MSVC\{14.16.27023}\lib\x86*
 6. Paste the `glut32.lib` header file in the destination.
 7. Now navigate to *C:\Windows\System32*
 8. Paste the`glut.dll` and `glut32.dll` there too.
 9. Now create a new windows console application(`cpp`).(`WCA Visual C++`). 
10. Open `Project > Properties`.
11. Naviagte to `Confurigation > All Confurigation > Confurigation Properties > C/C++ > Precompiled headers`.
12. Change the `precompiled Header` to `Not Using Precompiled Header`.
13. Naviagte to `Confurigation Properties > Linker > Input > Additional Dependencies > Edit`
14. Now type the following in the type-space
    `opengl32.lib`
    `glu32.lib`
    `glut32.lib`
 15. Now clone or download the zip files and move to the desired *directory* of visual stdio.
 16. `Build` the given solution and finally `run` the soultion.
 

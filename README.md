# README #

Volume Renderer is a simple volume rendering program based on VTK and Qt.
It uses the vtkSlicerGPURayCastVolumeMapper from Slicer (https://www.slicer.org/) to render volume data and widgets from CTK (www.commontk.org) to display the properties of volume data.

** 2016-11-13 Update: The project has been updated and successfully built with CMake 3.7, VTK 7.1, Qt 5.7 and Visual Studio 2015. **

** 2015-09-14 Update: The CTK widgets in this project are only a small subset of the CTK library downloaded on 14 September 2015 from https://github.com/commontk/CTK **

** CMake settings for this project **  
set(VTK_DIR "D:/VTK/VTK-7.1.0.rc2/build" CACHE PATH "VTK directory")  
set(QT_QMAKE_EXECUTABLE "D:/Qt/Qt5.7.0/5.7/msvc2015/bin/qmake.exe" CACHE PATH "Qt qmake.exe")  
set(CMAKE_PREFIX_PATH "D:/Qt/Qt5.7.0/5.7/msvc2015" CACHE PATH "Qt directory")  

** CMake settings for building VTK **  
set(VTK_DIR "D:/VTK/VTK-7.1.0.rc2/build" CACHE PATH "VTK directory")  
set(QT_QMAKE_EXECUTABLE "D:/Qt/Qt5.7.0/5.7/msvc2015/bin/qmake.exe" CACHE PATH "Qt qmake.exe")  
set(CMAKE_PREFIX_PATH "D:/Qt/Qt5.7.0/5.7/msvc2015" CACHE PATH "Qt directory")  
set(VTK_QT_VERSION 5 CACHE STRING "Qt version")  
set(VTK_NO_LIBRARY_VERSION ON CACHE BOOL "VTK_NO_LIBRARY_VERSION")  
set(VTK_Group_Qt ON CACHE BOOL "VTK_Group_Qt")  
set(Module_vtkGUISupportQt ON CACHE BOOL "Module_vtkGUISupportQt")  
set(Module_vtkGUISupportQtOpenGL ON CACHE BOOL "Module_vtkGUISupportQtOpenGL")  
set(Module_vtkRenderingQt ON CACHE BOOL "Module_vtkRenderingQt")  
set(BUILD_TESTING OFF CACHE BOOL "BUILD_TESTING")  
set(VTK_RENDERING_BACKEND_DEFAULT "OpenGL")  

You might also be interested in my article on volume rendering and VTK (in Chinese)
http://blog.csdn.net/winark/article/details/9069579

### Screenshots ###

** vtkSlicerGPURayCastVolumeMapper
* ![heart.png](https://bitbucket.org/repo/R56p67/images/449342279-heart.png)

** vtkGPUVolumeRayCastMapper
* ![1.png](https://bitbucket.org/repo/R56p67/images/1364252391-1.png)
* ![2.png](https://bitbucket.org/repo/R56p67/images/1505056923-2.png)

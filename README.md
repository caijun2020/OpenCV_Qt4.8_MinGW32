# OpenCV_Qt4.8_MinGW32
Based on the source code of OpenCV3.4.12, modified to support Qt4.8 built by mingw32


Source code from opencv.org:
opencv-3.4.12.zip


Modified to support Qt4 mingw32 build:
opencv-3.4.12-modified-for-Qt4.zip




How to fix build error:
1.编译到48%时遇到如下错误：

[ 47%] Building CXX object modules/imgcodecs/CMakeFiles/opencv_imgcodecs.dir/opencv_imgcodecs_main.cpp.obj
[ 47%] Linking CXX shared library ..\..\bin\libopencv_imgcodecs3412.dll
[ 47%] Built target opencv_imgcodecs
[ 47%] Building CXX object modules/videoio/CMakeFiles/opencv_videoio.dir/src/videoio_registry.cpp.obj
[ 47%] Building CXX object modules/videoio/CMakeFiles/opencv_videoio.dir/src/videoio_c.cpp.obj
[ 47%] Building CXX object modules/videoio/CMakeFiles/opencv_videoio.dir/src/cap.cpp.obj
[ 47%] Building CXX object modules/videoio/CMakeFiles/opencv_videoio.dir/src/cap_images.cpp.obj
[ 47%] Building CXX object modules/videoio/CMakeFiles/opencv_videoio.dir/src/cap_mjpeg_encoder.cpp.obj
[ 47%] Building CXX object modules/videoio/CMakeFiles/opencv_videoio.dir/src/cap_mjpeg_decoder.cpp.obj
[ 48%] Building CXX object modules/videoio/CMakeFiles/opencv_videoio.dir/src/container_avi.cpp.obj
[ 48%] Building CXX object modules/videoio/CMakeFiles/opencv_videoio.dir/src/cap_cmu.cpp.obj
[ 48%] Building CXX object modules/videoio/CMakeFiles/opencv_videoio.dir/src/cap_dshow.cpp.obj
In file included from D:/Qt/mingw32/i686-w64-mingw32/include/DShow.h:40:0,
                 from D:\Software\OpenCV\Linux\opencv-3.4.12\modules\videoio\src\cap_dshow.cpp:112:
D:/Qt/mingw32/i686-w64-mingw32/include/strmif.h:15380:2: warning: #warning COM interfaces layout in this header has not been verified. [-Wcpp]
 #warning COM interfaces layout in this header has not been verified.
  ^
D:/Qt/mingw32/i686-w64-mingw32/include/strmif.h:15381:2: warning: #warning COM interfaces with incorrect layout may not work at all. [-Wcpp]
 #warning COM interfaces with incorrect layout may not work at all.
  ^
D:/Qt/mingw32/i686-w64-mingw32/include/strmif.h:15410:2: warning: #warning COM interfaces layout in this header has not been verified. [-Wcpp]
 #warning COM interfaces layout in this header has not been verified.
  ^
D:/Qt/mingw32/i686-w64-mingw32/include/strmif.h:15411:2: warning: #warning COM interfaces with incorrect layout may not work at all. [-Wcpp]
 #warning COM interfaces with incorrect layout may not work at all.
  ^
In file included from D:\Software\OpenCV\Linux\opencv-3.4.12\modules\videoio\src\cap_dshow.cpp:116:0:
D:/Qt/mingw32/i686-w64-mingw32/include/bdaiface.h:153:2: warning: #warning COM interfaces layout in this header has not been verified. [-Wcpp]
 #warning COM interfaces layout in this header has not been verified.
  ^
D:/Qt/mingw32/i686-w64-mingw32/include/bdaiface.h:154:2: warning: #warning COM interfaces with incorrect layout may not work at all. [-Wcpp]
 #warning COM interfaces with incorrect layout may not work at all.
  ^
In file included from D:\Software\OpenCV\Linux\opencv-3.4.12\modules\videoio\src\cap_dshow.cpp:116:0:
D:/Qt/mingw32/i686-w64-mingw32/include/bdaiface.h:189:2: warning: #warning COM interfaces layout in this header has not been verified. [-Wcpp]
 #warning COM interfaces layout in this header has not been verified.
  ^
D:/Qt/mingw32/i686-w64-mingw32/include/bdaiface.h:190:2: warning: #warning COM interfaces with incorrect layout may not work at all. [-Wcpp]
 #warning COM interfaces with incorrect layout may not work at all.
  ^
D:/Qt/mingw32/i686-w64-mingw32/include/bdaiface.h:221:2: warning: #warning COM interfaces layout in this header has not been verified. [-Wcpp]
 #warning COM interfaces layout in this header has not been verified.
  ^
D:/Qt/mingw32/i686-w64-mingw32/include/bdaiface.h:222:2: warning: #warning COM interfaces with incorrect layout may not work at all. [-Wcpp]
 #warning COM interfaces with incorrect layout may not work at all.
  ^
In file included from D:\Software\OpenCV\Linux\opencv-3.4.12\modules\videoio\src\cap_dshow.cpp:116:0:
D:/Qt/mingw32/i686-w64-mingw32/include/bdaiface.h:280:2: warning: #warning COM interfaces layout in this header has not been verified. [-Wcpp]
 #warning COM interfaces layout in this header has not been verified.
  ^
D:/Qt/mingw32/i686-w64-mingw32/include/bdaiface.h:281:2: warning: #warning COM interfaces with incorrect layout may not work at all. [-Wcpp]
 #warning COM interfaces with incorrect layout may not work at all.
  ^
D:/Qt/mingw32/i686-w64-mingw32/include/bdaiface.h:320:2: warning: #warning COM interfaces layout in this header has not been verified. [-Wcpp]
 #warning COM interfaces layout in this header has not been verified.
  ^
D:/Qt/mingw32/i686-w64-mingw32/include/bdaiface.h:321:2: warning: #warning COM interfaces with incorrect layout may not work at all. [-Wcpp]
 #warning COM interfaces with incorrect layout may not work at all.
  ^
D:/Qt/mingw32/i686-w64-mingw32/include/bdaiface.h:381:2: warning: #warning COM interfaces layout in this header has not been verified. [-Wcpp]
 #warning COM interfaces layout in this header has not been verified.
  ^
D:/Qt/mingw32/i686-w64-mingw32/include/bdaiface.h:382:2: warning: #warning COM interfaces with incorrect layout may not work at all. [-Wcpp]
 #warning COM interfaces with incorrect layout may not work at all.
  ^
D:/Qt/mingw32/i686-w64-mingw32/include/bdaiface.h:411:2: warning: #warning COM interfaces layout in this header has not been verified. [-Wcpp]
 #warning COM interfaces layout in this header has not been verified.
  ^
D:/Qt/mingw32/i686-w64-mingw32/include/bdaiface.h:412:2: warning: #warning COM interfaces with incorrect layout may not work at all. [-Wcpp]
 #warning COM interfaces with incorrect layout may not work at all.
  ^
In file included from D:/Qt/mingw32/i686-w64-mingw32/include/DShow.h:40:0,
                 from D:\Software\OpenCV\Linux\opencv-3.4.12\modules\videoio\src\cap_dshow.cpp:112:
D:/Qt/mingw32/i686-w64-mingw32/include/strmif.h:15382:95: note: #pragma message: Interface IAMAsyncReaderTimestampScaling has unverified layout.
 __MINGW_BROKEN_INTERFACE(INTERFACE)
                                                                                               ^
D:/Qt/mingw32/i686-w64-mingw32/include/strmif.h:15412:81: note: #pragma message: Interface IAMPluginControl has unverified layout.
 __MINGW_BROKEN_INTERFACE(INTERFACE)
                                                                                 ^
In file included from D:\Software\OpenCV\Linux\opencv-3.4.12\modules\videoio\src\cap_dshow.cpp:114:0:
D:/Qt/mingw32/i686-w64-mingw32/include/Aviriff.h:2:8: error: expected constructor, destructor, or type conversion before 'file'
 * This file is part of the mingw-w64 runtime package.
        ^
D:/Qt/mingw32/i686-w64-mingw32/include/Aviriff.h:3:25: error: 'refer' does not name a type
 * No warranty is given; refer to the file DISCLAIMER within this package.
                         ^
In file included from D:/Qt/mingw32/i686-w64-mingw32/include/Aviriff.h:19:0,
                 from D:\Software\OpenCV\Linux\opencv-3.4.12\modules\videoio\src\cap_dshow.cpp:114:
D:/Qt/mingw32/i686-w64-mingw32/include/pshpack2.h:7:21: error: expected declaration before end of line
 #pragma pack(push,2)
                     ^
modules\videoio\CMakeFiles\opencv_videoio.dir\build.make:174: recipe for target 'modules/videoio/CMakeFiles/opencv_videoio.dir/src/cap_dshow.cpp.obj' failed
mingw32-make[2]: *** [modules/videoio/CMakeFiles/opencv_videoio.dir/src/cap_dshow.cpp.obj] Error 1
CMakeFiles\Makefile2:2752: recipe for target 'modules/videoio/CMakeFiles/opencv_videoio.dir/all' failed
mingw32-make[1]: *** [modules/videoio/CMakeFiles/opencv_videoio.dir/all] Error 2
Makefile:161: recipe for target 'all' failed
mingw32-make: *** [all] Error 2


解决
打开E:\MinGW-w64\x64-4.8.1-release-posix-seh-rev5\mingw64\x86_64-w64-mingw32\include\aviriff.h

发现第一行的多行注释少了个/符号，加上保存，如下：

/**
* This file is part of the mingw-w64 runtime package.
* No warranty is given; refer to the file DISCLAIMER within this package.
*/
1
2
3
4
然后重新mingw32-make就好


2. 编译到66%时又遇到如下错误：

[ 65%] Building CXX object modules/photo/CMakeFiles/opencv_photo.dir/opencv_photo_main.cpp.obj
[ 65%] Linking CXX shared library ..\..\bin\libopencv_photo3412.dll
[ 65%] Built target opencv_photo
Scanning dependencies of target opencv_test_photo
[ 66%] Building CXX object modules/photo/CMakeFiles/opencv_test_photo.dir/test/ocl/test_denoising.cpp.obj
[ 66%] Building CXX object modules/photo/CMakeFiles/opencv_test_photo.dir/test/test_cloning.cpp.obj
[ 66%] Building CXX object modules/photo/CMakeFiles/opencv_test_photo.dir/test/test_decolor.cpp.obj
[ 66%] Building CXX object modules/photo/CMakeFiles/opencv_test_photo.dir/test/test_denoise_tvl1.cpp.obj
[ 66%] Building CXX object modules/photo/CMakeFiles/opencv_test_photo.dir/test/test_denoising.cpp.obj
[ 66%] Building CXX object modules/photo/CMakeFiles/opencv_test_photo.dir/test/test_denoising.cuda.cpp.obj
[ 66%] Building CXX object modules/photo/CMakeFiles/opencv_test_photo.dir/test/test_hdr.cpp.obj
D:\Software\OpenCV\Linux\opencv-3.4.12\modules\photo\test\test_hdr.cpp: In member function 'virtual void opencv_test::{anonymous}::Photo_AlignMTB_regression_Test::Body()':
D:\Software\OpenCV\Linux\opencv-3.4.12\modules\photo\test\test_hdr.cpp:133:39: error: 'time' was not declared in this scope
     srand(static_cast<unsigned>(time(0)));
                                       ^
modules\photo\CMakeFiles\opencv_test_photo.dir\build.make:146: recipe for target 'modules/photo/CMakeFiles/opencv_test_photo.dir/test/test_hdr.cpp.obj' failed
mingw32-make[2]: *** [modules/photo/CMakeFiles/opencv_test_photo.dir/test/test_hdr.cpp.obj] Error 1
CMakeFiles\Makefile2:2094: recipe for target 'modules/photo/CMakeFiles/opencv_test_photo.dir/all' failed
mingw32-make[1]: *** [modules/photo/CMakeFiles/opencv_test_photo.dir/all] Error 2
Makefile:161: recipe for target 'all' failed
mingw32-make: *** [all] Error 2


在test_hdr.cpp头部引用一下

#include <sys/time.h>
即可

# OpenCV-MinGW
**OpenCV MinGW (mingw-x86_64-posix-seh-gcc) build on windows.**

Release:

General configuration for OpenCV 4.5.5 =====================================
  Version control:               4.5.5

  - Platform:
    	Timestamp:                   2023-02-06T12:13:41Z
		Host:                        Windows 10.0.19044 AMD64
    	CMake:                       3.23.2
    	CMake generator:             MinGW Makefiles
   	 CMake build tool:            C:/Application/mingw-x86_64-posix-seh-gcc/mingw64/bin/mingw32-make.exe
    	Configuration:               Release

  - CPU/HW features:
    	Baseline:                    SSE SSE2 SSE3
        Requested:                 SSE3
   	 Dispatched code generation:  SSE4_1 SSE4_2 FP16 AVX AVX2 AVX512_SKX
      	Requested:                 SSE4_1 SSE4_2 AVX FP16 AVX2 AVX512_SKX
     	SSE4_1 (18 files):         + SSSE3 SSE4_1
      	SSE4_2 (2 files):          + SSSE3 SSE4_1 POPCNT SSE4_2
      	FP16 (1 files):            + SSSE3 SSE4_1 POPCNT SSE4_2 FP16 AVX
      	AVX (5 files):             + SSSE3 SSE4_1 POPCNT SSE4_2 AVX
      	AVX2 (33 files):           + SSSE3 SSE4_1 POPCNT SSE4_2 FP16 FMA3 AVX AVX2
      	AVX512_SKX (8 files):      + SSSE3 SSE4_1 POPCNT SSE4_2 FP16 FMA3 AVX AVX2 AVX_512F AVX512_COMMON AVX512_SKX

  - C/C++:
    	Built as dynamic libs?:      YES
    	C++ standard:                11
    	C++ Compiler:                C:/Application/mingw-x86_64-posix-seh-gcc/mingw64/bin/g++.exe  (ver 12.2.0)
    	C++ flags (Release):         -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Wsuggest-override -Wno-delete-non-virtual-dtor -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -fvisibility-inlines-hidden -O3 -DNDEBUG  -DNDEBUG
    	C++ flags (Debug):           -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Wsuggest-override -Wno-delete-non-virtual-dtor -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -fvisibility-inlines-hidden -g  -O0 -DDEBUG -D_DEBUG
    	C Compiler:                  C:/Application/mingw-x86_64-posix-seh-gcc/mingw64/bin/gcc.exe
   	 C flags (Release):           -fsigned-char -W -Wall -Werror=return-type -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -O3 -DNDEBUG  -DNDEBUG
    	C flags (Debug):             -fsigned-char -W -Wall -Werror=return-type -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -g  -O0 -DDEBUG -D_DEBUG
    	Linker flags (Release):      -Wl,--gc-sections  
    	Linker flags (Debug):        -Wl,--gc-sections  
    	ccache:                      NO
   	 Precompiled headers:         NO
    	Extra dependencies:
    	3rdparty dependencies:

  - OpenCV modules:
    	To be built:                 calib3d core dnn features2d flann gapi highgui imgcodecs imgproc ml objdetect photo stitching ts video videoio
    	Disabled:                    world
   	 Disabled by dependency:      -
    	Unavailable:                 java python2 python3
    	Applications:                tests perf_tests apps
    	Documentation:               NO
    	Non-free algorithms:         NO

  	Windows RT support:            NO

  - GUI:                           WIN32UI
    	Win32 UI:                    YES
    	VTK support:                 NO

  - Media I/O: 
		ZLib:                        build (ver 1.2.11)
		JPEG:                        build-libjpeg-turbo (ver 2.1.2-62)
		WEBP:                        build (ver encoder: 0x020f)
		PNG:                         build (ver 1.6.37)
		TIFF:                        build (ver 42 - 4.2.0)
		JPEG 2000:                   build (ver 2.4.0)
		OpenEXR:                     build (ver 2.3.0)
		HDR:                         YES
		SUNRASTER:                   YES
		PXM:                         YES
		PFM:                         YES

  - Video I/O:
		DC1394:                      NO
		FFMPEG:                      YES (prebuilt binaries)
		  avcodec:                   YES (58.134.100)
		  avformat:                  YES (58.76.100)
		  avutil:                    YES (56.70.100)
		  swscale:                   YES (5.9.100)
		  avresample:                YES (4.0.0)
   	 GStreamer:                   NO
    	DirectShow:                  YES

  - Parallel framework:            none

- Trace:                         YES (built-in)

- Other third-party libraries:
		Lapack:                      NO
		Eigen:                       NO
		Custom HAL:                  NO
		Protobuf:                    build (3.19.1)

- OpenCL:                        YES (no extra features)
		Include path:                C:/Application/opencv-4.5.5/3rdparty/include/opencl/1.2
		Link libraries:              Dynamic load

- Python (for build):            C:/Users/Miniconda3/python.exe

- Java:                          
    	ant:                         NO
    	JNI:                         NO
    	Java wrappers:        NO
   	 Java tests:               NO

- Install to:                    C:/Application/opencv/install

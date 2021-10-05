## Success
- No QT (GTK+ instead of QT)
- No OpenGL
- No NVIDIA
- No Python
- No Contribute Modules

```shell
-- General configuration for OpenCV 3.4.0 =====================================
--   Version control:               unknown
-- 
--   Platform:
--     Timestamp:                   2021-09-26T11:18:17Z
--     Host:                        Linux 5.10.60-v7l+ armv7l
--     CMake:                       3.16.3
--     CMake generator:             Unix Makefiles
--     CMake build tool:            /usr/bin/make
--     Configuration:               RELEASE
-- 
--   CPU/HW features:
--     Baseline:
--       requested:                 DETECT
--       disabled:                  VFPV3 NEON
-- 
--   C/C++:
--     Built as dynamic libs?:      YES
--     C++11:                       YES
--     C++ Compiler:                /usr/bin/c++  (ver 8.3.0)
--     C++ flags (Release):         -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Winit-self -Wno-narrowing -Wno-delete-non-virtual-dtor -Wno-comment -Wno-implicit-fallthrough -fdiagnostics-show-option -pthread -fomit-frame-pointer -ffunction-sections -fdata-sections  -mfp16-format=ieee -fvisibility=hidden -fvisibility-inlines-hidden -O3 -DNDEBUG  -DNDEBUG
--     C++ flags (Debug):           -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Winit-self -Wno-narrowing -Wno-delete-non-virtual-dtor -Wno-comment -Wno-implicit-fallthrough -fdiagnostics-show-option -pthread -fomit-frame-pointer -ffunction-sections -fdata-sections  -mfp16-format=ieee -fvisibility=hidden -fvisibility-inlines-hidden -g  -O0 -DDEBUG -D_DEBUG
--     C Compiler:                  /usr/bin/cc
--     C flags (Release):           -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Winit-self -Wno-narrowing -Wno-comment -Wno-implicit-fallthrough -fdiagnostics-show-option -pthread -fomit-frame-pointer -ffunction-sections -fdata-sections  -mfp16-format=ieee -fvisibility=hidden -O3 -DNDEBUG  -DNDEBUG
--     C flags (Debug):             -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Winit-self -Wno-narrowing -Wno-comment -Wno-implicit-fallthrough -fdiagnostics-show-option -pthread -fomit-frame-pointer -ffunction-sections -fdata-sections  -mfp16-format=ieee -fvisibility=hidden -g  -O0 -DDEBUG -D_DEBUG
--     Linker flags (Release):
--     Linker flags (Debug):
--     ccache:                      NO
--     Precompiled headers:         YES
--     Extra dependencies:          dl m pthread rt
--     3rdparty dependencies:
-- 
--   OpenCV modules:
--     To be built:                 calib3d core dnn features2d flann highgui imgcodecs imgproc ml objdetect photo python_bindings_generator shape stitching superres ts video videoio videostab
--     Disabled:                    js python2 python3 world
--     Disabled by dependency:      -
--     Unavailable:                 cudaarithm cudabgsegm cudacodec cudafeatures2d cudafilters cudaimgproc cudalegacy cudaobjdetect cudaoptflow cudastereo cudawarping cudev java viz
--     Applications:                tests perf_tests apps
--     Documentation:               YES (/usr/bin/doxygen 1.8.13)
--     Non-free algorithms:         NO
-- 
--   GUI: 
--     GTK+:                        YES (ver 2.24.32)
--       GThread :                  YES (ver 2.58.3)
--       GtkGlExt:                  NO
--     VTK support:                 NO
-- 
--   Media I/O: 
--     ZLib:                        /usr/lib/arm-linux-gnueabihf/libz.so (ver 1.2.11)
--     JPEG:                        /usr/lib/arm-linux-gnueabihf/libjpeg.so (ver )
--     WEBP:                        build (ver encoder: 0x020e)
--     PNG:                         /usr/lib/arm-linux-gnueabihf/libpng.so (ver 1.6.36)
--     TIFF:                        /usr/lib/arm-linux-gnueabihf/libtiff.so (ver 42 / 4.1.0)
--     JPEG 2000:                   /usr/lib/arm-linux-gnueabihf/libjasper.so (ver 1.900.1)
--     OpenEXR:                     build (ver 1.7.1)
-- 
--   Video I/O:
--     DC1394:                      NO
--     FFMPEG:                      YES
--       avcodec:                   YES (ver 58.35.100)
--       avformat:                  YES (ver 58.20.100)
--       avutil:                    YES (ver 56.22.100)
--       swscale:                   YES (ver 5.3.100)
--       avresample:                NO
--     GStreamer:                   
--       base:                      YES (ver 1.14.4)
--       video:                     YES (ver 1.14.4)
--       app:                       YES (ver 1.14.4)
--       riff:                      YES (ver 1.14.4)
--       pbutils:                   YES (ver 1.14.4)
--     libv4l/libv4l2:              1.16.3 / 1.16.3
--     v4l/v4l2:                    linux/videodev2.h
--     gPhoto2:                     NO
-- 
--   Parallel framework:            pthreads
-- 
--   Trace:                         YES (built-in)
-- 
--   Other third-party libraries:
--     Lapack:                      NO
--     Eigen:                       NO
--     Custom HAL:                  YES (carotene (ver 0.0.1))
-- 
--   NVIDIA CUDA:                   NO
-- 
--   OpenCL:                        YES (no extra features)
--     Include path:                /home/pi/Downloads/tmp2/opencv-3.4.0/3rdparty/include/opencl/1.2
--     Link libraries:              Dynamic load
-- 
--   Python (for build):            /usr/bin/python2.7
-- 
--   Java:
--     ant:                         NO
--     JNI:                         NO
--     Java wrappers:               NO
--     Java tests:                  NO
-- 
--   Matlab:                        NO
-- 
--   Install to:                    /home/pi/local/opencv-3.4.0
-- -----------------------------------------------------------------
-- 
-- Configuring done
-- Generating done
-- Build files have been written to: /home/pi/Downloads/tmp2/opencv-3.4.0/build
pi@raspberrypi:~/Downloads/tmp2/opencv-3.4.0/build $ make -j4
[  0%] Generate opencv.pc
[  4%] Built target carotene_objs
[ 13%] Built target libwebp
[ 19%] Built target IlmImf
[ 19%] Built target gen-pkgconfig
[ 19%] Built target opencv_ts_pch_dephelp
[ 19%] Built target opencv_core_pch_dephelp
[ 24%] Built target libprotobuf
[ 25%] Built target opencv_imgcodecs_pch_dephelp
[ 25%] Built target opencv_imgproc_pch_dephelp
[ 25%] Built target opencv_videoio_pch_dephelp
[ 25%] Built target opencv_test_core_pch_dephelp
[ 25%] Built target opencv_highgui_pch_dephelp
[ 25%] Built target opencv_perf_core_pch_dephelp
[ 26%] Built target opencv_test_flann_pch_dephelp
[ 26%] Built target opencv_flann_pch_dephelp
[ 27%] Built target opencv_test_imgproc_pch_dephelp
[ 27%] Built target opencv_perf_imgproc_pch_dephelp
[ 27%] Built target opencv_ml_pch_dephelp
[ 29%] Built target opencv_test_objdetect_pch_dephelp
[ 29%] Built target opencv_test_ml_pch_dephelp
[ 30%] Built target opencv_objdetect_pch_dephelp
[ 30%] Built target opencv_perf_objdetect_pch_dephelp
[ 30%] Built target opencv_photo_pch_dephelp
[ 30%] Built target opencv_test_photo_pch_dephelp
[ 30%] Built target opencv_perf_photo_pch_dephelp
[ 30%] Built target opencv_test_video_pch_dephelp
[ 30%] Built target opencv_video_pch_dephelp
[ 30%] Built target opencv_perf_video_pch_dephelp
[ 30%] Built target opencv_perf_dnn_pch_dephelp
[ 30%] Built target opencv_test_dnn_pch_dephelp
[ 30%] Built target opencv_dnn_pch_dephelp
[ 30%] Built target opencv_test_imgcodecs_pch_dephelp
[ 30%] Built target opencv_shape_pch_dephelp
[ 30%] Built target opencv_test_shape_pch_dephelp
[ 30%] Built target opencv_perf_imgcodecs_pch_dephelp
[ 30%] Built target opencv_test_videoio_pch_dephelp
[ 30%] Built target opencv_perf_videoio_pch_dephelp
[ 30%] Built target opencv_test_highgui_pch_dephelp
[ 30%] Built target opencv_test_superres_pch_dephelp
[ 30%] Built target opencv_superres_pch_dephelp
[ 30%] Built target opencv_perf_superres_pch_dephelp
[ 30%] Built target opencv_perf_features2d_pch_dephelp
[ 30%] Built target opencv_features2d_pch_dephelp
[ 30%] Built target opencv_test_calib3d_pch_dephelp
[ 30%] Built target opencv_test_features2d_pch_dephelp
[ 30%] Built target opencv_calib3d_pch_dephelp
[ 30%] Built target opencv_perf_calib3d_pch_dephelp
[ 30%] Built target opencv_stitching_pch_dephelp
[ 30%] Built target opencv_test_stitching_pch_dephelp
[ 30%] Built target opencv_perf_stitching_pch_dephelp
[ 30%] Built target opencv_videostab_pch_dephelp
[ 31%] Built target tegra_hal
[ 31%] Built target opencv_test_videostab_pch_dephelp
[ 31%] Built target pch_Generate_opencv_core
[ 31%] Built target pch_Generate_opencv_ts
[ 32%] Built target pch_Generate_opencv_imgproc
[ 32%] Built target pch_Generate_opencv_imgcodecs
[ 32%] Built target pch_Generate_opencv_videoio
[ 32%] Built target pch_Generate_opencv_highgui
[ 32%] Built target pch_Generate_opencv_perf_core
[ 33%] Built target pch_Generate_opencv_test_core
[ 33%] Built target pch_Generate_opencv_flann
[ 33%] Built target pch_Generate_opencv_test_flann
[ 33%] Built target pch_Generate_opencv_perf_imgproc
[ 33%] Built target pch_Generate_opencv_test_imgproc
[ 34%] Built target pch_Generate_opencv_test_ml
[ 34%] Built target pch_Generate_opencv_ml
[ 34%] Built target pch_Generate_opencv_objdetect
[ 34%] Built target pch_Generate_opencv_test_objdetect
[ 34%] Built target pch_Generate_opencv_perf_objdetect
[ 34%] Built target pch_Generate_opencv_photo
[ 34%] Built target pch_Generate_opencv_test_photo
[ 35%] Built target pch_Generate_opencv_test_video
[ 35%] Built target pch_Generate_opencv_video
[ 36%] Built target pch_Generate_opencv_perf_video
[ 36%] Built target pch_Generate_opencv_perf_photo
[ 36%] Built target pch_Generate_opencv_dnn
[ 36%] Built target pch_Generate_opencv_test_dnn
[ 36%] Built target pch_Generate_opencv_test_imgcodecs
[ 36%] Built target pch_Generate_opencv_perf_dnn
[ 37%] Built target pch_Generate_opencv_perf_imgcodecs
[ 37%] Built target pch_Generate_opencv_test_shape
[ 37%] Built target pch_Generate_opencv_perf_videoio
[ 37%] Built target pch_Generate_opencv_shape
[ 37%] Built target pch_Generate_opencv_test_videoio
[ 37%] Built target pch_Generate_opencv_test_highgui
[ 37%] Built target pch_Generate_opencv_superres
[ 37%] Built target pch_Generate_opencv_test_superres
[ 37%] Built target pch_Generate_opencv_perf_superres
[ 37%] Built target pch_Generate_opencv_perf_features2d
[ 37%] Built target pch_Generate_opencv_features2d
[ 38%] Built target pch_Generate_opencv_test_features2d
[ 38%] Built target pch_Generate_opencv_calib3d
[ 38%] Built target pch_Generate_opencv_test_calib3d
[ 38%] Built target pch_Generate_opencv_stitching
[ 38%] Built target pch_Generate_opencv_perf_stitching
[ 38%] Built target pch_Generate_opencv_perf_calib3d
[ 38%] Built target pch_Generate_opencv_test_videostab
[ 38%] Built target pch_Generate_opencv_test_stitching
[ 38%] Built target pch_Generate_opencv_videostab
Scanning dependencies of target opencv_core
[ 38%] Building CXX object modules/core/CMakeFiles/opencv_core.dir/src/system.cpp.o
[ 38%] Linking CXX shared library ../../lib/libopencv_core.so
[ 44%] Built target opencv_core
[ 44%] Linking CXX shared library ../../lib/libopencv_flann.so
[ 44%] Linking CXX shared library ../../lib/libopencv_ml.so
[ 44%] Linking CXX shared library ../../lib/libopencv_imgproc.so
[ 44%] Built target opencv_flann
[ 46%] Built target opencv_ml
[ 50%] Built target opencv_imgproc
[ 50%] Linking CXX shared library ../../lib/libopencv_objdetect.so
[ 50%] Linking CXX shared library ../../lib/libopencv_photo.so
[ 50%] Linking CXX shared library ../../lib/libopencv_imgcodecs.so
[ 50%] Linking CXX shared library ../../lib/libopencv_video.so
[ 50%] Built target opencv_objdetect
[ 51%] Built target opencv_video
[ 51%] Linking CXX shared library ../../lib/libopencv_dnn.so
[ 52%] Linking CXX shared library ../../lib/libopencv_shape.so
[ 53%] Built target opencv_photo
[ 54%] Built target opencv_imgcodecs
[ 54%] Linking CXX shared library ../../lib/libopencv_videoio.so
[ 54%] Built target opencv_shape
[ 55%] Built target opencv_videoio
[ 55%] Linking CXX shared library ../../lib/libopencv_superres.so
[ 55%] Linking CXX shared library ../../lib/libopencv_highgui.so
[ 56%] Built target opencv_superres
[ 58%] Built target opencv_highgui
Scanning dependencies of target opencv_ts
[ 58%] Linking CXX executable ../../bin/opencv_annotation
[ 58%] Linking CXX shared library ../../lib/libopencv_features2d.so
[ 58%] Building CXX object modules/ts/CMakeFiles/opencv_ts.dir/src/ts.cpp.o
[ 60%] Built target opencv_features2d
[ 65%] Built target opencv_dnn
[ 65%] Linking CXX executable ../../bin/opencv_visualisation
[ 65%] Linking CXX executable ../../bin/opencv_version
[ 65%] Built target opencv_annotation
[ 65%] Linking CXX shared library ../../lib/libopencv_calib3d.so
[ 67%] Built target opencv_calib3d
[ 67%] Built target opencv_visualisation
[ 67%] Linking CXX shared library ../../lib/libopencv_videostab.so
[ 67%] Linking CXX shared library ../../lib/libopencv_stitching.so
[ 67%] Built target opencv_version
[ 67%] Linking CXX executable ../../bin/opencv_traincascade
[ 68%] Built target opencv_videostab
[ 68%] Linking CXX executable ../../bin/opencv_createsamples
[ 69%] Built target opencv_stitching
[ 69%] Linking CXX executable ../../bin/opencv_interactive-calibration
[ 70%] Built target opencv_traincascade
[ 70%] Built target opencv_createsamples
[ 70%] Built target opencv_interactive-calibration
[ 70%] Linking CXX static library ../../lib/libopencv_ts.a
[ 72%] Built target opencv_ts
[ 72%] Linking CXX executable ../../bin/opencv_test_flann
[ 72%] Linking CXX executable ../../bin/opencv_perf_core
[ 73%] Linking CXX executable ../../bin/opencv_test_core
[ 73%] Linking CXX executable ../../bin/opencv_test_imgproc
[ 73%] Built target opencv_test_flann
[ 73%] Linking CXX executable ../../bin/opencv_perf_imgproc
[ 76%] Built target opencv_perf_core
[ 76%] Linking CXX executable ../../bin/opencv_test_ml
[ 78%] Built target opencv_test_core
[ 78%] Linking CXX executable ../../bin/opencv_test_objdetect
[ 81%] Built target opencv_test_imgproc
[ 81%] Linking CXX executable ../../bin/opencv_perf_objdetect
[ 81%] Built target opencv_test_ml
[ 81%] Linking CXX executable ../../bin/opencv_test_photo
[ 84%] Built target opencv_perf_imgproc
[ 84%] Linking CXX executable ../../bin/opencv_perf_photo
[ 84%] Built target opencv_test_objdetect
[ 84%] Linking CXX executable ../../bin/opencv_test_video
[ 86%] Built target opencv_perf_objdetect
[ 86%] Linking CXX executable ../../bin/opencv_perf_video
[ 87%] Built target opencv_test_photo
[ 87%] Linking CXX executable ../../bin/opencv_test_dnn
[ 87%] Built target opencv_perf_photo
[ 88%] Built target opencv_test_video
[ 88%] Linking CXX executable ../../bin/opencv_perf_dnn
[ 88%] Linking CXX executable ../../bin/opencv_test_imgcodecs
[ 89%] Built target opencv_perf_video
[ 89%] Linking CXX executable ../../bin/opencv_perf_imgcodecs
[ 90%] Built target opencv_test_dnn
[ 90%] Linking CXX executable ../../bin/opencv_test_shape
[ 91%] Built target opencv_test_imgcodecs
[ 91%] Built target opencv_perf_dnn
[ 91%] Linking CXX executable ../../bin/opencv_test_videoio
[ 92%] Linking CXX executable ../../bin/opencv_perf_videoio
[ 92%] Built target opencv_perf_imgcodecs
[ 92%] Linking CXX executable ../../bin/opencv_test_highgui
[ 92%] Built target opencv_test_shape
[ 92%] Linking CXX executable ../../bin/opencv_test_superres
[ 92%] Built target opencv_perf_videoio
[ 93%] Built target opencv_test_videoio
[ 93%] Linking CXX executable ../../bin/opencv_perf_features2d
[ 93%] Linking CXX executable ../../bin/opencv_perf_superres
[ 93%] Built target opencv_test_highgui
[ 93%] Linking CXX executable ../../bin/opencv_test_features2d
[ 93%] Built target opencv_test_superres
[ 93%] Linking CXX executable ../../bin/opencv_test_calib3d
[ 93%] Built target opencv_perf_superres
[ 94%] Built target opencv_perf_features2d
[ 94%] Linking CXX executable ../../bin/opencv_perf_calib3d
[ 94%] Linking CXX executable ../../bin/opencv_perf_stitching
[ 95%] Built target opencv_test_features2d
[ 95%] Linking CXX executable ../../bin/opencv_test_stitching
[ 95%] Built target opencv_perf_calib3d
[ 95%] Linking CXX executable ../../bin/opencv_test_videostab
[ 97%] Built target opencv_test_calib3d
[ 98%] Built target opencv_perf_stitching
[100%] Built target opencv_test_stitching
[100%] Built target opencv_test_videostab
pi@raspberrypi:~/Downloads/tmp2/opencv-3.4.0/build $ make install
[  0%] Built target gen-pkgconfig
[  9%] Built target libwebp
[ 15%] Built target IlmImf
[ 19%] Built target carotene_objs
[ 20%] Built target tegra_hal
[ 25%] Built target libprotobuf
[ 25%] Built target opencv_ts_pch_dephelp
[ 25%] Built target pch_Generate_opencv_ts
[ 25%] Built target opencv_core_pch_dephelp
[ 25%] Built target pch_Generate_opencv_core
[ 31%] Built target opencv_core
[ 31%] Built target opencv_imgproc_pch_dephelp
[ 32%] Built target pch_Generate_opencv_imgproc
[ 36%] Built target opencv_imgproc
[ 37%] Built target opencv_imgcodecs_pch_dephelp
[ 37%] Built target pch_Generate_opencv_imgcodecs
[ 38%] Built target opencv_imgcodecs
[ 38%] Built target opencv_videoio_pch_dephelp
[ 38%] Built target pch_Generate_opencv_videoio
[ 39%] Built target opencv_videoio
[ 39%] Built target opencv_highgui_pch_dephelp
[ 39%] Built target pch_Generate_opencv_highgui
[ 40%] Built target opencv_highgui
[ 41%] Built target opencv_ts
[ 41%] Built target opencv_test_core_pch_dephelp
[ 43%] Built target pch_Generate_opencv_test_core
[ 46%] Built target opencv_test_core
[ 46%] Built target opencv_perf_core_pch_dephelp
[ 46%] Built target pch_Generate_opencv_perf_core
[ 49%] Built target opencv_perf_core
[ 49%] Built target opencv_flann_pch_dephelp
[ 49%] Built target pch_Generate_opencv_flann
[ 49%] Built target opencv_flann
[ 50%] Built target opencv_test_flann_pch_dephelp
[ 50%] Built target pch_Generate_opencv_test_flann
[ 50%] Built target opencv_test_flann
[ 51%] Built target opencv_test_imgproc_pch_dephelp
[ 51%] Built target pch_Generate_opencv_test_imgproc
[ 54%] Built target opencv_test_imgproc
[ 54%] Built target opencv_perf_imgproc_pch_dephelp
[ 54%] Built target pch_Generate_opencv_perf_imgproc
[ 58%] Built target opencv_perf_imgproc
[ 58%] Built target opencv_ml_pch_dephelp
[ 58%] Built target pch_Generate_opencv_ml
[ 60%] Built target opencv_ml
[ 61%] Built target opencv_test_ml_pch_dephelp
[ 62%] Built target pch_Generate_opencv_test_ml
[ 62%] Built target opencv_test_ml
[ 62%] Built target opencv_test_objdetect_pch_dephelp
[ 63%] Built target opencv_objdetect_pch_dephelp
[ 63%] Built target pch_Generate_opencv_test_objdetect
[ 63%] Built target pch_Generate_opencv_objdetect
[ 63%] Built target opencv_objdetect
[ 63%] Built target opencv_test_objdetect
[ 63%] Built target opencv_perf_objdetect_pch_dephelp
[ 63%] Built target pch_Generate_opencv_perf_objdetect
[ 64%] Built target opencv_perf_objdetect
[ 64%] Built target opencv_test_photo_pch_dephelp
[ 64%] Built target opencv_photo_pch_dephelp
[ 64%] Built target pch_Generate_opencv_photo
[ 65%] Built target opencv_photo
[ 65%] Built target pch_Generate_opencv_test_photo
[ 66%] Built target opencv_test_photo
[ 66%] Built target opencv_perf_photo_pch_dephelp
[ 66%] Built target pch_Generate_opencv_perf_photo
[ 66%] Built target opencv_perf_photo
[ 66%] Built target opencv_test_video_pch_dephelp
[ 67%] Built target pch_Generate_opencv_test_video
[ 67%] Built target opencv_video_pch_dephelp
[ 67%] Built target pch_Generate_opencv_video
[ 68%] Built target opencv_video
[ 69%] Built target opencv_test_video
[ 69%] Built target opencv_perf_video_pch_dephelp
[ 70%] Built target pch_Generate_opencv_perf_video
[ 72%] Built target opencv_perf_video
[ 72%] Built target opencv_test_dnn_pch_dephelp
[ 72%] Built target opencv_dnn_pch_dephelp
[ 72%] Built target pch_Generate_opencv_dnn
[ 77%] Built target opencv_dnn
[ 77%] Built target pch_Generate_opencv_test_dnn
[ 78%] Built target opencv_test_dnn
[ 78%] Built target opencv_perf_dnn_pch_dephelp
[ 78%] Built target pch_Generate_opencv_perf_dnn
[ 78%] Built target opencv_perf_dnn
[ 78%] Built target opencv_test_imgcodecs_pch_dephelp
[ 78%] Built target pch_Generate_opencv_test_imgcodecs
[ 79%] Built target opencv_test_imgcodecs
[ 79%] Built target opencv_perf_imgcodecs_pch_dephelp
[ 80%] Built target pch_Generate_opencv_perf_imgcodecs
[ 80%] Built target opencv_perf_imgcodecs
[ 80%] Built target opencv_shape_pch_dephelp
[ 80%] Built target opencv_test_shape_pch_dephelp
[ 80%] Built target pch_Generate_opencv_shape
[ 81%] Built target opencv_shape
[ 81%] Built target pch_Generate_opencv_test_shape
[ 81%] Built target opencv_test_shape
[ 81%] Built target opencv_test_videoio_pch_dephelp
[ 81%] Built target opencv_perf_videoio_pch_dephelp
[ 81%] Built target pch_Generate_opencv_perf_videoio
[ 82%] Built target opencv_perf_videoio
[ 82%] Built target pch_Generate_opencv_test_videoio
[ 83%] Built target opencv_test_videoio
[ 83%] Built target opencv_test_highgui_pch_dephelp
[ 83%] Built target pch_Generate_opencv_test_highgui
[ 83%] Built target opencv_test_highgui
[ 83%] Built target opencv_test_superres_pch_dephelp
[ 83%] Built target opencv_superres_pch_dephelp
[ 83%] Built target pch_Generate_opencv_test_superres
[ 83%] Built target pch_Generate_opencv_superres
[ 84%] Built target opencv_superres
[ 84%] Built target opencv_test_superres
[ 84%] Built target opencv_perf_superres_pch_dephelp
[ 84%] Built target pch_Generate_opencv_perf_superres
[ 84%] Built target opencv_perf_superres
[ 84%] Built target opencv_features2d_pch_dephelp
[ 84%] Built target pch_Generate_opencv_features2d
[ 87%] Built target opencv_features2d
[ 87%] Built target opencv_perf_features2d_pch_dephelp
[ 87%] Built target pch_Generate_opencv_perf_features2d
[ 88%] Built target opencv_perf_features2d
[ 88%] Built target opencv_test_features2d_pch_dephelp
[ 88%] Built target pch_Generate_opencv_test_features2d
[ 89%] Built target opencv_test_features2d
[ 89%] Built target opencv_test_calib3d_pch_dephelp
[ 89%] Built target opencv_calib3d_pch_dephelp
[ 90%] Built target pch_Generate_opencv_calib3d
[ 92%] Built target opencv_calib3d
[ 92%] Built target pch_Generate_opencv_test_calib3d
[ 94%] Built target opencv_test_calib3d
[ 94%] Built target opencv_perf_calib3d_pch_dephelp
[ 94%] Built target pch_Generate_opencv_perf_calib3d
[ 94%] Built target opencv_perf_calib3d
[ 94%] Built target opencv_test_stitching_pch_dephelp
[ 94%] Built target opencv_stitching_pch_dephelp
[ 94%] Built target pch_Generate_opencv_stitching
[ 95%] Built target opencv_stitching
[ 95%] Built target opencv_perf_stitching_pch_dephelp
[ 95%] Built target pch_Generate_opencv_perf_stitching
[ 96%] Built target opencv_perf_stitching
[ 96%] Built target pch_Generate_opencv_test_stitching
[ 97%] Built target opencv_test_stitching
[ 97%] Built target opencv_videostab_pch_dephelp
[ 97%] Built target pch_Generate_opencv_videostab
[ 98%] Built target opencv_videostab
[ 98%] Built target opencv_test_videostab_pch_dephelp
[ 98%] Built target pch_Generate_opencv_test_videostab
[ 98%] Built target opencv_test_videostab
[100%] Built target opencv_traincascade
[100%] Built target opencv_createsamples
[100%] Built target opencv_annotation
[100%] Built target opencv_visualisation
[100%] Built target opencv_interactive-calibration
[100%] Built target opencv_version
Install the project...
-- Install configuration: "RELEASE"
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/cvconfig.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/opencv_modules.hpp
-- Installing: /home/pi/local/opencv-3.4.0/lib/pkgconfig/opencv.pc
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/OpenCVModules.cmake
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/OpenCVModules-release.cmake
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/OpenCVConfig-version.cmake
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/OpenCVConfig.cmake
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/valgrind.supp
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/valgrind_3rdparty.supp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv/cv.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv/cv.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv/cvaux.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv/cvaux.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv/cvwimage.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv/cxcore.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv/cxcore.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv/cxeigen.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv/cxmisc.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv/highgui.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv/ml.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/opencv.hpp
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_core.so.3.4.0
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_core.so.3.4
-- Set runtime path of "/home/pi/local/opencv-3.4.0/lib/libopencv_core.so.3.4.0" to "/home/pi/local/opencv-3.4.0/lib"
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_core.so
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/block.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/border_interpolate.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/color.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/common.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/datamov_utils.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/dynamic_smem.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/emulation.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/filters.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/funcattrib.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/functional.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/limits.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/reduce.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/saturate_cast.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/scan.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/simd_functions.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/transform.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/type_traits.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/utility.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/vec_distance.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/vec_math.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/vec_traits.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/warp.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/warp_reduce.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/warp_shuffle.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/detail/color_detail.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/detail/reduce.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/detail/reduce_key_val.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/detail/transform_detail.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/detail/type_traits_detail.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda/detail/vec_distance_detail.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/affine.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/base.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/bufferpool.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/core.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/core_c.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda.inl.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda_stream_accessor.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cuda_types.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cv_cpu_dispatch.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cv_cpu_helper.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cvdef.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cvstd.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/cvstd.inl.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/directx.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/eigen.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/fast_math.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/hal/hal.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/hal/interface.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/hal/intrin.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/hal/intrin_cpp.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/hal/intrin_neon.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/hal/intrin_sse.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/hal/intrin_vsx.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/ippasync.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/mat.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/mat.inl.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/matx.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/neon_utils.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/ocl.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/ocl_genbase.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/opengl.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/operations.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/optim.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/ovx.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/persistence.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/ptr.inl.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/saturate.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/softfloat.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/sse_utils.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/traits.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/types.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/types_c.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/utility.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/utils/filesystem.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/utils/logger.defines.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/utils/logger.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/utils/trace.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/va_intel.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/version.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/vsx_utils.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/core/wimage.hpp
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_flann.so.3.4.0
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_flann.so.3.4
-- Set runtime path of "/home/pi/local/opencv-3.4.0/lib/libopencv_flann.so.3.4.0" to "/home/pi/local/opencv-3.4.0/lib"
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_flann.so
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/all_indices.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/allocator.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/any.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/autotuned_index.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/composite_index.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/config.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/defines.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/dist.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/dummy.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/dynamic_bitset.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/flann.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/flann_base.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/general.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/ground_truth.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/hdf5.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/heap.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/hierarchical_clustering_index.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/index_testing.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/kdtree_index.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/kdtree_single_index.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/kmeans_index.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/linear_index.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/logger.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/lsh_index.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/lsh_table.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/matrix.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/miniflann.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/nn_index.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/object_factory.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/params.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/random.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/result_set.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/sampling.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/saving.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/simplex_downhill.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/flann/timer.h
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_imgproc.so.3.4.0
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_imgproc.so.3.4
-- Set runtime path of "/home/pi/local/opencv-3.4.0/lib/libopencv_imgproc.so.3.4.0" to "/home/pi/local/opencv-3.4.0/lib"
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_imgproc.so
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/imgproc.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/imgproc/hal/hal.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/imgproc/hal/interface.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/imgproc/imgproc.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/imgproc/imgproc_c.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/imgproc/types_c.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/imgproc/detail/distortion_model.hpp
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_ml.so.3.4.0
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_ml.so.3.4
-- Set runtime path of "/home/pi/local/opencv-3.4.0/lib/libopencv_ml.so.3.4.0" to "/home/pi/local/opencv-3.4.0/lib"
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_ml.so
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/ml.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/ml/ml.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/ml/ml.inl.hpp
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_objdetect.so.3.4.0
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_objdetect.so.3.4
-- Set runtime path of "/home/pi/local/opencv-3.4.0/lib/libopencv_objdetect.so.3.4.0" to "/home/pi/local/opencv-3.4.0/lib"
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_objdetect.so
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/objdetect.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/objdetect/detection_based_tracker.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/objdetect/objdetect.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/objdetect/objdetect_c.h
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_photo.so.3.4.0
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_photo.so.3.4
-- Set runtime path of "/home/pi/local/opencv-3.4.0/lib/libopencv_photo.so.3.4.0" to "/home/pi/local/opencv-3.4.0/lib"
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_photo.so
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/photo.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/photo/cuda.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/photo/photo.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/photo/photo_c.h
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_video.so.3.4.0
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_video.so.3.4
-- Set runtime path of "/home/pi/local/opencv-3.4.0/lib/libopencv_video.so.3.4.0" to "/home/pi/local/opencv-3.4.0/lib"
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_video.so
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/video.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/video/background_segm.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/video/tracking.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/video/tracking_c.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/video/video.hpp
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_dnn.so.3.4.0
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_dnn.so.3.4
-- Set runtime path of "/home/pi/local/opencv-3.4.0/lib/libopencv_dnn.so.3.4.0" to "/home/pi/local/opencv-3.4.0/lib"
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_dnn.so
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/dnn.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/dnn/all_layers.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/dnn/dict.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/dnn/dnn.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/dnn/dnn.inl.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/dnn/layer.details.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/dnn/layer.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/dnn/shape_utils.hpp
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_imgcodecs.so.3.4.0
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_imgcodecs.so.3.4
-- Set runtime path of "/home/pi/local/opencv-3.4.0/lib/libopencv_imgcodecs.so.3.4.0" to "/home/pi/local/opencv-3.4.0/lib"
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_imgcodecs.so
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/imgcodecs.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/imgcodecs/imgcodecs.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/imgcodecs/imgcodecs_c.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/imgcodecs/ios.h
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_shape.so.3.4.0
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_shape.so.3.4
-- Set runtime path of "/home/pi/local/opencv-3.4.0/lib/libopencv_shape.so.3.4.0" to "/home/pi/local/opencv-3.4.0/lib"
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_shape.so
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/shape.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/shape/emdL1.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/shape/hist_cost.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/shape/shape.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/shape/shape_distance.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/shape/shape_transformer.hpp
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_videoio.so.3.4.0
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_videoio.so.3.4
-- Set runtime path of "/home/pi/local/opencv-3.4.0/lib/libopencv_videoio.so.3.4.0" to "/home/pi/local/opencv-3.4.0/lib"
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_videoio.so
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/videoio.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/videoio/cap_ios.h
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/videoio/videoio.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/videoio/videoio_c.h
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_highgui.so.3.4.0
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_highgui.so.3.4
-- Set runtime path of "/home/pi/local/opencv-3.4.0/lib/libopencv_highgui.so.3.4.0" to "/home/pi/local/opencv-3.4.0/lib"
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_highgui.so
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/highgui.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/highgui/highgui.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/highgui/highgui_c.h
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_superres.so.3.4.0
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_superres.so.3.4
-- Set runtime path of "/home/pi/local/opencv-3.4.0/lib/libopencv_superres.so.3.4.0" to "/home/pi/local/opencv-3.4.0/lib"
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_superres.so
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/superres.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/superres/optical_flow.hpp
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_features2d.so.3.4.0
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_features2d.so.3.4
-- Set runtime path of "/home/pi/local/opencv-3.4.0/lib/libopencv_features2d.so.3.4.0" to "/home/pi/local/opencv-3.4.0/lib"
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_features2d.so
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/features2d.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/features2d/features2d.hpp
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_calib3d.so.3.4.0
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_calib3d.so.3.4
-- Set runtime path of "/home/pi/local/opencv-3.4.0/lib/libopencv_calib3d.so.3.4.0" to "/home/pi/local/opencv-3.4.0/lib"
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_calib3d.so
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/calib3d.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/calib3d/calib3d.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/calib3d/calib3d_c.h
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_stitching.so.3.4.0
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_stitching.so.3.4
-- Set runtime path of "/home/pi/local/opencv-3.4.0/lib/libopencv_stitching.so.3.4.0" to "/home/pi/local/opencv-3.4.0/lib"
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_stitching.so
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/stitching.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/stitching/warpers.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/stitching/detail/autocalib.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/stitching/detail/blenders.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/stitching/detail/camera.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/stitching/detail/exposure_compensate.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/stitching/detail/matchers.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/stitching/detail/motion_estimators.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/stitching/detail/seam_finders.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/stitching/detail/timelapsers.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/stitching/detail/util.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/stitching/detail/util_inl.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/stitching/detail/warpers.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/stitching/detail/warpers_inl.hpp
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_videostab.so.3.4.0
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_videostab.so.3.4
-- Set runtime path of "/home/pi/local/opencv-3.4.0/lib/libopencv_videostab.so.3.4.0" to "/home/pi/local/opencv-3.4.0/lib"
-- Installing: /home/pi/local/opencv-3.4.0/lib/libopencv_videostab.so
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/videostab.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/videostab/deblurring.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/videostab/fast_marching.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/videostab/fast_marching_inl.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/videostab/frame_source.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/videostab/global_motion.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/videostab/inpainting.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/videostab/log.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/videostab/motion_core.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/videostab/motion_stabilizing.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/videostab/optical_flow.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/videostab/outlier_rejection.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/videostab/ring_buffer.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/videostab/stabilizer.hpp
-- Installing: /home/pi/local/opencv-3.4.0/include/opencv2/videostab/wobble_suppression.hpp
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/doc/html
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/haarcascades/haarcascade_eye.xml
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/haarcascades/haarcascade_eye_tree_eyeglasses.xml
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/haarcascades/haarcascade_frontalcatface.xml
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/haarcascades/haarcascade_frontalcatface_extended.xml
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/haarcascades/haarcascade_frontalface_alt.xml
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/haarcascades/haarcascade_frontalface_alt2.xml
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/haarcascades/haarcascade_frontalface_alt_tree.xml
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/haarcascades/haarcascade_frontalface_default.xml
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/haarcascades/haarcascade_fullbody.xml
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/haarcascades/haarcascade_lefteye_2splits.xml
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/haarcascades/haarcascade_licence_plate_rus_16stages.xml
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/haarcascades/haarcascade_lowerbody.xml
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/haarcascades/haarcascade_profileface.xml
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/haarcascades/haarcascade_righteye_2splits.xml
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/haarcascades/haarcascade_russian_plate_number.xml
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/haarcascades/haarcascade_smile.xml
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/haarcascades/haarcascade_upperbody.xml
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/lbpcascades/lbpcascade_frontalcatface.xml
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/lbpcascades/lbpcascade_frontalface.xml
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/lbpcascades/lbpcascade_frontalface_improved.xml
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/lbpcascades/lbpcascade_profileface.xml
-- Installing: /home/pi/local/opencv-3.4.0/share/OpenCV/lbpcascades/lbpcascade_silverware.xml
-- Installing: /home/pi/local/opencv-3.4.0/bin/opencv_traincascade
-- Set runtime path of "/home/pi/local/opencv-3.4.0/bin/opencv_traincascade" to "/home/pi/local/opencv-3.4.0/lib"
-- Installing: /home/pi/local/opencv-3.4.0/bin/opencv_createsamples
-- Set runtime path of "/home/pi/local/opencv-3.4.0/bin/opencv_createsamples" to "/home/pi/local/opencv-3.4.0/lib"
-- Installing: /home/pi/local/opencv-3.4.0/bin/opencv_annotation
-- Set runtime path of "/home/pi/local/opencv-3.4.0/bin/opencv_annotation" to "/home/pi/local/opencv-3.4.0/lib"
-- Installing: /home/pi/local/opencv-3.4.0/bin/opencv_visualisation
-- Set runtime path of "/home/pi/local/opencv-3.4.0/bin/opencv_visualisation" to "/home/pi/local/opencv-3.4.0/lib"
-- Installing: /home/pi/local/opencv-3.4.0/bin/opencv_interactive-calibration
-- Set runtime path of "/home/pi/local/opencv-3.4.0/bin/opencv_interactive-calibration" to "/home/pi/local/opencv-3.4.0/lib"
-- Installing: /home/pi/local/opencv-3.4.0/bin/opencv_version
-- Set runtime path of "/home/pi/local/opencv-3.4.0/bin/opencv_version" to "/home/pi/local/opencv-3.4.0/lib"
pi@raspberrypi:~/Downloads/tmp2/opencv-3.4.0/build $ 
```





## Error

using QT instead of GTK+ as the GUI.

```shell
pi@raspberrypi:~/Downloads/tmp2/opencv-3.4.0/build $ cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/home/pi/local -D OPENCV_EXTRA_MODULES_PATH=/home/pi/Downloads/tmp2/opencv_contrib-3.4.0/modules -D BUILD_opencv_python2=OFF -D BUILD_opencv_python3=OFF -D WITH_LIBV4L=ON -D WITH_QT=ON -D WITH_OPENGL=ON ..

-- xfeatures2d/vgg: Download: vgg_generated_120.i
-- 
-- General configuration for OpenCV 3.4.0 =====================================
--   Version control:               unknown
-- 
--   Extra modules:
--     Location (extra):            /home/pi/Downloads/tmp2/opencv_contrib-3.4.0/modules
--     Version control (extra):     unknown
-- 
--   Platform:
--     Timestamp:                   2021-09-26T07:01:46Z
--     Host:                        Linux 5.10.60-v7l+ armv7l
--     CMake:                       3.16.3
--     CMake generator:             Unix Makefiles
--     CMake build tool:            /usr/bin/make
--     Configuration:               RELEASE
-- 
--   CPU/HW features:
--     Baseline:
--       requested:                 DETECT
--       disabled:                  VFPV3 NEON
-- 
--   C/C++:
--     Built as dynamic libs?:      YES
--     C++11:                       YES
--     C++ Compiler:                /usr/bin/c++  (ver 8.3.0)
...
--     Applications:                tests perf_tests apps
--     Documentation:               YES (/usr/bin/doxygen 1.8.13)
--     Non-free algorithms:         NO
-- 
--   GUI: 
--     QT:                          YES (ver 5.11.3)
--       QT OpenGL support:         YES (Qt5::OpenGL 5.11.3)
--     GTK+:                        NO
--     OpenGL support:              YES (/usr/lib/arm-linux-gnueabihf/libGL.so)
--     VTK support:                 NO
-- 
--   Media I/O: 
--     ZLib:                        /usr/lib/arm-linux-gnueabihf/libz.so (ver 1.2.11)
--     JPEG:                        /usr/lib/arm-linux-gnueabihf/libjpeg.so (ver )
--     WEBP:                        build (ver encoder: 0x020e)
--     PNG:                         /usr/lib/arm-linux-gnueabihf/libpng.so (ver 1.6.36)
--     TIFF:                        /usr/lib/arm-linux-gnueabihf/libtiff.so (ver 42 / 4.1.0)
--     JPEG 2000:                   /usr/lib/arm-linux-gnueabihf/libjasper.so (ver 1.900.1)
--     OpenEXR:                     build (ver 1.7.1)
-- 

```


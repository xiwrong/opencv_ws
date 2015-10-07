cmake_minimum_required(VERSION 2.8)
project(opencv_ws)


find_package( OpenCV REQUIRED )

#link_directories(/usr/local/lib
#                 /usr/lib)




#add_executable(opencv_version opencv_version.cpp)
#target_link_libraries( opencv_version ${OpenCV_LIBS} )
#
#add_executable(introduction_to_svm introduction_to_svm.cpp)
#target_link_libraries(introduction_to_svm ${OpenCV_LIBS})
#
#add_executable(calibration calibration.cpp)
#target_link_libraries(calibration ${OpenCV_LIBS})
#
#
#add_executable(camera_calibration camera_calibration.cpp)
#target_link_libraries(camera_calibration ${OpenCV_LIBS})
#
#add_executable(test001 test001.cpp)
#target_link_libraries(test001 ${OpenCV_LIBS})
#
add_executable(02_add_image 02_add_image.cpp)
target_link_libraries(02_add_image ${OpenCV_LIBS})

add_executable(02_contrast 02_contrast.cpp)
target_link_libraries(02_contrast ${OpenCV_LIBS})
# add_executable(ch2_ex2_1  ch2_ex2_1.cpp)
add_executable(02_saltImage 02_saltImage.cpp)
target_link_libraries(02_saltImage ${OpenCV_LIBS})
# target_link_libraries(ch2_ex2_1 ${OpenCV_LIBS})

# add_executable(ch12_ex12_1 ch12_ex12_1.cpp)
# target_link_libraries(ch12_ex12_1 ${OpenCV_LIBS})

# add_executable(ch11_ex11_1 ch11_ex11_1.cpp)
# target_link_libraries(ch11_ex11_1 ${OpenCV_LIBS})

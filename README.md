# Homework-1.2
Exercice 1.2. testing CMAKE for Master on Robotics UVIC

First action is do the Fork of the webcamp repository and clone it in our computer.
```
$ git clone https://github.com/teresamg22/webcam_capture.git
Clonando en 'webcam_capture'...
remote: Enumerating objects: 62, done.
remote: Total 62 (delta 0), reused 0 (delta 0), pack-reused 62
Desempaquetando objetos: 100% (62/62), listo.
```

Later we make a new directory inside the webcam_capture directory in our computer called build and we go to that directory.
```
$ cd webcam_capture/
~/webcam_capture$ mkdir build
~/webcam_capture$ cd build

```
Then we can build and execute the program with de cmake.
```
~/webcam_capture/build$ cmake ..
-- The C compiler identification is GNU 7.4.0
-- The CXX compiler identification is GNU 7.4.0
-- Check for working C compiler: /usr/bin/cc
-- Check for working C compiler: /usr/bin/cc -- works
-- Detecting C compiler ABI info
-- Detecting C compiler ABI info - done
-- Detecting C compile features
-- Detecting C compile features - done
-- Check for working CXX compiler: /usr/bin/c++
-- Check for working CXX compiler: /usr/bin/c++ -- works
-- Detecting CXX compiler ABI info
-- Detecting CXX compiler ABI info - done
-- Detecting CXX compile features
-- Detecting CXX compile features - done
-- Found OpenCV: /usr (found version "3.2.0") 
-- Configuring done
-- Generating done
-- Build files have been written to: /home/teresa/Master/Integracion/TEST/webcam_capture/build
~/Master/Integracion/TEST/webcam_capture/build$ make
Scanning dependencies of target webcam_capture
[ 50%] Building CXX object CMakeFiles/webcam_capture.dir/src/webcam_capture.cpp.o
[100%] Linking CXX executable webcam_capture
[100%] Built target webcam_capture
~/Master/Integracion/TEST/webcam_capture/build$ ./webcam_capture 
Opening video device 0
```
And the capture of the program working below.

![Capture of webcam_capture program](https://github.com/teresamg22/Homework-1.2/blob/master/media/Captura%20de%20pantalla%20de%202019-11-02%2012-27-37.png)






# OpenCV Mobile Example

## Build steps
- Download OpenCV Mobile for Luckfox from here - https://github.com/nihui/opencv-mobile/releases/download/v23/opencv-mobile-4.8.1-luckfox-pico.zip and place in in the same folder

- Update CMakeLists.txt to point to correct compiler location

- Compilers can be downloaded from - https://github.com/LuckfoxTECH/luckfox-pico.git
- Create build directory and change change to it
- Run `cmake ..`
- Run `make`
- Binary file is created in the current folder
- Copy binary file to Luckfox board and run (you may need to kill rkipc process for camera access)

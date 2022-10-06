# MC3172 CMake Project

使用步骤:

http://www.mounriver.com/download

选择 Linux，下载 MRS_Toolchain_Linux_x64_V1.50.tar.xz

解压到 /home/nihui/osd/MRS_Toolchain_Linux_x64_V1.50

git clone https://github.com/nihui/MC3172-CMake

打开CMakeLists.txt 修改你的工具链路径,注意不要带空格
```
mkdir build
cd build
cmake ..
make
```
生成 mc3172-cmake.hex

## LICENSE
Apache-2.0

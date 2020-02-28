# QUFace SDK 样例

### Build

##### Install tools

1. CMake >= 3.10
1. [Git lfs](https://github.com/git-lfs/git-lfs)

```bash
sudo apt install cmake git-lfs # Ubuntu
brew install cmake git-lfs # MacOS
```

##### CMake options
1. `HISI_SDK_PREFIX`: 海思 SDK 目录
1. `OPENCV_PREFIX`: OpenCV 目录
1. `QUFACE_SDK_PREFIX`: QuFace SDK 目录

##### Start build

```bash
mkdir build && \
    cd build && \
    cmake .. \
    make
```
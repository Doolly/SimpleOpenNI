# Manual installation to use Kinect V2 with SimpleOpenni

### Mac OS

* Install brew

* Make sure these build tools are available: wget, git, cmake, pkg-config. Xcode may provide some of them. Install the rest via package managers.

* Download libfreenect2 source
    ```
    git clone https://github.com/OpenKinect/libfreenect2.git
    cd libfreenect2
    ```

- Install dependencies: libusb, GLFW
    ```
    brew update
    brew install libusb
    brew tap homebrew/versions
    brew install glfw3
    ```
- Install TurboJPEG (optional)
    ```
    brew install jpeg-turbo
    ```
- Install CUDA (optional): TODO
- Install OpenNI2 (optional)
    ```
    brew tap brewsci/science
    brew install openni2
    export OPENNI2_REDIST=/usr/local/lib/ni2
    export OPENNI2_INCLUDE=/usr/local/include/ni2
    ```

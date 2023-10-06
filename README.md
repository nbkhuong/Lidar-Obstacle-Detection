# Lidar Obstacle Detection

This repo is a clone of the template code of the Udacity course (https://github.com/udacity/SFND_Lidar_Obstacle_Detection). The repo is to simulate the Lidar point clouds with PCL.

## Local Installation
The below instructions are the steps to build the code in MacOS since the code was tested and run on a Macbbook M1. In the case of building on Linux or Windows, please refer to the original repo mentioned above.

### MAC

#### Install via Homebrew
1. install [homebrew](https://brew.sh/)
2. update homebrew 
	```bash
	$> brew update
	```
3. add  homebrew science [tap](https://docs.brew.sh/Taps) 
	```bash
	$> brew tap brewsci/science
	```
4. view pcl install options
	```bash
	$> brew options pcl
	```
5. install PCL 
	```bash
	$> brew install pcl
	```

6. Clone this github repo

   ```shell
   cd ~
   git clone https://github.com/nbkhuong/Lidar-Obstacle-Detection.git
   ```

7. Execute the following commands in a terminal to build and run the project

   ```shell
   cd ~/Lidar-Obstacle-Detection
   mkdir build && cd build
   cmake ..
   make
   ./environment
   ```
If you get build errors related to Qt5, make sure that the path for Qt5 is correctly set in .bash_profile or .zsh_profile (Refer [#45](https://github.com/udacity/SFND_Lidar_Obstacle_Detection/issues/45))

#### Build from Source

[PCL Source Github](https://github.com/PointCloudLibrary/pcl)

[PCL Mac Compilation Docs](https://pcl.readthedocs.io/projects/tutorials/en/latest/compiling_pcl_macosx.html#compiling-pcl-macosx)

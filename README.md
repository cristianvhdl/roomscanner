What is this?

The beginnings of a raw RGB-D data collecting app for Google Project Tango.

Features:

- 3 Scanner modes: (screenshot mode) Takes a single RGBD screenshot, generates a visualization, and saves the data into cache. (scan mode) Begins a continuous feed of RGBD data into the cache while generating a visualization. (raw mode) View a visualization of raw RGBD data.
    
- A save button that saves all cached RGBD data into a project file with epoch timestamps [TO FIX].

- RGB video feed on the top left corner [TO FIX].

Base Code: Unity Point Cloud Tango Example

Other Notes:

Many problems with properly obtaining raw YUV image data simultaneously with depth/pose/mocap data. Skeleton left commented out for future API updates.

Fixed overheating problem, and some memory leaks.

Problems with conventional functions for saving files to local Android memory - need to find a workaround for Tango.

Sample depth scan of a staircase:
![alt tag](https://raw.githubusercontent.com/andyzeng/roomscanner/master/Preview/Screenshot_2015-06-19-19-43-54.png)

Sample depth screenshot of a toilet:
![alt tag](https://raw.githubusercontent.com/andyzeng/roomscanner/master/Preview/Screenshot_2015-06-19-19-47-29.png)

Sample depth scan of a restroom (view 1):
![alt tag](https://raw.githubusercontent.com/andyzeng/roomscanner/master/Preview/Screenshot_2015-06-19-19-48-51.png)

Sample depth scan of a restroom (view 2):
![alt tag](https://raw.githubusercontent.com/andyzeng/roomscanner/master/Preview/Screenshot_2015-06-19-19-49-07.png)

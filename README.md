# Launch application
 -npm run buildLaunch (In terminal)

----------------------------------------------------------------------
potential error :
    - Be carefull to have a version of python<= 3.10
----------------------------------------------------------------------

Steps done:
 -To add button that record video RGB. First of all, I check the sdk Browser V2.0 which have different samples, especially one to register one screen.
 -Then i bind openCV to this program which is on Visual studio, and I register my image with openCV (cv::imWrite)
 -So I want to do the same for my project, and have to modify the binding.gyp files.
 - /!\Be carefull to have the good path in the binding.gyp file to your openCV lib /!\


 down and extract opencv.com/sdfsdf zip in third-party/opencv
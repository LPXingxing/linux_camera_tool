# Changelog
All notable changes to Linux Camera Tool will be documented in this file.

## [Unreleased]

## v0.3.2 - 2019-07-15  
**Changed:**
- Makefile build with C++11 so it won't fail at build
  
**Added:**
- add OpenCV CUDA support, put gain,exp max query in cam_property to avoid device mismatch, refactor the code, put macros in hardware.h for customized build
## v0.3.1 - 2019-07-12  
**Changed:**
- correct the bug of finding wrong /dev/video  gain and exposure and resolutions infomation from v4l2
## v0.3.0 - 2019-07-11
**Changed:**  
- correct frame rate calculation in >1 nbufs
## v0.2.9 - 2019-07-08
**Changed:**  
- correct the bug of read sensor val buffer being too small
## v0.2.8 - 2019-07-03
**Changed:**  
- add exposure and gain maximum value in GUI that read from v4l2 so the range doesn't confuse people
## v0.2.7 - 2019-07-02  
**Added:**
- add lif firmware update support, add elaspe time count in main
## v0.2.6 - 2019-07-02 
**Changed:**
- Merge pull request #6 from xiao6768/set_compiler_c11
- Set C++ compiler standard to c++11
## v0.2.5 - 2019-07-01  
**Changed:** (Caspar Chen  <hchen@nullmax.ai>)
- Set C++ compiler standard to c++11
- To fix compiler error "‘stoi’ is not a member of ‘std’"
## v0.2.4 - 2019-06-28  
**Added:**
- add error check for parsing  hex/dec input
- add firmware update from shell script, TODO: need to integrate into GUI
## v0.2.3 - 2019-06-26
**Added:**  
- add batch cmd parser
## v0.2.2 - 2019-06-21
**Added:**  
- add AR0231 DUAL CAM DEMO code, byte swap debug function, TODO: ui click need to further debug
## v0.2.1 - 2019-06-13
**Added:**  
- add firmware erase
  
**Changed:**
- fix register read for 16 bit value
## v0.2.0 - 2019-05-31 
**Changed:** 
- before refactor
## v0.1.9 - 2019-05-29
**Changed:**  
- refactor the code
- put all grid elements in an array and initialize their positions all together
## v0.1.8 - 2019-05-21 
**Changed:** 
- fix the bug of some register addr & val length don't work
## v0.1.7 - 2019-05-08
**Changed:**  
- fix the bug of camera tool exit when clicking 3a and choose mono, add icon for control window
## v0.1.6 - 2019-05-06
**Changed:**  
- reorg ui_ctrl, remove some warning messages
  
**Added:**
- add raw8 support
## v0.1.5 - 2019-05-01  
**Added:**
- integrate register write into json, TODO: capture images in while loop or before?
## v0.1.4 - 2019-04-30
**Changed:**  
- put header files into includes
## v0.1.3 - 2019-04-18 
**Changed:** 
- use inline for short functions, use switch to substitute if etc
- fix split screen issue bug  when use nbufs > 1, add monochrome featured button in GUI, clean up the code
## v0.1.2 - 2019-04-17
**Changed:**  
- correct udev for laptop with webcam, TODO: batchtxt etc
- add doc
## v0.1.1 - 2019-04-12
**Changed:**  
- Merge branch 'trickyMan-master'
- Merge branch 'master' of https://github.com/trickyMan/linux_camera_tool into trickyMan-master
## v0.1.0 - 2019-04-12
**Added:**  
- add datatype exp
- Update AUTHOR
- Create AUTHOR
- Create LICENSE
## v0.0.9 - 2019-04-12
**Added:**  
- close on exit
- add current frame rate into camera streaming window
## v0.0.8 - 2019-04-11  
**Added:**
- add current frame rate into camera streaming window
## v0.0.7 - 2019-04-11  
**Added:** (Philip.Pi  <piziwei@hesaitech.com>)
- delete unnecessary external variable
- return error for trigger
- add usage of cmake for this project
- 1. add cmake support. 
- 2. compile test tool when buiding current project. if not, only build the library. 
- 3. move ui_control to test/ cause it seems a test tool
## v0.0.6 - 2019-04-10  
**Added:**
- white balance new algorithm still debug
- add pics and edit readme
## v0.0.5 - 2019-04-09  
**Added:**
- add resolution and frame rate update from terminal
- add gitignore
## v0.0.4 - 2019-04-08  
**Added:**
- add resolution and frame rate
- add readme and .gigignore etc
- add awb in ui control
- add white balance,TODO: edit UI
## v0.0.3 - 2019-04-05  
**Changed:**
- remove unused libraries
- remove unnecessary comments
- remove unnecessary file guard
- remove unnecessary file guard
- remove all the warnings
- 16-bit/8-bit address width for write
- add most functions
## v0.0.2 - 2019-04-04
**Changed:**  
- commit temp before go home
## v0.0.1 - 2019-04-03 
**Added:** 
- modify except ui and extend_cam_ctrl
- initial commit

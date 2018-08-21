
**DATAQSubsitute/dio**

"dio" is a repository that consists of prototype Python scripts intended and Javascript-based Node-red flows to work in tandem with the products
developed by DATAQ.

**PYTHON SCRIPTS**

"dio_oz_test.py", which will be renamed later on, is a script that will activate the DAQ instrument Model 1110 remotely upon running. It locates the connected instrument and gives it an input/output command 10 times.

"blinky.py" will manipulate the LED on the connected 1110 instrument.

Further developed scripts will work with not only Model 1110 for more complex commands, but these programs will work with other products manufactured by DATAQ as well.

These scripts are also an attempt to have DATAQ instruments with other operating systems like Raspberry Pi or Linux.

All scripts are located in the "python" branch.

**NODE-RED FLOWS**

In the master branch is the latest version of a Node-red flow that I was working on for a DATAQ product that records changes in voltage over long periods of time. It writes those recordings to csv files in a PC location, which can also be constantly copied to a cloud drive it set as such. In addition, the readings can be displayed on gauges in the Node-red's dashboard UI.

This flow is named 8g_final in the master branch. Old drafts and other applications made using Node-red are located in the "node-red" branch.

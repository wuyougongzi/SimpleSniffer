# Linux Sniffer (homework)


## Dependency
* qt 5
* libpcap
* OS: linux

## Comments
Please do not push sniffer.pro.user anymore. Conflicts will happen.

## Code Structure
* NetworkChoice(Dialog) -- Sniffer
* MainWindow
  * CaptureThread
    * Sniffer
      * (inherit) CSniffer
  * Filter
  * MultiView
    * (inherit) ListView
      * Packets 

## Current tasks
* waiting for ultimate tree structure to implement new features
* IP slides reunited (undo)
* analyse file type which packets transmit (undo)
* search and filtrate packets by protocal content (soon)
* clicked right mouse on TreeView can save current packet info to file (finished)
* analyse packets upon different protocols 
  * implement code in capturethread.cpp: run
  * show brief packets' info in List View (finished)
  * show detail in a tree structure (untested)
  * show hex raw data in Text View (untested)
* file operation
  * choose a file to save captured data (untested)
  * load a file with packets' data  (untested)
* packets filter (finished)
  * set standard rules and check user's input (finished)
  * filtrate packets with fixed rules (finished)
* using a dialog to choose network (finished)
  * dialog should show network info (finished)
  * user choose network in a list (finished)
  * press OK and network info should be passed to mainwindow (finished)

# Robotframework Live Logs

This repo consist of generating live logs while execution is in progress

Steps to Use:

 - Step 1: Download or clone this repo
 
 - Step 2: Copy `LiveLogsListener.py` to your project

 - Step 3: Execute test case/suites using LogListener
   > - `robot --listener LiveLogsListener.py Tests` 

 - Step 4: A new browser will be opened with logs
   > Note: Page refresh's for every 5 seconds.
   > - Users can modify reload time from .py file
   > - `<meta http-equiv="refresh" content="5" >`

---

Available Logs:

 - LiveLogsListener.py --> Suite, Test and Keyword status
    > Uses ROBOT_LISTENER_API_VERSION = 2

 - LogListener.py --> Suite and Test status
    > Uses ROBOT_LISTENER_API_VERSION = 3

---

*Screenshot*

<img src="/LiveLogs.jpg" alt="LiveLogs">

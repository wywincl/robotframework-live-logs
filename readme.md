# Robotframework Live Logs

This repo consist of generating live logs while execution is in progress

Steps to Use:

 - Step 1: Download this repo
 - Step 2: Copy `LiveLogs.py` to your project
 - Step 3: Execute test case/suites using LogListener
   > - `robot --listener LiveLogs.py Tests` 
 - Step 4: A new browser will be opened with logs
   > Note: Page refresh's for every 5 seconds.
   > - Users can modify reload time from .py file
   > - `<meta http-equiv="refresh" content="5" >`

---

Available Logs:

 - LiveLogs.py --> Suite, Test and Keyword status
    > Uses ROBOT_LISTENER_API_VERSION = 2

 - LogListener.py --> Suite and Test status
    > Uses ROBOT_LISTENER_API_VERSION = 3

---

*Screenshot*

<img src="https://i.ibb.co/ncYCMcM/LiveLogs.jpg" alt="LiveLogs">

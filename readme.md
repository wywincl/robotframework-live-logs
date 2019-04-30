# Robotframework Live Logs

This repo consist of generating live logs while execution is in progress

Steps to Use:

 - Step 1: Download this repo
 - Step 2: Copy `LogListener.py` to your project
 - Step 3: Execute test case/suites using LogListener
   > - `robot --listener LogListener.py Tests` 
 - Step 4: A new browser will be opened with logs
   > Note: Page refresh's for every 5 seconds.
   > - Users can modify reload time from .py file
   > - `<meta http-equiv="refresh" content="5" >`

---

Note: This example consist of only Suite and Tests info, In future will add logging for keywords as well

*Screenshot*

<img src="https://i.ibb.co/Wpq70br/LiveLogs.png" alt="LiveLogs" border="0">

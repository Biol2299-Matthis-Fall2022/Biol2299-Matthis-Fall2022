# How to clone and run a Github repository

[![hackmd-github-sync-badge](https://hackmd.io/Uv9pkkvHThaNlylNjBNXlg/badge)](https://hackmd.io/Uv9pkkvHThaNlylNjBNXlg)

###### tags: diataxis, how-to, pycharm, github, documentation

1. Install Pycharm 
    - Community version is fine
2. Open Pycharm 
    - NOTE - I'm not sure exactly what you will see the first time you open the program. Add a comment here if there is some step I skipped
3.  In the top menu bar: Git > Clone...
    - a window will pop up
    - select the `Repository URL` tab in the left panel
    - Set: 
        - **URL:** The url of the repo
            -  e.g. https://github.com/freemocap/freemocap
        - **Directory: ** The location on your computer where you want the *contents* of that repo to be cloned to
            - e.g. `C:\Users\jon\freemocap`
    - Click `Clone` button in bottom right
    - WAIT FOR IT TO COMPLETE IT'S STUFF BEFORE CLICKING AROUND
        - There's a status bar in the bottom or the window
4. Assuming the repo has a `requirements.txt` file, PyCharm should pop up a little `Creating Virtual Environments Window` (if it doesn't, I'll make another How-To stub for how to set the python interpretter. hint, bottom right of screen):
    - **Location:** will be auto-set to `path to this rep\ venv`
    - **Base Interpreter: ** will be set to your default Python installation
    - **Dependencies:** will point to the `requirements.txt` file
    - Click OK
    - Let it do it's thing (status in bottom bar)
    - It might take a while if there are a bunch of packages
    - You should see something like `Python 3.10 {Name Of This Repo}` pop up in the bottom right
5. Test that it worked!
    - Open a Terminal window in Pycharm (click `Terminal` in the bottom left of screen)
    - it should say `(venv)` on the left of each line (that means your interpreter is set to the `python` executable in the `venv\` folder)
    - enter the command `pip list` to check your installed packages
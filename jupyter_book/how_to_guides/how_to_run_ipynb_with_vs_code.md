# How to run a Jupyter/iPython notebook (`.ipynb`) with VS Code

## Step 1. [Download VS Code](https://code.visualstudio.com/)
```{note}
*Note - I've recommended PyCharm before but I've recently realized/come to the conclusion that VS Code is a better option for handling `ipynb` files (aka `Jupyter Notebooks`). I do still think that  PyCharm is a better tool for full-on python-based programming though. It's all about using the right tool for the job ✨*
```
## Step 2. **Get the code on your computer somehow**

```{note}
Do **EITHER** Method 1 **OR** Method 2 (doing both is redundant)
```

### **Method 1 (Beginner/Easy mode)**
```{note}
This method involves manually downloading the class repository from the GitHub website. 

Its simple and straightforward, and the **recommended** option for folks who want to get things up and running as quickly as possible.
```
- Download the repository from the web page
        - go to : https://github.com/Biol2299-Matthis-Fall2022/Biol2299-Matthis-Fall2022
        - Click on `Code` button
        - Select `Download ZIP`
        - Unzip it somewhere on your computer
        - PROCEED TO STEP 3
        
### **Method 2 (Advanced/Cool kid hacker mode)**   
```{note}
This method involves cloning the repository from the command line using `git`.

It's rather more advanced, but it will provide XP in the powerful magicks of `git` and 'command line'/'terminal' usage - which are important skills to master if you want to be a fancy pants comp sci hacker type 👽
```

- Clone the repository via Git and the command line 
- Open your favorite command line interface (CLI)
    - Mac/Linux - 
        - press `Command` + `space` and search for and open a program called `Terminal` 
    - Windows
        - Press `Windows` key and search for/open`Command Prompt`
- Type `git` and press enter to check if you have `git` installed
    - if it says `Git not found` or something:
      - Install Git: https://git-scm.com/downloads (just pick all the default options in the installer)
- Navigate to the place you want to download the repository with `cd` ('change directory') commands
  - Enter this command to download the repo to your computer
```bash
git clone  https://github.com/Biol2299-Matthis-Fall2022/Biol2299-Matthis-Fall2022
```


#### Wow you did it probably!
[so cool 😎](https://cdn.costumewall.com/wp-content/uploads/2017/08/hackerman.jpg)



## 3. Open the repository **folder** in VS Code
```{note}
With most code based project, we want to open the *entire folder* in the software IDE (e.g. VS Code or PyCharm) rather than openning a single file (i.e. a `.py` or `'.ipynb'` )
```

In VS Code, in the top bar (aka the `Menu bar`)
- File > 'Open Folder'
    - Select the repository folder you downloaded/cloned in [Step 2](#2-Get-the-code-on-your-computer-somehow)
    - it will be called `Biol2299-Matthis-Fall2022`

                    
                    

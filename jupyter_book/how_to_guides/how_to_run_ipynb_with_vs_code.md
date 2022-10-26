# How to run a Jupyter/iPython notebook (`.ipynb`) with VS Code

## 1. [Download VS Code](https://code.visualstudio.com/)
:::{info}
I've recommended PyCharm before, but I've recently realized/come to the conclusion that VS Code is a better option for handling `ipynb` files (aka `Jupyter Notebooks`). 
:::

## 2. **Get the code on your computer somehow**

### **Method 1 (Easy mode)** 
- Download the repository from the web page
        - go to : https://github.com/Biol2299-Matthis-Fall2022/Biol2299-Matthis-Fall2022
        - Click on `Code` button
        - Select `Download ZIP`
        - Unzip it somewhere on your computer
        - PROCEED TO STEP 3
        - 
:::spoiler **Method 2 (Cool kid hacker mode)**
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

:::success 
:::spoiler Wow you did it probably!
[so cool :sunglasses:](https://cdn.costumewall.com/wp-content/uploads/2017/08/hackerman.jpg)
:::  

## 3. Open the repository **folder** in VS Code
:::info
With most code based project, we want to open the *entire folder* in the software IDE (e.g. VS Code or PyCharm) rather than openning a single file (i.e. a `.py` or `'.ipynb'` )
:::
In VS Code, in the top bar (aka the `Menu bar`)
- File > 'Open Folder'
    - Select the repository folder you downloaded/cloned in [Step 2](#2-Get-the-code-on-your-computer-somehow)
    - it will be called `Biol2299-Matthis-Fall2022`

                    
                    

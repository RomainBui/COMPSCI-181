# COMPSCI-181
Machine Learning at Harvard

### System Requirements
Make sure your system meets these requirements:
  - Operating system: MacOS 10.7 10.8 10.9 10.10 (it has been tested successfully on these)
  - RAM: 2GB.
  - Disk space: 2GB

### Step 1: Install Command Line Tools
  - Open terminal, type “xcode-select --install” in terminal (without quotes)
  - A pop-up windows will appear asking you about install tools, choose install tools, wait install to finish
  
### Step 2: Install Homebrew

  ```
  ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  brew tap samueljohn/python
  brew tap homebrew/science
  ```

### Step 3: Install Python and its modules
    
  ```
  brew install python
  pip install numpy
  pip install scipy
  pip install matplotlib
  pip install pandas
  pip install scikit-learn
  ```
  
### Step 4: Install MacTex
  I recommend using a MacTeX distribution: https://www.tug.org/mactex/, or (skip if you download from the link) install via Homebrew
  ```
  brew install Caskroom/cask/mactex
  ```

### Step 5: Install Github

  1. I recommend download and install the latest version of Git from https://git-scm.com/downloads, or (skip if you download from the link) install via Homebrew
  
    ```
    brew install git
    ```
  
  2. Tell Git your name so your commits will be properly labeled.
  
     ``` 
     git config --global user.name "YOUR NAME" 
     ```
     
  3. Tell Git the email address that will be associated with your Git commits.
  
     ```
     git config --global user.email "YOUR EMAIL ADDRESS"
     ```
     

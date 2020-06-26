# Customize-Emacs-Locally


### Steps:

#### 1. Install Brew and Emacs

Refer to [Brew Website] (https://brew.sh/) to install the helpful tool Brew. Then use the command `brew install emacs` to install Emacs26. 

#### 2. Install Clang-format
Before you configure your emacs, you need to install corresponding binary executable, like clang-format. Use the following command to install it `brew install clang-format` .


#### 3. Run the script
Download the script and run it. Then done.

#### 4. Note
You could comment out the line `(package-refresh-contents)` in your `~/.emacs` file since you dont necessary need it to check for update each time you use the Emacs. 

P.S. Some part of the packages require the Emacs version be and above 25.0.

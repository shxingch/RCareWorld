![alt text](rcareworld.png)

# Here is the code for RCareWorld V1.0.0 🦾
- Check the website https://emprise.cs.cornell.edu/rcareworld/

We support Windows, Linux (Tested on Ubuntu), and MacOS. You need to make sure git and git-lfs are installed on your system. You should use Git Bash if you have it (else Powershell) for windows, 
and use bash for Linux and MacOS.

# Clone this repo

Open up Terminal, Git Bash, or Powershell on your computer.

If you have ssh key setup on github use:
`git clone git@github.com:empriselab/RCareWorld.git`

otherwise,
`git clone https://github.com/empriselab/RCareWorld.git`

Navigate to the `RCareWorld` repository using the cd command.
Example command: `cd RCareWorld`

Checkout to the hackathon branch:
`git checkout hackathon`

Next, `git lfs pull`.

Then navigate to `TestInstall` folder which is in `hackathon_demo` folder.

You should expect to see `Linux.zip`, `Mac.zip`, and `Windows.zip` under `hackathon_demo/Build/TestInstall` folder. Unzip the one that matches your system.

# Install guide

If you are preceeding immediately after the "Clone this repo" step, navigate back to the RCareWorld directory.
Example commands: `cd ~/RCareWorld`

If you already have anaconda installed our your system, skip installing `install_conda`. 

## Windows
Run `install/Windows/install_conda.bat`, and then run `install/Windows/install_pyrcareworld.bat`.

Example commands:
`./install/Windows/install_pyrcareworld.bat`

Note on Windows you may need to install Microsoft Visual C++ 14.0 or greater using Visual Studio Installer.

## Ubuntu
Run `install/Ubuntu/install_conda.sh`, and then run `install/Ubuntu/install_pyrcareworld.sh`.

Example commands:
`bash install/Ubuntu/install_pyrcareworld.sh`

## Mac
Run `install/Mac/install_conda.sh`, and then run `install/Mac/install_pyrcareworld.sh`.

Example commands:
`bash install/Mac/install_pyrcareworld.sh`. 

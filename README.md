# CoderDojo Winter 2018 InstallFest

## For MAC users

_Install Node and NPM via Homebrew_
<http://blog.teamtreehouse.com/install-node-js-npm-mac>
The following commands should be run in your terminal:
ruby -e "$(curl -fsSL <https://raw.githubusercontent.com/Homebrew/install/master/install)”>
brew install node
(check if installed) node -v
(check if installed) npm -v
_If you already have homebrew installed, run:_
brew update
brew upgrade node
sudo npm update -g npm
_Install Grunt and the Grunt-CLI_
sudo npm install -g grunt grunt-cli
_Install git_
<https://www.atlassian.com/git/tutorials/install-git#mac-os-x> (#Install Git with Homebrew)
If you do not already have a githubt account, go to github.com and set up your account
brew install git
git —version
git config --global user.name "Your Name”
git config --global user.email youremail@email.com
Set SSH key and passphrase <https://help.github.com/articles/working-with-ssh-key-passphrases/>

## For PC users

Make sure you have the Windows Command Prompt installed or install <http://cmder.net/>
_Install Node and NPM (even if you already have it installed)_
<http://blog.teamtreehouse.com/install-node-js-npm-windows>
  Download Node installer <https://nodejs.org/en/> run installer and follow prompts
  Restart your computer
  Open Windows Command Prompt <https://www.lifewire.com/how-to-open-command-prompt-2618089>
  (check if installed) node -v
  (check if installed) npm –v
_Install Grunt and the Grunt-CLI_
  npm install -g grunt grunt-cli
_Install git_
<https://www.atlassian.com/git/tutorials/install-git#windows> (#Install Git on Windows)
  Download <https://gitforwindows.org/>
  git config --global user.name "Your Name”
  git config --global user.email " youremail@email.com"
  Set SSH key and passphrase <https://help.github.com/articles/working-with-ssh-key-passphrases/#platform-windows>


## For both Mac and PC users after npm and git are installed

_Download the project files_
<https://github.com/CharlesRiverCoderDojo/movie-app-client-starter-code>
git clone git@github.com:CharlesRiverCoderDojo/movie-app-client-starter-code.git
git init
npm install
grunt serve (to run front-end server)
The project will be available at <http://localhost:8080/>
To add the API to your project, the URL you will need is <https://88d437xnc6.execute-api.us-east-1.amazonaws.com/api/>

# gitcommand
Short helper scripts for working with git, written for bash.

## Installation
Install in a convenient location, prefferably somewhere with in your `$PATH`. Most bashrc files loads the folder `~/bin` or `~/.local/bin`; these would be suitable locations for the scripts.

## Usage
### commit <message>
Takes the parameter of a commit message. The script runns the following commands in order
  
    git add .
    git commit -m <message>
    git push

### ssh-gen <email>
Generates an ssh key pair for easy connection to GitHub. The script also tries to copy the public key to your system clipboard, to make it easier to paste it onto the webpage. The email paramter is non optional as it is needed for the generation of the ssh keys.

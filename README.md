# GDP-00_Temporary_Cybok
This repo houses the temporary Cybok resources until a more permanent solution can be arranged.

## Connect your VM to GitHub

In a terminal window connected to your Azure VM, set your Git user and email:
- `git config --global user.name "<Firstname Lastname>"`
- `git config --global user.email "<firstname.lastname@dewc.com>"`

Create a new SSH key-pair so the VM can pull and push from GitHub:
- `ssh-keygen` and enter a passphrase when prompted
- `cat /home/azureuser/.ssh/id_rsa.pub`
- copy and paste the key into your GitHub *Settings* -> *SSH and GPG keys* as a 'New SSH key'
- you can now clone this (and any future) repo(s)

## Upskilling
The following concepts will form a good base for future projects to build on:
- SSH
- Linux
- VSCode
- Debugging
- Types of DBs
- Git

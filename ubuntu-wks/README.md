##Assumptions: 
This is a completly new setup

## Prerequisite

**Create a Git repository on github or your Git server**

**Create an OpenSSH key to be used for cloning Git repository**

    ssh-keygen -t ed25519 -C "yourname@yourdomain.com"

**Install git on your local machine**
    
    sudo apt install git

**Pull down repository**

    git clone https://url/to/your/repository

**Add a file to version control**
    
    git add <filename>

**Create a git commit**
    
    git commit -m "message about the commit"

**Push the changes up to Github**
    
    git push origin main

## Creating PlayBook

**Install ansible**

    sudo apt install ansible

**create Playbook**

    nano local.yml

**Run Playbook using ansible pull**

    sudo ansible-pull -U 
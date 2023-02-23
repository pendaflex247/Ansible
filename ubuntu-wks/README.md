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

**Install dconf cli package**

    sudo apt install dconf-cli

    sudo apt install python3-psutil

    #dump dconf setting to see what is avaible

    dconf dump / > settings.txt

    nano settings

**Create Playbook**

    nano local.yml

    #if you edit the git repo update the git repo before you run the playbook 
    
**Run Playbook using ansible pull**

    sudo ansible-pull -U https://github.com/pendaflex247/ubuntu-wks.git


## Running the play book on a new desktop or laptop

    sudo apt install ansible

    sudo ansible-pull -U https://github.com/pendaflex247/ubuntu-wks.git

**Content**

    Packages:

    Wallpaper:

    Hostname:

    Hosts:

    Add user:

    set ipaddress:


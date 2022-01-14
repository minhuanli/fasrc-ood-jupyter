# fas-ood-jupyter
OnDemand app for serving Jupyter notebooks out of your local path 

### Installation
 1) First, you need to (enable the FAS RC VPN)[#rc-vpn]
 2) Create a new folder in your home directory on the RC cluster
    `mkdir ~/fasrc/dev`
 3) Navigate to the Open OnDemand app (page)[https://vdi.rc.fas.harvard.edu]
 4) Click on the `</> Develop` dropdown (top right) and go to "My SandBox Apps (Development)"
 5) Click on "New App" (top left)
 6) Click on "Clone Existing App"
 7) Fill in some suitable directory name. This will determine the name of the directory inside `~/fasrc/dev` used for this project
 8) Paste one of the following into the "Git remote" dialog box
    - `https://github.com/Hekstra-Lab/fasrc-ood-jupyter` if you do not have `ssh` configured or do not want to use it
    - `git@github.com:Hekstra-Lab/fasrc-ood-jupyter.git` if you want to sue `ssh`. This requires having an `ssh` key configured on the cluster and registered with your github account.
 9) Click "Submit"

### RC VPN
 - General (instructions)[https://docs.rc.fas.harvard.edu/kb/vpn-setup/] for the RC VPN are available in the FASRC docs
 - Linux specific instructions using `openconnect` (here)[https://docs.rc.fas.harvard.edu/kb/linux-vpn/]


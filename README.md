# AI-ml-engineering-with-Azure
projects which includes pytorch,tensorflow and AI models

# Project1 with Tensorflow:
Implementing a neural network with TensorFlow 
in this I have build a neural network using TensorFlow, train it on the Fashion MNIST dataset, and evaluate its performance.
Steps:
Load and preprocess a dataset using TensorFlow.

Define a neural network architecture using the Keras Sequential API.

Compile and train the neural network on a dataset.

Evaluate the model's performance using test data.

Experiment with different model parameters to enhance accuracy.

# Project2 :
differentiate between pytorch and tensorflow with CNN implementation

# Project3:
comparing DL techniques like FNN,CNN,RNN,GAN,Autoencoder


Welcome to the Azure Machine Learning terminal

Enter "git clone [url]" to clone a repo                         
Enter "git --help" to learn about Git CLI. To learn more about integrating Git with the Azure Machine Learning terminal, navigate here:
        https://learn.microsoft.com/en-us/azure/machine-learning/concept-train-model-git-integration#clone-git-repositories-into-your-workspace-file-system
Enter "az ml --help" to learn about Azure ML CLI v2                                

Note: Use "az login --identity" instead of "az login" to avoid device code authentication


(azureml_py38) azureuser@simplysowj1:~/cloudfiles/code/Users/simplysowj/gittest$ git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint:
hint:   git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint:
hint:   git branch -m <name>
Initialized empty Git repository in /mnt/batch/tasks/shared/LS_root/mounts/clusters/simplysowj1/code/Users/simplysowj/gittest/.git/
(azureml_py38) azureuser@simplysowj1:~/cloudfiles/code/Users/simplysowj/gittest$ git add .fatal: detected dubious ownership in repository at '/mnt/batch/tasks/shared/LS_root/mounts/clusters/simplysowj1/code/Users/simplysowj/gittest'
To add an exception for this directory, call:

        git config --global --add safe.directory /mnt/batch/tasks/shared/LS_root/mounts/clusters/simplysowj1/code/Users/simplysowj/gittest
(azureml_py38) azureuser@simplysowj1:~/cloudfiles/code/Users/simplysowj/gittest$ git config --global --add safe.directory /mnt/batch/tasks/shared/LS_root/mounts/clusters/simplysowj1/code/Users/simplysowj/gittest
(azureml_py38) azureuser@simplysowj1:~/cloudfiles/code/Users/simplysowj/gittest$ git add .(azureml_py38) azureuser@simplysowj1:~/cloudfiles/code/Users/simplysowj/gittest$ git commit -m "initial commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'azureuser@simplysowj1.(none)')
(azureml_py38) azureuser@simplysowj1:~/cloudfiles/code/Users/simplysowj/gittest$ git config --global user.email "simplysowj@gmail.com""
> git config --global user.name "sowjanya"
> 
> git config --global user.email "simplysowj@gmail.com""
git config --global user.name "sowjanya"
(azureml_py38) azureuser@simplysowj1:~/cloudfiles/code/Users/simplysowj/gittest$ git commit -m "initial commit"
[master (root-commit) b765114] initial commit
 6 files changed, 179 insertions(+)
 create mode 100644 .amlignore
 create mode 100644 .amlignore.amltmp
 create mode 100644 .ipynb_aml_checkpoints/Untitled-checkpoint2025-0-5-0-51-49Z.ipynb
 create mode 100644 .ipynb_aml_checkpoints/Untitled-checkpoint2025-0-5-0-52-40Z.ipynb
 create mode 100644 Untitled.ipynb
 create mode 100644 untitled.ipynb.amltmp
(azureml_py38) azureuser@simplysowj1:~/cloudfiles/code/Users/simplysowj/gittest$ git remote add origin https://github.com/simplysowj/gittest.git
(azureml_py38) azureuser@simplysowj1:~/cloudfiles/code/Users/simplysowj/gittest$ (type -p wget >/dev/null || (sudo apt update && sudo apt-get install wget -y)) \
> && sudo mkdir -p -m 755 /etc/apt/keyrings \
>         && out=$(mktemp) && wget -nv -O$out https://cli.github.com/packages/githubcli-archive-keyring.gpg \
>         && cat $out | sudo tee /etc/apt/keyrings/githubcli-archive-keyring.gpg > /dev/null \
> && sudo chmod go+r /etc/apt/keyrings/githubcli-archive-keyring.gpg \
> && echo "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/githubcli-archive-keyring.gpg] https://cli.github.com/packages stable main" | sudo tee /etc/apt/sources.list.d/github-cli.list > /dev/null \
> && sudo apt update \
> && sudo apt install gh -y
2025-01-05 01:14:56 URL:https://cli.github.com/packages/githubcli-archive-keyring.gpg [2270/2270] -> "/tmp/tmp.qPczq318Kp" [1]
Hit:1 http://azure.archive.ubuntu.com/ubuntu focal InRelease
Get:2 http://azure.archive.ubuntu.com/ubuntu focal-updates InRelease [128 kB]            
Get:3 http://azure.archive.ubuntu.com/ubuntu focal-backports InRelease [128 kB]          
Get:4 http://azure.archive.ubuntu.com/ubuntu focal-security InRelease [128 kB]           
Hit:5 https://packages.microsoft.com/repos/azure-cli focal InRelease                     
Get:6 https://packages.microsoft.com/ubuntu/20.04/prod focal InRelease [3632 B]          
Get:7 file:/var/cudnn-local-repo-ubuntu2004-9.1.1  InRelease [1572 B]                    
Get:8 https://cli.github.com/packages stable InRelease [3917 B]                          
Get:9 https://nvidia.github.io/libnvidia-container/stable/ubuntu18.04/amd64  InRelease [1484 B]
Hit:10 https://nvidia.github.io/nvidia-container-runtime/stable/ubuntu18.04/amd64  InRelease
Get:11 file:/var/nccl-repo-2.2.13-ga-cuda9.2  InRelease                                  
Ign:11 file:/var/nccl-repo-2.2.13-ga-cuda9.2  InRelease                                  
Get:7 file:/var/cudnn-local-repo-ubuntu2004-9.1.1  InRelease [1572 B]                    
Get:12 file:/var/nvidia-driver-local-repo-ubuntu2004-535.183.06  InRelease [1572 B]      
Hit:13 https://nvidia.github.io/nvidia-docker/ubuntu18.04/amd64  InRelease               
Get:12 file:/var/nvidia-driver-local-repo-ubuntu2004-535.183.06  InRelease [1572 B]      
Get:14 file:/var/nccl-repo-2.2.13-ga-cuda9.2  Release [574 B]                            
Get:14 file:/var/nccl-repo-2.2.13-ga-cuda9.2  Release [574 B]                            
Hit:15 https://storage.googleapis.com/tensorflow-serving-apt stable InRelease            
Get:16 https://developer.download.nvidia.com/compute/cuda/repos/ubuntu2004/x86_64  InRelease [1581 B]
Hit:17 https://apt.repos.intel.com/mkl all InRelease                                     
Hit:18 http://ppa.launchpad.net/cran/libgit2/ubuntu focal InRelease
Hit:19 http://ppa.launchpad.net/git-core/ppa/ubuntu focal InRelease
Get:20 http://azure.archive.ubuntu.com/ubuntu focal-updates/main amd64 Packages [3735 kB]
Get:21 http://azure.archive.ubuntu.com/ubuntu focal-updates/main Translation-en [570 kB]
Get:22 http://azure.archive.ubuntu.com/ubuntu focal-updates/restricted amd64 Packages [3493 kB]
Get:23 http://azure.archive.ubuntu.com/ubuntu focal-updates/restricted Translation-en [488 kB]
Get:24 http://azure.archive.ubuntu.com/ubuntu focal-updates/universe amd64 Packages [1253 kB]
Get:25 http://azure.archive.ubuntu.com/ubuntu focal-updates/universe Translation-en [300 kB]
Get:26 http://azure.archive.ubuntu.com/ubuntu focal-security/main amd64 Packages [3343 kB]
Get:27 http://azure.archive.ubuntu.com/ubuntu focal-security/main Translation-en [489 kB]
Get:28 http://azure.archive.ubuntu.com/ubuntu focal-security/restricted amd64 Packages [3319 kB]
Get:29 http://azure.archive.ubuntu.com/ubuntu focal-security/restricted Translation-en [464 kB]
Get:30 http://azure.archive.ubuntu.com/ubuntu focal-security/universe amd64 Packages [1031 kB]
Get:31 http://azure.archive.ubuntu.com/ubuntu focal-security/universe Translation-en [218 kB]
Get:32 https://packages.microsoft.com/ubuntu/20.04/prod focal/main amd64 Packages [324 kB]
Get:33 https://packages.microsoft.com/ubuntu/20.04/prod focal/main arm64 Packages [69.4 kB]
Get:34 https://packages.microsoft.com/ubuntu/20.04/prod focal/main armhf Packages [23.8 kB]
Get:35 https://cli.github.com/packages stable/main amd64 Packages [345 B]                
Get:36 https://cloud.r-project.org/bin/linux/ubuntu focal-cran40/ InRelease [3622 B]
Get:38 https://developer.download.nvidia.com/compute/cuda/repos/ubuntu2004/x86_64  Packages [1890 kB]
Get:39 https://cloud.r-project.org/bin/linux/ubuntu focal-cran40/ Packages [88.8 kB]
Fetched 21.5 MB in 3s (6741 kB/s)                                  
Reading package lists... Done
Building dependency tree       
Reading state information... Done
37 packages can be upgraded. Run 'apt list --upgradable' to see them.
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following NEW packages will be installed:
  gh
0 upgraded, 1 newly installed, 0 to remove and 37 not upgraded.
Need to get 13.7 MB of archives.
After this operation, 50.4 MB of additional disk space will be used.
Get:1 https://cli.github.com/packages stable/main amd64 gh amd64 2.64.0 [13.7 MB]
Fetched 13.7 MB in 0s (56.5 MB/s)
Selecting previously unselected package gh.
(Reading database ... 172533 files and directories currently installed.)
Preparing to unpack .../archives/gh_2.64.0_amd64.deb ...
Unpacking gh (2.64.0) ...
Setting up gh (2.64.0) ...
Processing triggers for man-db (2.9.1-1) ...
(azureml_py38) azureuser@simplysowj1:~/cloudfiles/code/Users/simplysowj/gittest$ gh auth login
? Where do you use GitHub? GitHub.com
? What is your preferred protocol for Git operations on this host? HTTPS? Authenticate Git with your GitHub credentials? Yes
? How would you like to authenticate GitHub CLI? Login with a web browser

! First copy your one-time code: 10F9-0B83
Press Enter to open https://github.com/login/device in your browser... 
/usr/bin/xdg-open: 869: www-browser: not found
/usr/bin/xdg-open: 869: links2: not found
/usr/bin/xdg-open: 869: elinks: not found
/usr/bin/xdg-open: 869: links: not found
/usr/bin/xdg-open: 869: lynx: not found
/usr/bin/xdg-open: 869: w3m: not found
xdg-open: no method available for opening 'https://github.com/login/device'
! Failed opening a web browser at https://github.com/login/device
  exit status 3
  Please try entering the URL in your browser manually
✓ Authentication complete.
- gh config set -h github.com git_protocol https
✓ Configured git protocol
! Authentication credentials saved in plain text
✓ Logged in as simplysowj
(azureml_py38) azureuser@simplysowj1:~/cloudfiles/code/Users/simplysowj/gittest$ git push -u origin master
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 1.32 KiB | 61.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/simplysowj/gittest.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.
(azureml_py38) azureuser@simplysowj1:~/cloudfiles/code/Users/simplysowj/gittest$ git checkout -b
error: switch `b' requires a value
(azureml_py38) azureuser@simplysowj1:~/cloudfiles/code/Users/simplysowj/gittest$ git checkout -b feature-branch
Switched to a new branch 'feature-branch'
(azureml_py38) azureuser@simplysowj1:~/cloudfiles/code/Users/simplysowj/gittest$ git add .(azureml_py38) azureuser@simplysowj1:~/cloudfiles/code/Users/simplysowj/gittest$ git commit -m "added
> "
[feature-branch 938994d] added
 3 files changed, 50 insertions(+), 2 deletions(-)
 create mode 100644 .ipynb_aml_checkpoints/Untitled-checkpoint2025-0-5-1-31-5Z.ipynb
(azureml_py38) azureuser@simplysowj1:~/cloudfiles/code/Users/simplysowj/gittest$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.
(azureml_py38) azureuser@simplysowj1:~/cloudfiles/code/Users/simplysowj/gittest$ git merge feature-branch
Updating b765114..938994d
Fast-forward
 .../Untitled-checkpoint2025-0-5-1-31-5Z.ipynb             | 46 +++++++++++++++++++++++++
 Untitled.ipynb                                            |  3 +-
 untitled.ipynb.amltmp                                     |  3 +-
 3 files changed, 50 insertions(+), 2 deletions(-)
 create mode 100644 .ipynb_aml_checkpoints/Untitled-checkpoint2025-0-5-1-31-5Z.ipynb
(azureml_py38) azureuser@simplysowj1:~/cloudfiles/code/Users/simplysowj/gittest$ 

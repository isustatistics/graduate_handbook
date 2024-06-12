# Getting Started

To contribute to this graduate handbook, 
you will utilize the functionality of git repository hosted at github.com. 
The first step is to 

- [ ] [create an account at github.com](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github).

To ensure this account is available after you leave Iowa State University,
it is recommended you use a personal email address. 

There are many different ways to interact with github.com. 
This opinionated way uses RStudio as the main software for interacting with
github.com. 
More information about interacting with git and github through R is available
from these resources

- [Happy Git and GitHub for the useR](https://happygitwithr.com/) 
- [github rstudio resource](https://resources.github.com/github-and-rstudio/),
- [Posit resource](https://docs.posit.co/ide/user/2023.06.1/ide/guide/tools/version-control.html)

## Install Software

Install the following software

- [ ] [R](https://www.r-project.org/)
- [ ] [RStudio Desktop](https://posit.co/download/rstudio-desktop/)
- [ ] [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

## Configure Git/GitHub

Configure git on your computer using Terminal in RStudio, enter the following

```
git config --global user.name "Jane Doe"
git config --global user.email "jane@example.com"
```

Make sure the email address entered here is the same address you used for your
github.com account. 

To ease the interaction with github.com, it is recommended that you set up 
SSH keys. 

- [ ] [Create SSH key in Rstudio](https://forum.posit.co/t/github-rstudio-how-to-switch-from-password-to-ssh/97096) (Leave passphrase blank)
- [ ] Click "View public key" and copy to clipboard
- [ ] [Add SSH RSA key to github.com](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account#adding-a-new-ssh-key-to-your-account) (Step 1 has already been completed in the previous step.)
- [ ] [Test ssh github.com connection](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/testing-your-ssh-connection). 

Using Terminal tab in RStudio enter the following

> ssh -T git@github.com

## Setup repository

- [ ] [Fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) the [isustatistics/graduate_handbook](https://github.com/isustatistics/graduate_handbook) repository. 
- [ ] [Copy **SSH** (not HTTPS) GitHub CLI](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository#cloning-a-repository) (Steps 1-3 using your forked version.)
- [ ] [Create RStudio project](https://gge-ucd.github.io/R-DAVIS/setting_up_git.html#3_Create_a_New_Version_Controlled_(git)_RStudio_Project) (Locate repository anywhere you want on your computer using "Create project as subdirectory of:")


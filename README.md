# Introduction to Programming in R

## Setup Instructions

### 1) Install R

If you'll be installing R on Windows or Mac OS X, visit [this website](https://mirror.its.sfu.ca/mirror/CRAN/).

#### Windows

- Follow the link for Windows on the page and click the link labeled "Install R for the first time."
- Download the file labeled "R-3.5.1.exe" (the specific version number may vary depending on when you visit the page).
- Double click on the downloaded file to begin installing.

#### Mac OS X

- Follow the link for Mac OS X on the page.
- Download the file labeled "R-3.5.1.pkg" (the specific version number may vary depending on when you visit the page).
- Double click the downloaded file to begin installing.

#### Debian / Ubuntu / Linux Mint

- Open terminal.
- Enter the following commands:

```bash
sudo apt-get update
sudo apt-get install r-base
```

#### RedHat / Fedora / CentOS

- Open terminal.
- Enter the following commands:

```bash
sudo yum update
sudo yum install -y R
```

### 2) Install RStudio

- Visit [this website](https://www.rstudio.com/products/rstudio/download/#download) and download the appropriate installer for your operating system.
- Installers are available for Windows 7/8/10, Mac OS X 10.6+, and several common Linux distributions.

### 3) Install Git

- Installing Git before the workshop will help keep us on track, however don't sweat it if you run into trouble during this step. We'll be spending a bit of time configuring Git to work with RStudio anyway. The most important thing here is to download the installation files beforehand to avoid having several users on the same network downloading at once.

#### Windows / Mac

- Visit [this website](https://git-scm.com/downloads) and download the appropriate installer for your operating system.
- Double-click the downloaded file to begin installing.

#### Linux

- Linux users should already have a working Git installation.
- This can be tested by running the following command in a terminal window:

```bash
git --version
```

- If you receive an error it is likely that you do not have Git installed. In this case, please follow the same instructions provided for Windows / Mac users.
- If problems persist, please see me at the beginning of the workshop and we will try to resolve the issue.

### 4) Setup a GitHub Account

- Visit [GitHub](www.github.com) and follow the registration instructions to set up a new account.
- Feel free to skip this step if you have an existing GitHub account.

### 4) Install a suitable text editor. (Optional)

- The text editors included with most operating systems tend to be powerful but hard to use. For this reason, I would strongly recommend installing a more modern text editor such as one of the options listed below. This is optional, however it will make working with text files considerably easier.

#### Windows

- [Notepad++](https://notepad-plus-plus.org/download/v7.5.8.html)

#### Windows / Mac OS X / Linux

- [Sublime Text](https://www.sublimetext.com/)

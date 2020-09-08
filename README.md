# THUIAR Official Website

![](https://img.shields.io/badge/Framework-Hugo-green?style=for-the-badge&logo=hugo)
![](https://img.shields.io/badge/Theme-Academic-blue?style=for-the-badge&logo=hugo)

This is the repo which contains all files that used to build the [THUIAR Offcicial Website](https://thuiar.github.io), which mainly based on Hugo Framework and Academic Theme.

**The website is made and maintained by [FanyangMengDev](https://github.com/FanyangMengDev).**

# Get Started

## Prerequisites

Before downloading your site, lets first install Hugo Extended and its prerequisites.

Choose your operating system below to get started.

### Windows

Install and open the Windows Powershell 5 app.

Install Scope, the package manager for Windows, by pasting the following commands into Powershell and pressing the Enter ↵ key:

```bash
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
iwr -useb get.scoop.sh | iex
```

Install Hugo and its dependencies:

```bash
scoop install git openssh go hugo-extended
setx GOPATH "%scoopApps%/go" /M
setx GOBIN "%GOPATH%/bin" /M
setx PATH "%PATH%;%GOBIN%" /M
```

### Mac

Open the Terminal app.

Install Homebrew, the Mac package manager, by pasting the following command and pressing the Enter ↵ key:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

Apply any Homebrew updates:

```bash
brew update && brew upgrade
```

Install Hugo and its dependencies:

```bash
brew install git golang hugo
```

Open the hidden `~/.zshrc` (or `~/.bashrc`) file in a text editor, add the following line, and restart your Terminal app so that Hugo can find the location of its Go dependency.

```bash
export PATH=$PATH:/usr/local/go/bin
```

### Linux

Using Snap:

```bash
sudo snap install --classic go
snap install hugo --channel=extended
```

Brilliant! Now you have already finished installing the requirements that the website need.

## Customize the Website

### Config

You can change the config of the website in the `./config/_default/` folder.

**config.toml** contains the main information of the site.

**languages.toml** allows you to change the translation of the site.

**params.toml** contains core parameters of the site.

**menus.toml** allows you to change the menu in the homapage.

### Content

After you finish setting the config, all you need to do is customize the `content` folder. It contains all files that display on our website.

Files within the `./content/zh/home/` are the main pages display on the homepage. You can choose whether to show them by changing the value `active` in every file.

### View it locally

You can run `hugo server` directly in the root dictionary. Then open your browser and input http://localhost:1313, now you can view the whole website locally.

### Generate deployment files

Just run `hugo --baseUrl="https://thuiar.github.io"`, then the `public` folder is the deployment folder that you need.






# THUIAR Official Website

![](https://img.shields.io/badge/Framework-Hugo-green?style=for-the-badge&logo=hugo)
![](https://img.shields.io/badge/Theme-Academic-blue?style=for-the-badge&logo=hugo)

This is the repo which contains all files that used to build the [**THUIAR Offcicial Website**](https://thuiar.github.io), which mainly based on Hugo Framework and Academic Theme.

**The website is made and maintained by [MFYDev](https://github.com/MFYDev).**

# Get Started

Before downloading the site, lets first install Hugo Extended and its prerequisites.

Choose your operating system below to get started.

## Windows

Download the latest version of **Powershell** from https://github.com/PowerShell/PowerShell/releases and install it.

Install Scope, the package manager for Windows, by pasting the following commands into Powershell and pressing the Enter ↵ key:

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
iwr -useb get.scoop.sh | iex
```

Install Hugo and its dependencies:

```powershell
scoop install git openssh go hugo-extended
```

## Mac

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

## Linux

Using Snap:

```bash
sudo snap install --classic go
snap install hugo --channel=extended
```

Brilliant! Now you have already finished installing the requirements that the website need.

# Customize the Website

## Config

You can change the config of the website in the `./config/_default/` folder.

**config.toml** contains the main information of the site.

**languages.toml** allows you to change the translation of the site.

**params.toml** contains core parameters of the site.

**menus.toml** allows you to change the menu in the homapage.

## Content

After you finish setting the config, all you need to do is customize the `content` folder. It contains all files that display on our website.

Files within the `./content/zh/home/` are the main pages display on the homepage. You can choose whether to show each widget by changing the value `active` in it.

## Create a publication

### Automatically

The leading reference management tools enable you to export your publications to the open BibTeX format. If you are new to research we recommend managing references with **Zotero**, a popular open source tool.

In your reference management tool, create a list of your own publications and export it as a `*.bib` BibTeX file.

Python 3 is a prerequisite, so please install **Python 3** if it’s not already installed. Also, you should backup your website before continuing, or ensure that it is checked into Git so that you can review the changes that will be proposed by Academic’s admin tool later on.

Open your Terminal or Command Prompt app and install Academic’s admin tool:

```bash
pip3 install -U academic
```

Use the cd command to navigate to your website folder in the terminal.

Then import your publications with:

```bash
academic import --bibtex <path_to_your/publications.bib>
```

The tool is in beta status and intended purely to help assist you, so the generated output in the `publication` folder should be reviewed prior to publishing your site. You can also consider enhancing the output by taking a look at the front matter parameters in the files alongside the details in the *Manually* section below.

### Manually

Alternatively, publications can be manually created using the command:

```bash
hugo new --kind publication publication/<my-publication>
```

where `<my-publication>` is the name of your publication, using hyphens (-) instead of spaces.

Then edit the parameters in `content/publication/<my-publication>/index.md` to include the details of your publication. The main parameters include:

- **title**: the title of your publication

- **date**: the date that your publication was first published (must be in a valid TOML date format)

- **publication_types**: use the following legend to specify the type of your publication, e.g. "1" for conference proceedings:

    - 0 = Uncategorized
    - 1 = Conference paper
    - 2 = Journal article
    - 3 = Preprint / Working Paper
    - 4 = Report
    - 5 = Book
    - 6 = Book section
    - 7 = Thesis 
    - 8 = Patent 

- **publication**: where your title was published - Markdown formatting is enabled here for italic etc.

- **abstract**: the summary of your publication

Further details on your publication can be written in the body of the document (after the YAML/TOML front matter) using Markdown for formatting. This text will be displayed on the publication’s page.

To enable visitors to read your work, either paste a link to your PDF in `url_pdf` or add a PDF file with the same name as your publication’s own folder to your publication’s folder and a PDF link will be automatically generated. For example, if your publication is located at `publication/photons/index.md`, place a PDF at `publication/photons/photons.pdf`.

To enable visitors to easily cite your work, export a BibTeX citation file named `cite.bib` from your reference management tool to your publication’s own folder and a citation link will be automatically generated.

## View it locally

You can run `hugo server` directly in the root dictionary. Then open your browser and input http://localhost:1313, now you can view the whole website locally.

## Generate deployment files

Just run `hugo --baseUrl="https://thuiar.github.io"`, then the `public` folder is the deployment folder that you need.






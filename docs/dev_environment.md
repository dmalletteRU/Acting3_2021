# Setting up your Development Environment

## Getting Started

The workflow has been based around using [Visual Studio Code](https://code.visualstudio.com/) as it has some useful plugins, is lightweight on system resources and integrates nicely with GitHub. There are also a few plugins that can help with writing HTML, CSS and Javascript. If you have a system that works better for you feel free to use it.

## Visual Studio Code

Please go to the [Visual Studio Code](https://code.visualstudio.com/) website and download the latest version for your operating system. Once it is installed open Visual Studio Code and download the following plugins. You can copy the ID in brackets and search with that to download the exact plugins.

* HTML Snippetes (abusaidm.html-snippets)
* Prettier (esbenp.prettier-vscode)
* Live Server (ritwickdey.liveserver)

These plugins will help with development of the website. HTML Snippets helps auto-complete HTML tags. Prettier helps colour and format code to make it easier to read. Live server lets you run a web server from Visual Basic Code to see your changes in a browser as you make them.

## Downloading the Content

### Windows

Download a program called Git for Windows [here](https://gitforwindows.org/). Git BASH is most important here as you can copy and paste the commands below and have everything working. Download and install Git for Windows, the installation defaults should be everything you need. There is an option to change the default branch name from master to main which I encourage.

Once that is ready create the folder that the website content will be located in and right click on empty space and select *Git Bash Here*. Next run the following command:

``` bash
git clone https://github.com/dmalletteRU/Acting3_2021.git
```

This command clones the repository into your folder and you should have all the files now. Do not modify anything just yet, we will need to get into branches and pull requests first.

### Mac

If you haven't already, install [Homebrew](https://brew.sh/) on your Mac which lets you easily install Git. Run the following command after insatlling Homebrew to install Git:

``` bash
brew install git
```

If you do not want to you can take a look at the [other installation options](https://git-scm.com/download/mac). Once that is done open a terminal window and create/navigate to the folder you wish to download the website content to. Example:

``` bash
cd /home/user/documents
mkdir acting3_website
cd acting3_website
```

Finally, run the clone command with the repository URL to download the content into your folder. Don't work on anything just yet until we cover branches and pull requests. 

``` bash
git clone https://github.com/dmalletteRU/Acting3_2021.git
```

## Setting up Git



## Beginning Work

First step to beginning work is to ensure that you are not working on something that is already being worked on as that can cause merging issues with the files. Example, if the index.htlm is being worked on but the style.css file is not, feel free to work on the style.css file and submit a pull request.

To start working, choose what you want to do and create a branch with one or two works to describe what you are working on. Make your additions and changes and then push to Github. Once you are done working on that branch submit a pull request and include if you want the branch to be deleted or not. The pull request will be reviewed and merged into the main branch.
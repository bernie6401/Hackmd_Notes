# Computer Reinstall Required Software
###### tags: `problem solution`

## Browser
* Mozilla Firefox（x64zh-TW）
* Google Chrome


## Other Software
* AdobeAcrobat(64-bit）
* MicrosoftOfficeLTSC事業增强版2021-zh-tw
* PDNob Image Translator 2.0.1.12
* File Shredder 2.5
* VLC media player
* WinRAR6.21(64-bit)
* Typora 1.5
* Spotify
* Webex
* Anydesk
* Key Freeze
* Photo Scan
* WinSCP


## Social
* Discord
* LINE


## CTF
* HxDHexEditor2.5
* Docker Desktop
* Burp Suite Professional
* VMware Workstation
* Virtual Box
* WireGuard
* wsl Ubuntu 20.04/22.04
* IDA Pro(From NTU Cool)
* Wireshark

### Ubuntu Tools
* zsh: `apt install zsh; chsh -s /bin/zsh`
* zplug:
    ```
    $ curl -sL --proto-redir -all,https https://raw.githubusercontent.com/zplug/installer/master/installer.zsh | zsh
    ```
* Anaconda:
    ```bash
    $ cd /tmp
    $ wget https://repo.anaconda.com/archive/Anaconda3-2023.03-1-Linux-x86_64.sh
    $ sh Anaconda3-2023.03-1-Linux-x86_64.sh
    $ conda create --name TAAD python=3.7
    $ conda create --name NTUCNS python=3.10
    $ conda create --name sideproject python=3.10
    ```
* nvm
    ```bash
    $ cd /tmp
    $ curl https://raw.githubusercontent.com/nvm-sh/nvm/master/install.sh | zsh
    $ nvm install node
    $ nvm install 18.16.0
    $ nvm use 18.16.0
    ```
* composer
    ```bash
    $ sudo apt-get update && sudo apt-get upgrade -y
    $ sudo apt install php
    $ php -r "copy('https://getcomposer.org/installer', '/tmp/composer-setup.php');"
    $ php -r "if (hash_file('SHA384', '/tmp/composer-setup.php') === '55ce33d7678c5a611085589f1f3ddf8b3c52d662cd01d4ba75c0ee0459970c2200a51f492d557530c71c15d8dba01eae') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('/tmp/composer-setup.php'); } echo PHP_EOL;"
    Installer verified
    $ sudo php /tmp/composer-setup.php --install-dir=/usr/local/bin --filename=composer
    $ composer -v
    ```


## TAAD
* Appium Server GUl 1.22.3-4
* Java(TMSEDevelopment Kit 17.0.7（64-bit）
* wkhtmltox0.12.6-1



## Coding Tool
* Microsoft Visual Studio Code (User）
* Anaconda32023.03-1（Python3.10.964-bit）
* Git
* Sublime Text 3
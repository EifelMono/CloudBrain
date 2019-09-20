
# PowerShell

## Get process with open port
* Get-Process -Id (Get-NetTCPConnection -LocalPort 6000).OwningProcess

## Stop process with port
* Stop-Process -Id (Get-Process -Id (Get-NetTCPConnection -LocalPort 6000).OwningProcess).Id


# Terminal

* [Developing on Windows with WSL2 (Subsystem for Linux), VS Code, Docker, and the Terminal](https://www.youtube.com/watch?v=A0eqZujVfYU&t=611s)
* [Customize the Windows Terminal with WSL2, Cascadia Code, Powerline, Nerd Fonts, Oh My Posh and more!](https://www.youtube.com/watch?v=oHhiMf_6exY)


# Tools

## Posh

* https://github.com/JanDeDobbeleer/oh-my-posh

## fonts

* [nerd fonts](https://www.nerdfonts.com/)

# New Window PC Setup

0. enable "show file extensions" and "show hidden files" in windows start menu
1. Set-ExecutionPolicy -ExecutionPolicy Unrestricted
2. Install vscode `https://visualstudio.microsoft.com/downloads/`
    - select "open with code" directory context on install menu
3. install wsl `https://learn.microsoft.com/en-us/windows/wsl/install`
    - use the `wsl_setup.sh` script after getting your linux dist installed
4. install vscode extensions with this command
    `Get-Content extensions.txt | ForEach-Object { code --install-extension $_ }`
5. `https://dbeaver.io/download/`
6. `https://www.rarlab.com/download.html`
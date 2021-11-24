## installation

1. download the script to local drive [link](https://chocolatey.org/install)

> Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))


2. restart the powershell

3. install required softwares
> choco install -y googlechrome
> choco install -y docker-desktop 
> choco install -y git
> choco install -y vscode
> choco install -y visualstudio2019professional
> choco install -y anaconda3
> choco install -y nodejs
> choco install -y 7z
> choco install azure-functions-core-tools-3 --params "'/x64'"

4. install vs code extensions
code --install-extension ms-python.python
code --install-extension ms-python.vscode-pylance
code --install-extension dbaeumer.vscode-eslint
code --install-extension ms-vscode-remote.remote-ssh
code --install-extension visualstudioexptteam.vscodeintellicode
code --install-extension esbenp.prettier-vscode
code --install-extension ms-azuretools.vscode-docker
code --install-extension eamodio.gitlens
code --install-extension donjayamanne.githistory
code --install-extension ms-dotnettools.csharp
code --install-extension ms-azuretools.vscode-azurefunctions



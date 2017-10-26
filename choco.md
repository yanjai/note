安裝 choco
=====
* 管理員身份打開 powershell
* 輸入
* Set-ExecutionPolicy RemoteSigned
* Set-ExecutionPolicy Bypass; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
* curl https://raw.githubusercontent.com/j16180339887/dotfile/master/Windows/profile.ps1 -o ~/Documents/WindowsPowerShell/profile.ps1
* 設定 powershell 背景為黑色
* 關閉 powershell
* 重新啟動 powershell

安裝套件
=====
* choco install aria2 ffmpeg youtube-dl -y
* choco install directx vcredist2005 vcredist2008 vcredist2010 vcredist2012 vcredist2013 vcredist2015 vcredist2017 vcredist-all -y

升級所有套件
=====
* choco upgrade all

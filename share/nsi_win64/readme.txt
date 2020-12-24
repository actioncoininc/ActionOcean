Requirements:

- run command "sudo apt-get install nsis" to install nsis for installer creation

- Download internet client plug-in for files download and upload (http://nsis.sourceforge.net/Inetc_plug-in)
  copy Inetc/Plugins/x86-unicode/INetC.dll from downloaded file package into /usr/share/nsis/Plugins/x86-unicode

- Place komodo-qt.exe in content\komodo-qt.exe and rename to action-qt-win.exe

- Run command "makensis ./share/nsi_win64/install.nsi" from root directory


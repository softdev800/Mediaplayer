# Mediaplayer
Приложения "Медиаплеер"

Initial setup:

```
pip3 install -r requirements.txt
pyrcc5 resources.qrc -o resources_rc.py
pyuic5 mainwindow.ui -o MainWindow.py

pip3 install PyInstaller
pip3 install PyQt5 PyInstaller
pyinstaller --windowed --icon=images/music-icon-128.ico --name Mediaplayer mediaplayer.py

pyinstaller mediaplayer.py
pyinstaller Mediaplayer.spec
```

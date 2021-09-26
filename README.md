### 1) Start the software ###
from pywinauto.application import Application

#Start the application
app = Application(backend='uia').start('notepad.exe')


### 2) What is the window?  ###
window = app['Untitled - Notepad']


### 2) Get all controlers in window  ###
window.print_control_identifiers()

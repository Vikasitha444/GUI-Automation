### Start the software ###
from pywinauto.application import Application

#Start the application
app = Application(backend='uia').start('notepad.exe')

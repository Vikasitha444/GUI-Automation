### 1) Start the software ###
from pywinauto.application import Application
app = Application(backend='uia').start('notepad.exe')


### 2) What is the window?  ###
window = app['Untitled - Notepad']


### 3) Get all controlers in window  ###
window.print_control_identifiers()


### 4) Select a button and click ###
window.<button info>.wrapper_object().click_input() 
  
  

### 5) Repeat Step 3 and 4 as much as you want ###

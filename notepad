from pywinauto.application import Application

#Start the application
app = Application(backend='uia').start('notepad.exe')


#What is the window?
window = app['Untitled - Notepad']


#Get all controlers in window
window.print_control_identifiers()


#Select a button and click
window.child_window(title="File", control_type="MenuItem").wrapper_object().click_input()

# patterns
Patterns
It is a music player by using python in tkinter ibrary.
Tkinter 
Tkinter is a GUI library in Python that is a fast and easy way to create GUI applications.

Initialization
To open Tkinter, follow the following steps:

Import Tkinter module
Initialize an object to it and add required widgets
Add object name.mainloop()
The following steps are shown in the code below:

12345
from tkinter import *

obj = Tk()

obj.mainloop()
Buttons
The Button object is used to display the button on your application:

12
new_button = Button(text= "button", command ="")
new_button.pack()
Entry
The Entry object is used to display a single input text field line:

12
text_field = Entry()
text_field.pack()
Label
The Label object is used to display a single text field line:

12
main_title = Label(text = "Hello")
main_title.pack()
Geometry management
All the widget has to use is a specific geometry method and it is divided into three types. These types are:

Pack: organizes the widgets before placing them in the parent widget.
1234567891011
new_button = Button(text= "button", command ="")
new_button.pack(side = BOTTOM)


text_field = Entry()
text_field.pack(side = LEFT)


main_title = Label(text = "Hello")
main_title.pack(side= RIGHT)

Place: you can provide an absolute position for where to place the widget.
12
new_button = Button(text= "button", command ="")
new_button.place(height = 100, width = 100)
Grid: displays widgets in Table format.
12345678910


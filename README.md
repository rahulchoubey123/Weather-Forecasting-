# Weather-Forecasting-
#LIST OF CONCEPT COVRED:
#Dictionary:- 
•	Dictionary stores the data in key value format.
•	Dictionaries are initialized under curly brackets {}
•	In dictionary keys and values are separated by colon (: )
•	Dictionary is ordered and unchangeable
•	In dictionary duplicate elements are not allowed.
•	Keys in dictionary are just of immutable data type like string, int, etc.
•	Values in dictionary can be of any data type.
•	We can access the elements in dictionary using keys.
In our code we have accessed the elements of dictionary like value of minimum temperature, maximum temperature, pressure, humidity, etc. using there keys.


#Json Module:-
•	JSON means Java Script Object Notation
It means that a script file which is made up of text in a programming language is used to store and transfer the data.
JSON represents objects as name/value pairs just like a python dictionary.
JSON is a built-in-module called .json
•	Serialization in JSON means the conversion of python objects into their respective JSON objects.
•	 Deserialization in JSON means the conversion of JSON objects into their respective Python Objects.

1.	json.load (): json.load () use to convert JSON data to python dictionary.
    Syntax: json.load (file object)
2.	json.loads (): json.loads () use to convert JSON string to python object.
Using file object.read () with json.loads ()
We can return the content of the file.
Syntax: json.loads (jsonstring) #For Json string
json.loads (file object.read ()) # for file object
•	In our project, we use response.json () to convert JSON data in to python dictionary.



#Request Module:-
•	The requests module allows you to send HTTP requests using Python.
•	The HTTP request returns a Response Object with all the response data (content, encoding, status, etc.).
•	Python requests module has several built-in methods to make Http requests to specified URL using GET, POST, PUT, PATCH or HEAD requests.
•	An Http request is meant to either retrieve data from a specified URL or to push data to a server. 
•	It works as a request-response protocol between a client and a server.
•	Http Request Methods –
•	GET- GET method is used to retrieve information from the given server using a given URL.
•	POST - POST request method requests that a web server accepts the data enclosed in the body of the request message, most likely for storing it
•	PUT - The PUT method requests that the enclosed entity be stored under the supplied URL. If the URL refers to an already existing resource, it is modified and if the URL does not point to an existing resource, then the server can create the resource with that URL.
•	DELETE  - DELETE method deletes the specified resource
•	HEAD - The HEAD method asks for a response identical to that of a GET request, but without the response body.
•	PATCH - It is used for modify capabilities. The PATCH request only needs to contain the changes to the resource, not the complete resource

In our program we have used get function to get the data from Openweathermap site using API and URL.
3) Tkinter Module:-
•	Tkinter is the standard GUI library for Python. Python when combined with Tkinter provides a fast and easy way to create GUI applications. Tkinter provides a powerful object-oriented interface to the Tk GUI toolkit. 
•	It has various function and commands which are used to create GUI window, button, Lable, Entry box or to display images and messages in GUI window.

It has following functions:-
	Tk () is used to create GUI window.
	title() is used to give title to the GUI window. Its parameter is title name.
	iconbitmap () function is used to insert icon in front of title of GUI window. Its parameter is extension of icon image.
	Photoimage() function is used to insert images in GUI window. Its parameter is file, file holds the complete path of image file.
	Label () function is used to create label in GUI window.
It takes two parameters:-
1) Master: - Variable in which GUI window is stored.
2) Options: -
 It has following options:
•	bg: This option is used to set the normal background colour displayed behind the label.
•	height: This option is used to set the vertical dimension of the label.
•	width: Width of the label in characters (not pixels!). If this option is not set, the label will be sized to fit its contents.
•	font: If you are displaying text in the label (with the text or textvariable option), the font option is used to specify in what font that text in the label will be displayed.
•	cursor: It is used to specify what cursor to show when the mouse is moved over the label. The default is to use the standard cursor.
•	textvariable: As the name suggests it is associated with a Tkinter variable (usually a StringVar) with the label. If the variable is changed, the label text is updated.
•	bitmap: It is used to set the bitmap to the graphical object specified so that, the label can represent the graphics instead of text.
•	fg: The label colour, used for text and bitmap labels. The default is system specific. If you are displaying a bitmap, this is the colour that will appear at the position of the 1-bits in the bitmap.
•	image: This option is used to display a static image in the label widget.

	Entry () function is used to create Text box to input multiple lines.
It has two parameters:-
     1) Master: - Variable in which GUI window is stored.
     2) Options: -
     It has following options:
•	bg: The normal background colour displayed behind the indicator. 
•	bd : The size of the border around the indicator. Default is 2 pixels. 
•	font : The font used for the text. 
•	fg: The colour used to render the text. 
•	justify : If the text contains multiple lines, this option controls how the text is justified: CENTER, LEFT, or RIGHT. 
•	relief : With the default value, relief=FLAT. You may set this option to any of the other styles like : SUNKEN, RIGID, RAISED, GROOVE 
•	show : Normally, the characters that the user types appear in the entry. To make a .password. entry that echoes each character as an asterisk, set show=”*”. 
•	textvariable: In order to be able to retrieve the current text from your entry widget, you must set this option to an instance of the StringVar class.

	Button () function is used to create the button in GUI window.
	It has two parameters:-
                1) Master: - Variable in which GUI window is stored.
                2) Options: -
                 It has following options:
•	text= It is used to display text on button.
•	Image= It is used to display image on the button.
•	height=It is used to change the height of button.
•	width=It is used to change the width of button.
•	bg=It is used to apply background color to button.
•	fg=It is used to apply color to text on button.
•	Command=It is used to run specified function after pressing the button. 

	Configure () function is used to access an object's attributes after its initialization.  

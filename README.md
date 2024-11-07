# Convert-image-to-pdf-using-Python-GUI

# Introduction :
The code given is a simple Graphical User Interface (GUI) application created using the Tkinter library in Python. The application for helping any user convert multiple images into a single Portable Document Format (PDF) file. The user does the selection of images they want to convert and provides the name and location of the resulting PDF file to the interpreter. The application uses the Python Imaging Library (PIL) to handle the conversion process.

# Explanation :
The application consists of three main buttons, namely: Select Images, Select PDF and Convert. The Select Images button opens a file dialog allowing the user to select multiple image files they want to convert to PDF.

The Select PDF button opens a second file dialog box that allows the user to enter a name and choose the location for the resulting PDF file they will get after conversion.

Finally, the Convert button invokes the conversion process and displays a success or an error message depending on the outcome of the program.

In crux, the code provides a simple and intuitive way for its users to convert multiple images into a single PDF File, without the help of manual conversions or external tools.

The code given above uses the Python Tkinter library. It is a GUI (Graphical User Interface) – based program written in Python for the purpose of converting multiple images to a single PDF document.

As you can see, the program has three buttons with:

# 1. Select Images: This button helps to open a dialog box that allows us to select one or more image files of extensions such as JPG, JPEG and PNG to be converted to PDF.

# 2. Select PDF: This button will open a save file dialog that will allow the user(you) to select the name and location of the PDF file the user(you) wants to create.

# 3. Convert: This will call the “images_to_pdf” function, which takes the selected images and name of the PDF file as inputs and converts the images to a single PDF document.

The “images_to_pdf” function uses the PIL library. It first opens the first image to create a new PDF file with that image. It then appends the remaining images to the PDF file. The function is also invoked to display a success popup or an error message, in case of a conversion failure.

Once the GUI is run, the user can interact with the buttons to select the images and PDF file, and then convert the images to a single PDF document.

Coming to the rest of the program:

1. The code starts with a tkinter package which is very important package in Python. “tkinter” is the main module in Python to create GUI applications.

2. ‘fileddialog’: This provides a file selection dialog box whenever invoked to allow users for selecting images and specifying the PDF file name and path.

3. ‘messagebox’: Provides a feedback message box to display success and error messages to the user.

4. ‘PIL’: This is an image processing library used to open and save image files.

# Functions Used in Above Program:
1. ‘images_to_pdf‘: This function takes a list of images and the name of a PDF file as inputs. creates a new PDF file with the info given, and appends the images to it. If the conversion process is successful, it shows successful feedback/message to the user, otherwise, it shows an error.

2. ‘select_images‘: This function opens a file selection dialog allowing users to select one or more than one image file.

3. ‘select_pdf’: The function will help open a dialog box allowing users to specify the name and path of the PDF file for its creation.

Finally, the mainloop() function is a common Python function invoked and used in Python’s GUI-based programs where the function creates a GUI event loop and keeps the window open until the user chooses to close it.
# Output:
![image](https://github.com/user-attachments/assets/0da98c81-e7dd-4339-9559-a4b0a7b9b2f8

Following changes were made to the existing notepad file:

1)A file named 'Untitled_copy.txt' is opened in write mode if it doesn't exist else opened in read mode

#def update_line_number()
2)On <Any-KeyPress> the contents of these files are copied to 'Untitled_copy.txt'

# def new_file()
3)The function new_file() truncates the previous text and opens file 'Untitled_copy.txt' in write mode and copies the content in it.

#def open_file()
4)In function open_file() if we open an existing file and do some changes in it and close it before saving even then the changes are retrieved in the file when we run the 'Final_Notepad.py' the next time.
This is done as 'filename'+'copy.txt' file is made and contents are copied from it when we again run the program
	
5)The changes made to a file are retrieved even if it is not saved and by default the root name will be 'Untitled-Tkeditor'

6)When file 'Untitled_copy.txt' is opened in read mode it inserts data on the text area
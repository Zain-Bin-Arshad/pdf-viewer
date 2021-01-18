# PDF-Viewer
A **Pure Python PDFViewer**, which provides almost all functionalities you want from a PDF reader. Following are the some of main features of this application

- Searching through PDF document
- Table of contents
- Take notes and save them automatically
- Night mode for taking care of your eyes
- Zooming feature
- Developed in pure python (python-3.7.4)

## Why bother creating new PDF Viewer?
I wanted to create an application that requires me to have a PDF Viewer with access to the source code, in python. I searched the internet for a PDF Viewer written in Python, but all in vain. I couldn't find any reasonable result.
Hence, I decided to create my own PDF Viewer, that uses pure python packages.

## How to run?
Make sure you have installed these packages:

- PySimpleGUI
- PyMuPDF
- fitz

You can simple run this command to install all packages. First make sure you are in same directory as *requirements.txt*, then type:

`pip install -r requirements.txt`

This will install all the packages, then you have to simple run this command:

`python pdfviewer.py`

Given command will generate this screen:
![1](https://user-images.githubusercontent.com/49767636/101292187-c08cbf80-382f-11eb-9f8b-65e32dab0a48.jpg)

Now, you can open any book and enjoy reading.
![5xVcJDdb75](https://user-images.githubusercontent.com/49767636/101292582-3abe4380-3832-11eb-86e5-0f85c80c4c72.gif)

## Searching
We all just want to search through a document and get things done quickly, well I got your back. Keep searching using this advanced user-friendly search feature.
<p align="center">
  <img src="https://user-images.githubusercontent.com/49767636/101292458-5ffe8200-3831-11eb-8873-71056c39d2e0.gif" alt="animated" width="1500" height="490"/>
</p>

## Night Mode
You want to read more but your eyes can't see the white screen anymore, switch to night mode. This not only updates the application's theme,  but converts the PDF to black background and white text so that your eyes can relax.
![night](https://user-images.githubusercontent.com/49767636/101292512-b966b100-3831-11eb-8ed5-8ab291b6b645.jpg)

## Notes
Well you can take notes as you go through the book. On the right side there a space for writing anything you want. There is a "Check Box" at the right hand corner make sure that box is checked, only then the note will be saved.

A file name like this "%PDF Filename%_notes.txt" will appear once you close the document. This file will look something like this:
<p align="center">
  <img src="https://user-images.githubusercontent.com/49767636/101292682-e10a4900-3832-11eb-9b54-c63708c7c1d6.jpg" alt="animated" />
</p>

You can see how easy it is to navigate through this text file and see all the notes.

### What's so special about it?
Once you have taken the notes, then, whenever you open the same file again, all the notes will appear again with respective to there page number. If you take example of above given screenshot of the notes.txt, when I open the same file again you can see the notes:
<p align="center">
  <img src="https://user-images.githubusercontent.com/49767636/101292715-0d25ca00-3833-11eb-815c-1d4f73cd271f.jpg" alt="animated" />
</p>

Make sure you don't delete the text file that is created automatically by the PDFViewer.

## Buy me a coffee
If you like my effort and want this project to move forward, you can support this project by using the `Sponser` button above. Every generous help is much appreciated.

## Pythonic Code
This code is not as much pythonic as I want it to be, but I had just enough time and resources to get this done, so this is what it is. I might take 1-2 days out of my schedule to refactor this code base so anyone using this code don't want to kill me, hahaa.

## Special Thanks
I want to thanks [PySimpleGUI](https://github.com/PySimpleGUI/PySimpleGUI) for developing such a great GUI-Framework in python.

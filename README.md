# Web-browser-made-using-pyqt5
Who does not use a browser these days? Everyone does. Creating a browser with a lot of utility is a bit time taking and difficult in the real world, but what if today in this article we will Create Your Own Web Browser Using Python.
******************************************************************************************************************************
So today in this article, we are going to create a web browser that is simple and usable. We will make a browser that will have some of the common features like the forward and backward button, home button, etc.
--------------------------------------------------------------------------------------------------------------------------------------------
Before starting with the coding of Web Browser Using Python, let us clear the difference between the two widely used words Browser and Search Engine.
Browser: A web browser is an application that allows you to access information on the Internet. Web browser helps to assist users in having an interactive online session on the World Wide Web/Internet. Example: Chrome, Firefox, etc.

Search Engine: It is a program that is used to locate specific websites on the Internet. It basically aids the user in obtaining knowledge about anything available on the internet.
Example: Google, Bing, etc.
*********************************************************************************************************************
Browser Features:
Home Button: This button must-have capability to take the user directly to the home page.
Forward Button: This button will take the user to the next site.
Back Button: This button will take the user to previously visited websites.
Refresh Button: It will have the capability to refresh the content of the site.

Steps for Developing Web Browser Using Python:
Step 1: Installing the required libraries.
PyQt5 and PyQtWebEngine
*********************************************************************************************************************
Step 2: Import the modules that are needed for the development of this project.
sys module, modules from PyQt5 like QtCore, QtWidgets, QtWebEngineWidgets

Step 3: Functions definition and creation of classes.
*********************************************************************************************************************************
Step 4: Coding for buttons and their functionalities.
**********************************************************************************************************************************
Getting Started:
Step 1: About Libraries & Its Installtion:
PyQTt5: PyQt5 is one of the most popular Python modules for creating graphical user interfaces as it is very easy to use for beginners. The PyQt5 designer makes it so easy to construct complex GUI programs in a short amount of time, and it is also another wonderful feature that motivates developers to choose PyQt5.

PyQtWebEngine: The framework is built on the Chrome browser and allows users to embed online content in their apps. The bindings are built on top of PyQt5 and are divided into three modules that match the framework’s various libraries.

Now, let us see how to install these libraries.
*******************************************************************************************************************************
PyQt5
PyQtWebEngine
To install the PyQt5 library, enter the following command in the cmd:
******************************************************************************************************************************
pip install PyQt5
To install the PyQtWebEngine library, enter the following command in the cmd:

pip install PyQtWebEngine
Step 2: Importing required modules:
import sys
from PyQt5.QtCore import *
from PyQt5.QtWidgets import *
from PyQt5.QtWebEngineWidgets import *
Explanation:
import sys: So, this command will import the sys module. The sys module contains methods and variables for modifying many aspects of the Python runtime environment. The python interpreter provides access to a number of variables, constants, functions, and methods.
import os: This module is imported in order to perform operations on directories, edit its contents etc.
QtCore: The sys module contains methods and variables for modifying many aspects of the Python runtime environment. The python interpreter provides access to a number of variables, constants, functions, and methods.
Qtwidgets: Qtwidgets are used to generate the user interface in Qt. and it also includes classes for constructing traditional desktop-style user interfaces but these widgets are more useful when developing large-scale applications.
QtWebEngineWidgets: The QtWebEngineWidgets package contains both a web browser engine and C++ classes for rendering and interacting with web content. The web content is embedded in the application using this framework.

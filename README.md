Tutorial on Yarpmanager
=======================================

This tutorial will quickly guide you to use `yarpmanager` to run Yarp applications 

You will learn how to  
- Use [yarpmanager](http://www.yarp.it/yarpmanager.html)
- Run multiple instance of a module
- Add connections 
- Run module with dependency and other constraint 
- Find the applications 
- etc 


# Tutorial
In this tutorial we build an application to run the YARP `test_grabber` and `yarpview`. We will see how we can use `yarpmanager` to run the modules and establish their connections. Moreover we will learn how to write a Yarp application description (XML) file. 


# Running the tutorial application
- Simply switch to the tutorial folder and run the `yarpmanager`. Then open/run the `Tutorial_Yarpmanager` application for the GUI then connect the ports: 
```
$ cd tutorial_yarpmanager
$ yarpmanager
```
![application](/misc/application.png)

# Modify the application

To modify the application you can edit the file `applications/tutorial_yarpmanager.xml`. Open and edit as you like the xml with a text editor. For example you can add another instance of `test_grabber` and `yarpview`. Try to modify the command line parameters of `test_grabber` for example to display a ball (`--mode ball`) instead of a line (`--mode line`).




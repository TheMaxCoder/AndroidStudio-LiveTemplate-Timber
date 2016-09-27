#Live template for [Timber](https://github.com/JakeWharton/timber)
A live template that for timber (A a logger with a small, extensible API which provides utility on top of Android's normal Log class) to make the logging a breeze.

# How to
There are two different files included

###TimberLogWithMethodName.xml
This will log the messge with the method name by default.

###TimberLog.xml
This will log the message normally as timber usually does.

To include the file in Android Studio download and copy the file and paste in the following directory depending on your operating system

`Windows`: <your_user_home_directory>..AndroidStudio<version_number>\config\templates

`Linux`: ~.AndroidStudio<version>\config\templates

`OS X`: ~/Library/Preferences/.AndroidStudio<version>/templates

and then restart the Android Studio. You can check if the template is included by going to  Settings> Editer> Live Templates
You should see a file named `TimberLog` there. if so you are good to go otherwise try repeating restarting the IDE and repeating the above steps.
You can find more information about including [here](https://www.jetbrains.com/help/idea/2016.2/live-templates.html)

#Usage

`timd`: Log debug message

`time` : Log error message

`timi` : Log information message

`timm` : Log method name and arguments

`timr` : Log result of this method

`timt` : logtag for next logging call.

`timv` : Log a verbose message

`timw` : Log a warning message



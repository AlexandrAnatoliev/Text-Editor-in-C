# ADitor is a simple text editor. 


## About
I love to create it in different languages. Already created in C# .net and Python. Both are available in my github. Now this time in C language. I guess its most powerful among all three flavours. GTK version 3 is used for GUI. 


## Installing the GTK-3 library
The first step is to search the **apt-get cache** to find the current version of GTK3 to install. You can search for available **apt-get** packages by the command:

`apt-cache search libgtk-3`

To make changes in the program code, you will need to download the development version GTK-3. At the moment, it looks like this: **libgtk-3-dev**. The package is installed by using the command:

`sudo apt-get install libgtk-3-dev`


## Compilng code and linking with the GTK-3 library
We compile the file by the command:

`gcc Aditor.c -o aditor \`pkg-config --cflags --libs gtk+-3.0\``

We get the **aditor** executable file and run it by the command:

`./aditor`

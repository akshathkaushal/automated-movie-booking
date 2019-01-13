# Bookmyshow Bot
This is a simple BookMyShow Bot developed in python using Selenium. 
Selenium is used mainly for automating web applications for testing purposes, but is certainly not limited to just that. Boring web-based administration tasks can (and should!) be automated as well.

This code is developed for chrome browser by installing its driver. Using it you can book the first show of your favourite movie in your favourite movie theatre. And not only this, you can also book your favourite snack among the listed ones if you want. 

Just follow the following steps after running the code:-
1) Type in your region.
2) Type the name of your favourite movie,play,play,sport etc.
3) Type in the date which suits you (for eg. 17).
4) Type the name of your favourite mall (for eg. pvr).
5) It will give you the first show of that day.
6) Then type the number of seats you want to book. (in the range 1 to 10).
7) It will automatically book the seats for you.
8) If you want, you can book a snack for you during the movie (type in y/n).
9) You can also selct the option where you can collect your ticket, either online or directly from box office. (type in m/b)
10) This code is generous :) , it automatically gives Rs.2 for charity. 
11) It also asks for your email id and phone number and fills it, taking you straight towards the payment.

Installation links:

1) Python installation link: 
   
   For linux:
      https://www.python.org/ftp/python/3.7.2/Python-3.7.2.tar.xz
   
   For windows:
      https://www.python.org/ftp/python/3.7.2/python-3.7.2-webinstall.exe

2) pip installation:

   For linux:
      In terminal, type the following commands,
      * sudo apt update
      * sudo apt install python3-pip
   
   For windows:
      Download get-pip.py to a folder on your computer.
      Open a command prompt and navigate to the folder containing get-pip.py.
      Run the following command:
      python get-pip.py

3) Installing selenium:

   For linux:
      In the terminal, type the following command,
      sudo pip install selenium
   
   For windows:
      In the command prompt, type the following command,
      pip install selenium

4) Installing chrome driver:

   https://sites.google.com/a/chromium.org/chromedriver/
   
   Make sure that you extract the driver in the downloads folder in your home. Or else, you can extract the driver in some 
   other folder and copy the address of the exe file and replace the address in the line 67 of the code with it.

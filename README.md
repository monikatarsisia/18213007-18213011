II3160 Integrative Programming - Socket Programming
A repository for all Integrative Programming Assignments of Monika Tarsisia Nangoi [18213007] and Rana Nugramahesa [18213011]

# Assignment 1 - 2015/09/08
Build a server application and a client application
File :
1) server.java
2) client.java
Scenario :
-. Server opens the connection with determined port number
-. Client connects to server
-. Client sends any message to server
-. Server receives the message

# Assignment 2 - 2015/09/15
Build a server application that can send a file to client and a client application that can request a file from server based on list.
File :
1) FileServer.py
2) FileClient.py
3) a.txt
Scenario :
-. Server open connection
-. Client connect to server
-. Server send list of file ([1] a.txt [2] b.txt [3] c.txt)
-. Client request one of file on the list (1/2/3)
-. Server sent file based on request
-. Client receives the file and save it 

# Assignment 3 - 2015/09/29
Build a program that request a web page from web server, download the page, then parse/extract all hyperlinks that exist. Download all pages on those hyperlinks. The web page will be saved as dataOri.html. The list of hyperlinks will be saved as hyperlinks.html. And the web page for each hyperlinks will be saved as data1.html, data2.html, data3.html, etc.
File :
1) Parsing.py
2) BeautifulSoup.py

# Assignment 4 (Mid Term) - 2015/10/23
A program that downloads all .jpg images from a webpage. Every image that is downloaded will automatically be backed up in another directory locally using rsync.
File :
  img_downloader.sh
Scenario :
-. Open the webpage
-. Find all links with a .jpg format
-. Download all the images
-. Save the images to the current folder
-. Sync the downloaded image to a folder named ‘back up’ and delete the source file
-. While syncing, filter the files. Moved all the images (files with .jpg format) and    exclude the files with .sh format

#Assignment 5 - 2015/11/03
A SOAP (Simple Object Access Protocol) client and server application. Server application provide function that return string, return addition of two integer, and return data from database. Client application connect to server application and access each function in server application.
File :
  SOAP_Client.php
  SOAP_Server.php
Scenario :
-. Prepare/run web server (Apache)
-. Make sure the source code is in the right directory
-. Run the web program to see if it’s working (SOAP_Client)
-. Create a database using PHP MyAdmin
-. Connect the database to the server
-. Run the web program (SOAP_Client)

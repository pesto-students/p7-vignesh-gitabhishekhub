# Week 1 Assignment 1


So, When I enter the url in the browser what happens,also how browser fetch the desired result

 A.  So, Basically when I type the url into any browser what I want is that i want to reach the server where the website is hosted.

So, now what the browser does is that it will look for the IP address of the domain name in DNS ,Domain Name server.

so here we can also access the website by typing the ip address but it is difficult to remember the nubers of the IP address so what we do is we will remember the name of the website with IP addressby the DNS.

**Now what does DNS do?**

DNS will checks  the cache part to run DNS query. Now It check with four cache type:
BRowser Cache,OS cache ,Router CAche ,ISP cache.
So, when start with browser cache if it does not contain cache then it will go for OS cache similarly in this manner if one not works it will go for another cache check.And if at the end ISP not work then it will go for DNS Recursive search and then initiate DNS query and commnicate with DNS server to find the IP address.


B..
![Screenshot (744)](https://user-images.githubusercontent.com/117532446/202266630-06fe71fb-286a-4fca-a049-c55b671b585f.png)

Now what does browser do is that it will intiate the connection with server ,how

So, Now what the browser know is that it receives the IP address and now it will establish the connection between browser and server with the INternet protocol and most commonly used protocol is TCP and it follows 3 steps Syn ,SYN +ACK and lastly  ack

So basically SYN is synchronised SEquence Number so in this as the client wants to start the communication it sends SYN.

SYN +ACK :so basically in this server ready to accept the connnection and acknoledge by sending the Syn+ack packet to the server.

ACk :in this client acknowledge the response of server by sending  ack packet request.

Now after all this things data transmission started.

C..

Now browser send the HTTp request to the server.
Basically browser will send the GET request to the server asking for the webpage .Also sends the cookies which has various information like record the user browser history.


D..

Now Server handles the request which is coming and give the response
So what happens now that server will handles the request and sending the http response with the status line consist of PROTOCOL VERsion ,status code followed by text .

So there are different meaning of status code.
but if the status code 2XX then the action was sucessfull and when it is 3XX some action has to be taken ,and when it 4XX then it is client side error and when it is 5XX it means server side error.

 
 

 
![Screenshot (744)](https://user-images.githubusercontent.com/117532446/202266721-d08d4c58-64bd-4f90-ac62-86d343d9c9b7.png)



E..

Now the browser will displaying the html content

Now after getting the response from server browser will display the Html content in phases and sends the multiple GEt request to get the Html structure ,links images and javascript folders ,and after all these steps which happens in millisecond the webpage will be displayed.


**Assignment 1.a**

So, the main functionality of the web browser is that it fetch the informative information from webpage.

Display those content like image text video to the user whichever the thing is in webpage to display.Also interacting with the webpage and the dynamic content.




**Assignment1.b**
The component of web browser are :
A.User Interface
B.Browser Engine
C.Rendering Engine
D.Networking
e.JavaScript Interpreter
f.UI Backend
g.Data Storage
 
![Screenshot (745)](https://user-images.githubusercontent.com/117532446/202266821-ad48852f-61eb-4999-91a0-53f44c3719fd.png)


**Assignment 1.c**

Rendering engine is usefull for displaying the content in the browser screen.Also translate the html ,xml files images all these formatted by CSS.
Also display the different type of content using different type of plugins nd extension.Some plugins by different type of browsers are:Trident,Blink,Webkit.

**Assignment 1.d**
It means analyze and convert a program into an internal format that a runtime environment can actually run and execute that, for example the JavaScript engine inside browsers. The browser parses HTML into a DOM tree. 

Also HTML parser involve and responsible for tree Construction.

**Assignment 1.e**
Processors can provide customizable URL that can execute javascript code and we have to advise that not create custom processors.
SCRIPT PRocessors
It will immidiatley invoke the function expression when the system call this script processors.

This function provide input parameter for some Api objects:g_request ,g_response and g _processor.



**Assignment 1.f**

HTMl is a tree that has open and close tag pair for each span of text. So,for the browser to be a tree there has tokens which evolve into nodes.
After the browser has created the nodes from HTML document it has created a tree like structure of these node objects. Also our HTML elements nested inside each other so the browser 
needs to replicate that but it has use node objects created previously.

![Screenshot (751)](https://user-images.githubusercontent.com/117532446/202272239-57d4ba3f-566f-48df-8097-86b018e01a6b.png)



**Assignment 1.g**

Script is used for specifying javascript which should be run in webpage and also script can include in the javascript to directly or it can point to a url.

So,if the script is not in order had the undesirable performance behaviour of loading and executing.
Script Order:
Load first order:Their document order does not matter which loads runs first.
Document order DOM:Executed after the document is loaded and then parsed.

**Assignment 1.h**
So, in layout part basically the browser captures the tree construction size and painting in the timeline and also after this process it goes to the paint part.

So,when the layout is complete the browser then issues paint setup and paint events which then convert the tree to pixels on the screen.
Also the time required to perform the tree costruction layout and paint varies from the size of document and device on which the document is running ,the more work the browser has the more complication in styles and more time in paint work also.




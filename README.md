#Boilerplate Index File Information 

#February 20, 2019

#David Salazar

1 . *< !doctype html >*: A doctype declaration which tells the browser that the document is using HTML.

2 . *< html class="no-js" lang="" >* : The "no-js" class gets removed by a Javascript library (Modernizr), 
   and this gets replaced with a js class. When Modernizr loads, it replaces no-js with js.
      
   This is a way to style with OR without Javascript.
   
   In other words, CSS styles can be defined for JavaScript-enabled browsers and for browsers that 
   have JavaScript disabled. lang="" sets the language of the web page.

3 . *< head >*: HTML tag also known as an element that is the container for all head elements. can have
   document title, styles, and other inforrmation. information about the web page itself. 
   
   < element > = opening tag
   
   < /element > = closing tag 

4 . *< meta charset="utf-8" >* : Universal text format 8 for all languages (except Asian languages) that 
   read left to right.

5 . < title> </ title > : The title of the webpage goes in between <title></title>. 
   ex: < title >Web Page Title</ title>
   
6 . < meta name="description" content="" > : Meta stands for metadata or information about specific data.
   <meta> gives metadata of a HTML document. Metadata does not get displayed on a page, but it will 
   instead be machine parsable
   
   Meta tags/elements are used to specify things like page description, a document's author, keywords,
   last modified (as well as other metadata), how to display/reload the content of a page, and search 
   engine keywords   
   
   Users can set the viewpoint of a website 
   
7 . < meta name="viewport" content="width=device-width, initial-scale=1" > : This is used by the browser to 
   render a web page the size of a device's screen used to view it  
   width = width of virtual viewport of device
   device-width = physical width of device's screen 
   initial-scale = 1 is the initial zoom. 1 is normal (without zooming in) 
   
8 . < link rel="manifest" href="site.webmanifest" > : information about the application (name, author, icon,
   description, and how the application should behave once installed in a device) in a JSON text file. 
   informs details for websites installed on the homescreen of a device. web app manifests are websites that 
   can be installed to a device's homescreen without an app store, the capability to work offlien, and receive
   push notifications 
    
   linking a web manifest to a web page

9 . < link rel="apple-touch-icon" href="icon.png" > : provides back up name and an icon for the web page.
   it is the image that one can see if if the website is added to the home screen of a device 
   
10 .   < link rel="stylesheet" href="css/normalize.css" > : the rel attribue speciefies the relationship btween the
      html file with the normalize.css file that are being linked. b/c normalize.css is a stylesheet, I have to specify 
      rel = 'stylesheet' the href attribute specifies the location of the file named normalize.css file. in this case, 
      it's inside the folder named 'css' that is inside the folder of the html file that I am using. as a result, 
      href = 'css/normalize.css'

11 .   < link rel="stylesheet" href="css/main.css" > : coding a link element referring to an external style sheet.
      this is a separate file that has the CSS for the web page. href attributes get usually coded with the URL relative
      to the current file 

12.    < meta name="theme-color" content="#fafafa" > : add a meta tag to the web page using "theme color" and set the 
      color to to a valid CSS color in this case #fafafa (the color hex composed of 98% red, 98% green, and 98% blue). 
      In this case the color hex (light grey) is applied to the browser 
  
13.   </head> : closing head tag of the head element. the < head > element is a container for all the head elements
      the < head > element can include a title for the scripts, styles, document, meta information, etc.
      
      The following tags, or elements, can go inside the < head > element: 
      < title > : defines the title of the document in the browser toolbar, provides a title for the page once added to 
                  favorites, and displays a title for the page in the results from a search engine
      < style > : to define the style information for an HTML document 
      < base > : used for specifying a default URL & default target for all links on a page
      < link > : link to an external style sheet
      < meta > : provides metadata about the HTML document. Metadata does not get displayed on the page, but it will be
                 machine parsable 
      < script > : to define a client-side script in JavaScript. it has scripting statements, or it points to an 
                   external script file through the sr attribute. Uses for JavaScript are the manipulation of images,
                   validation of form, and changing of contents dynamically
      < noscript > : defines alternate content for users that have scripts as disabled or are using a browser that 
                     does not support scripts 
    
    
    
* body = element 
  

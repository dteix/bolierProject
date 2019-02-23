# Timeline Project
# February 20th 2019
# Dennis Teixeira

1940- Stibitz demonstrated The Complex Number Calculator at an American Mathematical Society conference held at Darthmouth College. Stibitz stunned the group by performing calculations remotely on the CNC (located in New York) using a Teletype terminal connected to New York over special telephone lines. This was likely the first example of remote access computing. 

1941- Konrad Zuse finishes the Z3 computer. 

1942- The Atanasoff- Berry computer(ABC) is completed.

1943- The US Army asks Bell Laboratories to design a machine to assist in testing its M-9 gun director, a type of analog computer that aims large guns to their targets. Mathematician George Stibitz recommends using a relay-based calculator for the project. The result was the Relay Interpolator, later called the Bell Labs Model II. The Relay Interpolator used 440 relays, and since it was programmable by paper tape, was used for other applications following the war.

1944- Harvard Mark 1 is completed by Harvard physics professor Howard Aiken, and designed and built by IBM, the Harvard Mark 1 is a room-sized, relay-based calculator. The machine had a fifty-foot long camshaft running the length of the machine that synchronized the machine’s thousands of component parts and used 3,500 relays. The Mark 1 produced mathematical tables but was soon superseded by electronic stored-program computers.

1949- Modems were developed in 1949 for transmitting radar signals by Jack Harrington’s group at the Air Force Cambridge Research Center (AFCRC) near Boston, the modem modulates digital data into sounds, and demodulates received sounds into digital data. 
  
1956- At MIT, researchers begin experimenting with direct keyboard input to computers, a precursor to today´s normal mode of operation.
 
1957 – Russia puts Sputnik into orbit.

1958 – Space exploration assigned to Advanced Research Projects Agency (ARPA)

1958 – NASA opens for business via Eisenhower executive order.

1961 – Leonard Kleinrock of MIT wrote the first paper on packet switching theory.

1962 – J.C.R. Licklider of MIT writes memos on “Galactic Network Concept”

1965- ARPA sponsors study on cooperative network of time-sharing computers.

1968- Network Working Group, headed by Steve Crocker, loosely organized to develop host level protocols for communication over the ARPANET. 

1969 – Larry Roberts heads the project that connects first two ARPANET sites – UCLA and Stanford Research Institute.

1972 – Bob Kahn demonstrates ARPANET at the International Computer Communication Conference (ICCC) 

1972 – Ray Tomlinson discovered the first basic email program using “@”

1973- Bob Metcalfe's Harvard PhD Thesis outlines idea for Ethernet. The concept was tested on Xerox PARC's Alto computers, and the first Ethernet network called the Alto Aloha System 

1974- BBN opens Telenet, the first public packet data service, a commercial version of ARPANET.

1975- First ARPANET mailing list, MsgGroup, is created by Steve Walker. John Vittal develops MSG, the first all-inclusive email program providing replying, forwarding, and filing capabilities.

1979- ARPA establishes the Internet Configuration Control Board. 

1980- ARPANET grinds to a complete halt because of an accidentally-propagated status-message virus  

1983 – Jon Postel, Paul Mockapedis, and Craig Partridge design the Domain Name System (DNS)

1990 – Tim Berners-Lee creates World Wide Web

1993 – Marc Andreesen, Develops Mosaic web browser

1996 – Microsoft vs Netscape, Browser wars 


# Boilerplate Index File Information
# February 20, 2019
# David Salazar

1.< !doctype html >*: A doctype declaration which tells the browser that the document is using HTML.

2.< html class="no-js" lang="" > : The "no-js" class gets removed by a Javascript library (Modernizr), 
  and this gets replaced with a js class. When Modernizr loads, it replaces no-js with js.
      
  This is a way to style with OR without Javascript.
   
  In other words, CSS styles can be defined for JavaScript-enabled browsers and for browsers that 
  have JavaScript disabled. lang="" sets the language of the web page.

3.< head >: HTML tag also known as an element that is the container for all head elements. can have
  document title, styles, and other inforrmation. information about the web page itself. 
   
  < element > = opening tag
   
  < /element > = closing tag 

4.< meta charset="utf-8" > : Universal text format 8 for all languages (except Asian languages) that 
  read left to right.

5.< title> </ title > : The title of the webpage goes in between <title></title>. 
  ex: < title >Web xPage Title</ title>
   
6.< meta name="description" content="" > : Meta stands for metadata or information about specific data. < meta > gives  
  metadata of a HTML document. Metadata does not get displayed on a page, but it will instead be machine parsable
   
  Meta tags/elements are used to specify things like page description, a document's author, keywords,
  last modified (as well as other metadata), how to display/reload the content of a page, and search 
  engine keywords   
   
  Users can set the viewpoint of a website 
   
7.< meta name="viewport" content="width=device-width, initial-scale=1" > : This is used by the browser to render a web 
  page the size of a device's screen used to view it width = width of virtual viewport of device device-width = physical 
  width of device's screen initial-scale = 1 is the initial zoom. 1 is normal (without zooming in) 
   
8.< link rel="manifest" href="site.webmanifest" > : information about the application (name, author, icon,
  description, and how the application should behave once installed in a device) in a JSON text file. 
  informs details for websites installed on the home screen of a device
   
9.< link rel="apple-touch-icon" href="icon.png" > : provides back up name and an icon for the web page.
  it is the image that one can see if if the website is added to the home screen of a device 
   
10.< link rel="stylesheet" href="css/normalize.css" > : In rel = 'stylesheet' the href attribute specifies the 
   location of the file named normalize.css file. in this case, it's inside the folder named 'css' that is inside the 
   folder of the html file that I am using. as a result, href = 'css/normalize.css'
      
11.< link rel="stylesheet" href="css/main.css" > : coding a link element referring to an external style sheet.
   this is a separate file that has the CSS for the web page. href attributes get usually coded with the URL relative
   to the current file 
      
12.< meta name="theme-color" content="#fafafa" > : add a meta tag to the web page using "theme color" and set the 
   color to to a valid CSS color in this case #fafafa (the color hex composed of 98% red, 98% green, and 98% blue). 
   In this case the color hex (light grey) is applied to the browser 
  
13.< /head > : closing head tag of the head element. the < head > element is a container for all the head elements
   the < head > element can include a title for the scripts, styles, document, meta information, etc
     
    
14.< body > : the document's body containing all contents of an HTML document (ex: text, hyperlinks, images, tables, 
                 etc)
                 
15.< p >Hello world! This is HTML5 Boilerplate.< /p > : < p > is used for defining paragraphs 

16.< script src="js/vendor/modernizr-{{MODERNIZR_VERSION}}.min.js"></script > : Modernizsr is a JavaScript library 
   that finds HTML5 and CSS3 in a user's browser
      
17.< script src="https://code.jquery.com/jquery-{{JQUERY_VERSION}}.min.js" integrity="{{JQUERY_SRI_HASH}}" 
   crossorigin="anonymous"></script > :  JQuery is a JavaScript library used to wrap lines of code written in 
   JavaScript into methods that get called with single lines of code. This is loading JQuery
      
18.< script >window.jQuery || document.write('<script src="js/vendor/jquery-{{JQUERY_VERSION}}.min.js"><\/script>')
   < /script > : optimizes the way in which JQuery is loaded
      
19.< script src="js/plugins.js" >< /script > : a plug in, or a piece of code written in JavaScript. Provide useful 
   JQuery methods to be used with JQuery library methods 
      
20.< script src="js/main.js"></script > : establishes an entry point to the application 

21.< script > : defines a client-side script, JavaScript, that can either contain scripting elements or point to an 
   external script file using the src attribute
      
22.window.ga = function () { ga.q.push(arguments) }; ga.q = []; ga.l = +new Date;
   ga('create', 'UA-XXXXX-Y', 'auto'); ga('send', 'pageview')
   
   ga stands for google analytics. this a JavaScript library used for measuring user interaction with a website. It is 
   used for the tracking of an user's ID
   
23.< /script  > : closing script element

24.< script src="https://www.google-analytics.com/analytics.js" async defer >< /script > : provides small performance 
   boost on modern browsers, but at the same time can degrade to synchronous loading on older mobile browsers
   
25.< / body > : closing tag of the body tag

26.< /HTML > : closing of the HTML tag or HyperText Markup Language. This is the file retrieved by a web browser once it 
   builds a request for a web page in the form of a HTTP that gets rendered or translated to a HTML web page 
   
# Boilerplate: Descriptions Of All Files
# February 23, 2019
# David Salazar

1.doc file : contains TOC.md (table of contents), css.md, extend.md, faq.md, html.md, js.md, misc.md, and usage.md
  - TOC file : information on getting started with HTML, CSS, JavaScript, .gitignore, .editorconfig, Server 
    Configuration, robots.txt, humans.txt, browserconfig.xml.
    
      * css.md : explains Normalize.css (for making different browsers render web page consistently according to HTML 5 and 
      CSS standards), main.css (typography settings for improving readability and build up on css.md)
    
      * extend.md : information on making HTML5 Boilerplate projects better with App Stores information, Google Universal 
      Analytics, security.text, etc
     
      * faq.md : frequently asked questions
     
      * html.md : information on using HTML, and HTML5 Boilerplate homepage link
    
      * js.md : information on default JavaScript code included in a HTML5 Boilerplate project, javascript plugins, and 
      the vendor directory that has third party library code
    
  - misc.md : 
    
      * gitignore (used for avoiding specific project-level files and directories from being kept in 
      source control)
    
      * .editorconfig (encourages and helps people define and maintain consistent coding styles between 
      different editors
  
      * interactive development environment (IDE)
    
      * Server Configuration (H5BP with a .htaaccess file for Apache HTTP server)
     
      * robots.txt (gives instructions to web robots on what is to be crawled from the website)
    
      * humans.txt (provides information about people that are involved with a website), browserconfig.xml (used to 
      customize the tile displayed when users pin a web site with a Windows 8.1 start screen and allows for customizing 
      tile colors, custom images, and live tiles)
    
      * usage.md : explains the basic structure of a HTML file, listing of the major parts involved, and how to usethem
    
2.img file : contains a .gitingore file that is not available for viewing

3.js file : contains information for JavaScript plug ins

4..editorconfig file : contains information on whitespace editing for text 

5..gitattributes file : settings for normalizing text files, and for binary information to be left untouched 

6..gitignore file : contains the files and directories that Git will ignore before making a commit 
    
7.404.html file : provides an error message to show that the server could not find what an user requested, and provide a 
  message saying that a web page does not exist or was not found

8.browserconfig.xml file : used to define pinned site customizations for backgrounds, badge updates, tile notifications, 
  and customizations are set using external XML files instead of metadata in the HTML markup of a website

9.favicon.ico file : used for displaying the icon of a website left to an URL. ico is a file format that has a
  collection of images of different sizes and color depths

10.humans.txt file : provides information about people that are involved with a website

11.icon.png : an icon based on pixels, so it cannot be upscaled without losss of quality. png is a specific image

12.index file : has a default HTML skeleton that is the basis of pages for a website using html5-boilerplate

13.robots.txt file : gives instructions to web robots on what is to be crawled from the website
 
   
       

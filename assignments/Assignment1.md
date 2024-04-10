<h1>Assignment-1</h1><br>

<h3>1.What is Emmet?</h3>

Emmet is a plugin or web development tool kit that allows develpoers to write HTML and CSS code quickly and efficiently using abbrevations.It enables users to generate complex HTML and CSS structures by typing simple abbrevations and then expanding them into full code snippets.Emmet is commonly used in code editors and IDEs to boost productivity and streamline the process of writing markup and styling code.
<br>
html:5-basic structure of an HTML5 document.<br>
ul>li*5-nested elements<br>
div.container#main-content= <div class="container" id="main-content"></div>

<h3>2.Difference between a Library and Framework?</h3>

A Library is a collection of reusable code modules that can be called upon by a program.It provides functions and routines that can be directly used by your code.<br>
Think library is like a toolbox where you can pick and choose specific tools(functions)to use in your projects.you decide when and how to use each tool.
<br>
A framework sets up structure for your code and provides a foundation on which to build your application.It often dectates the flow of control,and your code fills in the details or hooks into the framework's predefined behaviour.<br>
A framework is more like a set of blueprints for building a house.It provides the overall structure and guidelines for how to build your project.You foloow the blue print and fill in the details to create your application.<br>


<h3>3.What is CDN? Why do we use it?</h3>
CDN stands fron Content Delivery Network.It's network of servers distributed geographically to deliver web content more efficiently to users.CDN caches copies of content in multiple locaton,reducing the distance between the user and the server,which improves loading times and overall performances.Its used to enhance website speed,reliability an scalabilty ,particularly for websites with high traffic or global audiences.
<br>
Think of a CDN like a network of delivery trucks.Instead of one big truck traveling long distance to deliver packages to everyone,there are many smaller trucks strategically placed closer to different negibourhood.This speeds up the delivery because packages dont have to travel so far.Similiarly,a CDN stors copies of website content (like images,videos,and scripts) on servers around the world.When someone visits a website,they get the content from the nearest server insted of the main server,making the website load faster.<br>

<h3>4.Why is React known as React</h3>
React got its name because of its reactive nature.It was designed to react to changes in data and automatically upadte the user interface accordingly.This reactive paradigm is at the core of React's functionality,hence the name "React.<br>

<h3>5.sWhat is CROSSORIGIN script tag?
The crossorigin attribute in a script tag is used to specify how the browser should handle requets made by the script tag when fetching resources from a different origin(ie,a different domain,protocol,port).It is commonly used when loading scripts from external sources such as CDNs.<br>

The crossorigin attribute can have different values:
anonymous:This value indicates that the cript is requesting resources without sending any credentials such as cookies,along with the requests.Its typically used for public resources that dont require authentication.<br>
user-credentials:This value indicates that the srcript requires credentials to be included with the request.It's used when the script needs access to protected resources that require authentication.<br>
By default ,when crossorigin attribute is not specified,the browser assumes the value is anonymous.Uisng the crossorigin attribute helps prevent certain types of security vulnerablties such as cross-site scripting attacks,by controlling how resources from different origins are accessed.<br>



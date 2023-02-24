# CS3200 Notes

## 1/9/23
---
**5 Projects**
1. Client side
2. Client side & Server
3. Client side & Server & Database
4. Client side & Server & Database & User Authentication
5. Deploy to cloud

**Static *vs* Dynamic** 


**DOM**

Document 
> HTML 

Object
> element/tag

Model
> Representation

**Print in JS**
console.log("*Hello, World!*")

**Linking JS tp HTML**

Add below code at the end of body for this class.
>`<script src="app.js"> </script>`

**Method used in this class with JS**
1. Query
2. Change content

**When ; is needed**
After
1. Calling a function.
2. Assigning a variable.

**Example of  querying element**
>`var h1Element = document.querySelector("#id or .class name here")`
>`h1Element.innerHTML = "something else between >This in the HTML<"`
These selectors can be console.log("With a description here:", h1Element)

#some-id
.some-class

**User Events**
1. Target Element(button, img, some element)
2. Actual event i.e. click/hover/keypress
3. Handler(listener). Outcome or action. A function!

Tip: Don't need to query what you've created

Function based so it can be repeatable

**Create random number**
Math.random() == random float between 0 and 1;
Math.random() * 10 == Random float between 0 and 9;
Math.Floor(Math.random() * 100) == Random integer between 0 - 99;
Note: exclusive

Python: Object == instance of a class
JavaScript: Object == Dictionary

Web-apps: Very data oriented
    Array of objects is the most common data structure
    Array of something...
    Event Driven programming

DOM Manipulation = changing an element
DOM Insertion = add/growing


**AJAX**
Asynchronous JS and XML (don't use XML anymore)
JSON - JavaScript Object Notation

Asynchronous - 
A - not
sync - together in
chrono - time

fetch == AJAX
AJAX because it provides a fluid user experience

User Experience >> Client >> User Interface >> Client
Client >> 1 Request >> Server >> 2 Response >> Client
Server >> DataBase >> Server

API - Application Programming Interface
Protocol - Agreed upon rules
Idempotent - May be repeated without occurring additional consequences
Same Origin Policy - CORS - Code can only phone home

Interview Question: Tell me about the same origin policy?

1 response per request >> Needs to have a response >> No Response == BAD

**Request**
*1. Method (GET/POST) or (Verb)*
*2. Path (Noun) or (/)*
3. Headers (MetaData)
4. Body (Data)

**Response**
*1. Status Code*
2. Headers
3. Body

**MIDTERM**
30 - 40 Questions
est 30-60min but 2 hours allotted
Conceptual questions
    - What is this for?
    - What do we do this?
    - What does this line of code do?

__

**Topics**

REST:
    Uniform Interface Interoperability
    Guidelines
    Path as noun / Method as Verb
    Manipulating
        update, create, retrieve
    POST was create

HTTP: REST uses HTTP as the protocol
    - Rule Based Communication
    -Requests are from client
    -Responses are from server
    Headers: 
        -Content Types
        -ie json, plain/text, www-urlencoded
    Access-Allow-Control- Origin

JSON:
    Interoperability // Notation
    Supported by many languages
    Medium for communicating data 

Unencoded Data:
    Simplified dictionary for simple bits of data

CORS:
    Is the exception to the rule.
    Code running in browser can only communicate to home server
    Server MUST authorize sharing cross-origin
    (All about protecting user)*Headers*

**Client**
AJAX: 
    Asynchronous - Communicating small points
        Giving attention to many things but one at a time
        For a smoother User-Experience

DOM(Output): 
    Dynamic - Can Change / Not Fixed
        Structure that evolves
    How WebApps work:
        Respond to what users are doing
        Our code has access to manipulate
        Interactivity
    -Query: Load certain element to Modify/Add/Insert elements
    -User Events(Input) - User Interactivity

HTTPServer:
    What runs program and listeners
        Listens & Waits

BaseHTTP: (subclass)
    Define responses / Define API

Fetch:
    What it is and what its for
    Implementing AJAX in JavaScript

Big Picture: 
    Client >< Server >< Architecture
    Accessibility - Can access across a myriad of devices.
    Common Centralized Accessibility

POST means Create
GET means Read

Status Codes:
    200
    201
    404
    400: Bad Request(General Status Code)

User Event:
    1. Element ie button
    2. Interaction ie mouse-over
    3. Event Handler: trigger function (do this thing)
        need to be a function ready to go

Structure of URL:
    https://    www.url.com     /xxxxx/xxxxxxx/xxxx/        ?hello=world \n
    Protocol    Hostname        Path                        Query String


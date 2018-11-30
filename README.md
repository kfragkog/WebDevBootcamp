# Introduction to this Course

# Introduction to Front End Development
 - the internet: url -> IP address -> HTTP request asking for content -> the servers job is to figure out what the request wants, what to send back -> the browser gets the response back in HTML, CSS, JS and displays content
- all the logic is in the Back End, all the stuff we see and interact with is the Front End
- dynamic vs static pages eg yelp vs restaurant page
- HTML defines the structure of a webpage - the “nouns”/skeleton of a webpage - it’s mandatory
- CSS defines the style of HTML - the “adjectives”/skin of a webpage
- JS adds logic and interactivity to a webpage = the “verbs”/actions on a webpage

# Introduction to HTML
HyperText Mark up Language - it allowed to create hyper links (1990)
We tag the content: <tagName> some content </tagName>
MDN - resource for HTML, CSS, JS
Every HTML doc will start with this boilerplate - html + tab:
<!DOCTYPE html> - to define that page uses HTML5
<html> - it’s html and we then need one head and one body
<head> - metadata, everything not displayed in the browser
	<title></title>
</head>
<body>

</body>
</html>
To add comment: <!-- text --> - cmd + /
Title is important for linking to page or googling it etc
h tag is a block element (gets its own line), not inline element like strong
Ordered list has numbers, unordered has bullet points
div - way of grouping things together (like a generic container) - block level element
span - generic container, but inline

attributes - add additional info to html elements - key value pair (link html attributes in MDN) - <tag attributename = "value"></tag>

src & href - two important attributes

a (anchor) tag is how we create links to other webpages - href is the url and between > and </a> we put the text for the link

relative path - add a link to a page that is relative to the one I am at (e.g page 2.html)

# Intermediate HTML
Tables - tr table row element, td element/cell inside row, th for heading in a tr OR thead and tbody

Forms
- the form tag is a container for all the inputs of a form eg the fb sign up form (all of it, so the items are submitted together): <form action = "/my-form-submitting-page" method="post"> all in puts here </form>
action: A form is going to send data to a server somewhere and this is the URL to send form data to, method: they type of HTTP request
- the input tag is what goes inside of our forms, and has the type attribute that we can create the different types
- button can be added with an input type submit or a button tag
- placeholder attribute is adding the temp text in a field so a user knows what to fill it in with
- name attribute in input tags is to give name to data so we can pass the value from the form and retrieve it later or send it to where the form sends the data to - if the same name is given, then the two things are connected
- labels are really important, as they let us add captions in a form; screenreading software will use those for ppls that need accessibility tools etc
when labels are used, the input tag goes in the label, and after the text we want the label to show OR use the same id/name in the for attribute for the label and the id for the input
- Validations to enforce rules and structure to the fields in a form (in an input) - two main things we can do with HTML, required fields (called: presence validation and we do we required) and validate the type of data that the user puts in a field eg an email does look like an email and we do with changing the type to email (for this example)
- further inputs.. Radio buttons/checkboxes, select tags (dropdown menus), textarea tag
- to tell hmtl that two radio buttons are linked we use the name attribute - we give them the same name
- to submit a form we can use either input type submit or the button tag but it needs to be the last line in the form
- value gives the name attribute an actual value to pass on so we know what was chosen by the user
- for dropdowns, use select tag and option tag in it (name and value can again be used to track data)
- textarea is like text, but for multiple lines - it's a tag
- to group things we can put them in p or div (for blocks)

# Introduction to CSS 6
- Stands for Cascading Style Sheets
- Seperate documents that we then include in our html file
- the General CSS rule:
  <!-- selector is where we reference existing html elements -->
  selector {
    <!-- and then we apply some style to it -->
    property: value;
    anotherProperty: value;
  }


















 - Intermediate CSS 7 - Bootstrap 8 - Introduction to JavaScript 9 - Javascript Basics: Control Flow 10 - Javascript Basics: Functions 11 - Javascript Basics: Arrays 12 - Javascript Basics: Objects 13 - DOM Manipulation 14 - Advanced DOM Manipulation 15 - Color Game Project 16 - Intro to jQuery 17 - Advanced jQuery 18 - Todo List Projects 19 - OPTIONAL Project: Patatap Clone 20 - Backend Basics 21 - The Command Line 22 - Node JS 23 - Server Side Frameworks 24 - Intermediate Express 25 - Working With API's 26 - YelpCamp: Basics 27 - Databases 28 - YelpCamp: Data Persistence 29 - RESTful Routing 30 - Data Associations 31 - YelpCamp: Comments 32 - Authentication 33 - YelpCamp: Adding Authentication 34 - YelpCamp: Cleaning Up 35 - YelpCamp: Update and Destroy 36 - YelpCamp: UI Improvements
37 - Git and Github 38 - Deploying 39 - JavaScript: The Tricky Stuff

1) What is the difference between HTML and XHTML?

Ans: HTML- HTML stands for Hypertext Markup Language.HTML is used to create web pages and link them from one to another.HTML is not a programming language, it is a markup language.We can use different other technologies as like CSS and javascript to give a new look to the pages developed by HTML. The format is a document file format.All tags and attributes are not necessarily to be in lower or upper case.Doctype is not necessary to write at the top.It is not necessary to close the tags in the order they are opened.While using the attributes it is not necessary to mention quotes.  For e.g. <Maria>.Filename extension used are .html, .htm.
  
    XHTML- XHTML stands for Extensible Hypertext Markup Language.It is extended from XML and HTML.The format is a markup language.In this, every tag and attribute should be in lower case.Doctype is very necessary to write at the top of the file.It is necessary to close the tags in the order they are opened.While using the attributes it is mandatory to mention quotes.  For e.g. <Maria=”MK”>.Filename extension are .xhtml, .xht, .xml.
  
2) What are the new form elements in HTML5?
  
Ans: There are a number of new form elements has been introduced in HTML 5 as follows: 
(1)Datalist:- Datalist provides functionality for auto-complete feature. 
(2)Datetime:- Datetime facilitate selecting a datetime along with Time Zone. 
(3)Output:- Output represents the result of a calculation. 
(4)Keygen:- Keygen generates a key-pair field in a form to implement secure authentication. 
(5)Date:- Date is an input field for date and applies validation accordingly. 
(6)Month:- Month for selecting a month and year in a form input field. 
(7)Week:- Week for selecting a week and year in an input field. 
(8)Time:- Time is an input field for selecting time i.e. Hours:Minutes: AM/PM. For example, 10:30 AM. 
(9)Color:- Color is an input field for color. 
(10)Number:- Number that only allows numeric values. 
(11)Range:- Range is an input field for selecting value within a specified range. 
(12)Email:- Email is input field for email with standard email validations. 
(13)URL:- Url is for an URL(Uniform Resource Locator) and validated accordingly.
  
3) What is DOM? How does the DOM work?
 
Ans: DOM stands for Document Object Model.When a web page is loaded, the browser creates a Document Object Model of the page.
     With the object model, JavaScript gets all the power it needs to create dynamic HTML:
      (1)JavaScript can change all the HTML elements in the page.
      (2)JavaScript can change all the HTML attributes in the page.
      (3)JavaScript can change all the CSS styles in the page.
      (4)JavaScript can remove existing HTML elements and attributes.
      (5)JavaScript can add new HTML elements and attributes.
      (6)JavaScript can react to all existing HTML events in the page.
      (7)JavaScript can create new HTML events in the page.
  
4) What does a <DOCTYPE html> do?
  
Ans: Doctype stands for Document Type Declaration. It informs the web browser about the type and version of HTML used in building the web document. This helps the browser to handle and load it properly.
  
5) What are the building blocks of HTML5?
  
Ans: The basic building blocks of HTML5 are:
      (1)Tags: An HTML tag surrounds the content and apply meaning to it. It is written between < and > brackets.
      (2)Attribute: An attribute in HTML provides extra information about the element, and it is applied within the start tag. An HTML attribute contains two                 fields: name & value.
      (3)Elements: An HTML element is an individual component of an HTML file. In an HTML file, everything written within tags are termed as HTML elements.
  
6) What is the difference between a <span> and a <div>?
  
Ans: The difference between <span> and a <div> are:
     A div is a block-level element and a span is an inline element. The div should be used to wrap sections of a document, while use spans to wrap small portions of text, images, etc. The <div> element is used while creating CSS based layouts in html, whereas <span> element is used to stylize texts.
  
7) Name 5 common block-level and inline HTML elements?
  
Ans: 5 common block-level elements are:
    (1) <h1>-<h6>
    (2) <p>
    (3) <div>
    (4) <main>
    (5) <li>
  
   Inline HTML elements:
   (1) <button>
   (2) <input>
   (3) <script>
   (4) <label>
   (5) <span>
  
8) What are Semantic and Non-Semantic elements in HTML?
  
Ans: A semantic element clearly describes its meaning to both the browser and the developer. Eg:<form> , <table> , and <article> - Clearly defines its content.
     Unlike, semantic elements they don’t have any meaning. They don’t tell anything about the content they contain. Eg:<div> and <span> - Tells nothing about its content.
  
9) Why you would like to use Semantic tag?
  
Ans: By adding semantic tags to your document, you provide additional information about that document, which aids in communication. Specifically, semantic tags make it clear to the browser what the meaning of a page and its content is.
  
10) What are the Semantic tags available in HTML5?
  
Ans: Some of the semantic tags available in HTML5 are <header>,<footer>,<article>,<form>,<table>.
  
11) What are the optional closing tag?
  
Ans: These are the following Optional closing tags:html, head, body, p, dt, dd, li, option, thead, th, tbody, tr, td, tfoot, colgroup .
  
12) What is a Self-closing tags?
  
Ans: A self-closing tag is a type of tag in HTML that need not to be closed by a closing tag, which means there is no saperate closing tag for it as </tag>. For example <img /> tag, <input /> tag, <br /> tag, etc. Self closing tags are also alternatively known as void tags, empty tags, singletons tags, etc.
  
13) What is the purpose of the main element?
  
Ans: The <main> tag specifies the main content of a document. The content inside the <main> element should be unique to the document.Which includes the sidebars, navigation links, copyright information, site logos, and search forms.
  Note: The document must not contained more than one <main> element . The <main> element should not be a child elements of an <article>, <aside>, <footer>, <header>, or <nav> element.

14) When should you use section,div or article?
  
Ans: <section> tag defines the section of documents such as chapters, headers, footers or any other sections. The section tag divides the content into section and subsections. The section tag is used when requirements of two headers or footers or any other section of documents needed. Section tag grouped the generic block of related contents. The main advantage of the section tag is, it is a semantic element, which describes its meaning to both browser and developer.
  
    The <div> is the most usable tag in web development because it helps us to separate out data in the web page and we can create a particular section for particular data or function in the web pages.
  
    The <article> HTML element represents a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable (e.g., in syndication). Examples include: a forum post, a magazine or newspaper article, or a blog entry, a product card, a user-submitted comment, an interactive widget or gadget, or any other independent item of content.
  
15) How to make page responsive?
  
Ans: We can make page responsive by using CSS and HTML to resize, hide, shrink, enlarge, or move the content to make it look good on any screen.
  
16) What is Character Encoding?
  
Ans: Character encoding is a method of converting bytes into characters.To validate or display an HTML document properly, a program must choose a proper character encoding.The most common character set or character encoding in use on computers is ASCII − The American Standard Code for Information Interchange, and this is probably the most widely used character set for encoding text electronically.
  
17) What is the purpose of meta tags?
  
Ans: The <meta> tag defines metadata about an HTML document. Metadata is data (information) about data. <meta> tags always go inside the <head> element, and are typically used to specify character set, page description, keywords, author of the document, and viewport settings.
  
18) What is the purpose of Alt attribute on images?
  
Ans:The required alt attribute specifies an alternate text for an image, if the image cannot be displayed. The alt attribute provides alternative information for an image if a user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).
  
19) What is the difference between Select and DataList?
  
Ans: Think of it as the difference between a requirement and a suggestion. For the select element,the user is required to select one of the options you've given. For the datalist element, it is suggested that the user select one of the options you've given, but he can actually enter anything he wants in the input.
  So which one you want to use depends upon your requirements. If the user must enter one of your choices, use the select element. If the user can enter whatever they want, use the datalist element.
  
20) What is Desktop First and Mobile First approach?
  
Ans: With a desktop-first approach you can build all the features you want and create them to the highest specs.Then as you test on smaller devices you’ll focus on keeping the interface light while supporting as many “high-end” features as possible.This workflow is quite different but starting from the desktop can be better for web designers who create feature-rich designs.
    Some benefits of Desktop approach are:
  (1) You get to see all major features at once.
  (2) It lets you imagine all the largest possibilities for your design first.
  (3) It’s the best strategy if your audience mostly uses desktops/laptops.
  
     With Mobile-first design is an approach in which web designers start product design for mobile devices first. This can be done by sketching or prototyping the web-app's design for the smallest screen first and gradually working up to larger screen sizes.
  
21) What are Data attributes good for?
  
Ans: Custom Data Attributes allow you to add your own information to tags in HTML. Even though the name suggests otherwise, these are not specific to HTML5 and you can use the data-* attribute on all HTML elements. 
The data-* attributes can be used to define our own custom data attributes. It is used to store custom data in private to the page or application. 
There are mainly 2 parts of the Data Attributes: 
  1)Attribute Name: Must be at least one character long, contain no capital letters and be prefixed with ‘data-‘.
  2)Attribute Value: Can be any string.
  Syntax: 
  <li data-book-author="Rabindra Nath Tagore"> Gitanjali </li>
  
22) Explain about HTML Canvas?
  
Ans: The HTML <canvas> element is used to draw graphics on a web page.The HTML 5 <canvas> tag is used to draw graphics using scripting language like JavaScript.
  
23) What is the difference between SVG and Canvas?
  
Ans:  <svg> produces raster graphics, while <canvas> produces vector graphics. <svg> cannot be used as a background image, while <canvas> can be used as a background.
  
24) Explain Drag and Drop in HTML5?
  
Ans: It is a powerful user interface concept which is used to copy, reorder and delete items with the help of mouse. You can hold the mouse button down over an element and drag it to another location. If you want to drop the element there, just release the mouse button.
  
25) Describe the difference between a cookie,sessionStorage and localStorage?
  
Ans: LocalStorage as it's called it's local storage for your browsers, it can save up to 10MB, SessionStorage does the same, but as it's name saying, it's session based and will be deleted after closing your browser, also can save less than LocalStorage, like up to 5MB, but Cookies are very tiny data storing in your computer when you visit a website.
  
26) List the API available in HTML5?
  
Ans: API available in HTML5 are:
    1)Geolocation
    2)getUserMedia/Stream API
    3)Forms
    4)Drag and Drop
    5)Ambient Light API
  
27) What does async and defer refer in script tag? Describe the difference between <script>,<script async> and <script defer>?
  
Ans: The async attribute is a boolean attribute.If async is present: The script is downloaded in parallel to parsing the page, and executed as soon as it is available (before parsing completes).The HTML defer attribute is a Boolean attribute which is used to specify that script is executed when the page has finished parsing.
  
  <script> : Including a script without async or defer is the default way to load scripts in the HTML document. 
  <script async>: By including a script with the async attribute, the script is downloaded in parallel with the interpretation of the HTML. When the script is downloaded, it's executed, blocking the rendering until it finishes.
  <script defer>: Finally, the deferred script will be downloaded asynchronously and in parallel with the HTML parsing, however, its execution is deferred until the whole HTML document has been parsed. In this case, if multiple scripts are loaded, the same loading order will be respected when executing it.
    
 28) Define Semantic Markup.What are the semantic meanings for <section>,<article>,<aside>,<nav>,<header>,<footer> and when/how should each be used in structuring html markup?
    
 Ans: Semantic HTML elements are those that clearly describe their meaning in a human- and machine-readable way. Elements such as <header> , <footer> and <article> are all considered semantic because they accurately describe the purpose of the element and the type of content that is inside them.
     <section>: The <section> element defines a section in a document.
     <article>: The <article> element specifies independent, self-contained content.
     <aside>: The <aside> HTML element represents a portion of a document whose content is only indirectly related to the document's main content.
     <nav>: The <nav> element defines a set of navigation links. 
     <header>: The <header> element represents a container for introductory content or a set of navigational links.
     <footer>: The <footer> element defines a footer for a document or section.
       


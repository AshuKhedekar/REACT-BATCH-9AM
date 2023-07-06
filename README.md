# REACT-BATCH-9AM
HTML stands for Hyper Text Markup Language.
HTML is used to create webpages by using tags/elements which is given by w3(world wide web).
To create HTML page, just save that file with .html extention
All .html files can run only in web browsers like IE, Chrome, Firefox,Opara,Safari etc.

# Syntax:
Tag: <Tagname></Tagname> : <script></script>
Element: <Tagname> Content </Tagname> : <span>Sachin</span>
Self closing Element: <Tagname /> : <input/>

# Markup Language vs Programming Language
# Markup Language(HTML):
No compilation is required to run.
No tags are mandatory, empty .html files also run in browser.
If no tags in .html file, then browser placed by default three tags, html,head,body\\

# Programming Language(C):
First have to compile, after that only can run.
Minimum lines of code is required, at least main() method.

# Inline Elements:
Inline elements takes content width as its own width.
Inline elements are not starts in new line
span,i,b,img,input,select etc.. are Inline elements
By using display:block CSS property ,we can convert Inline element into block level element.

# Block Level Elements:
Block level elements takes parent width as its own width.
Block level elements always starts in new line
p,div,h1..h6,ul,li etc.. are Block level elements
By using display:inline CSS property ,we can convert Block level element into inline element.

# Attribute:
An attribute is a key value pair, it tells the behavior of an element.
Attribute key is always unique.
Then common attributes for all HTML elements are id,name,class,style etc..
# Ex:

<div id="div1" >Sachin </div>

In this 'id' is an attribute.
'Id' attribute value always unique(recomended).

# Input Controls:
# 1.Text Box:

Using input tag we can create text box.
The default attribute for input tag is type=text.
Ex:

<input/>
<input type="text" />

# 2.Password Box:

Using input tag and type=password attribute we can create password field.
Ex:

<input type="password" />

# 3.Radio button:

If we select one option from multiple options, then go with radio button.
Using input tag and type=radio attribute we can create radio button.
To group radio buttons , we have to take same name attribute values.
# Ex:

<input type="radio" name='gen'/> Male
<input type="radio" name='gen'/> FeMale

# 4.checkbox:

If we select multiple options from multiple options, then go with checkbox.
Using input tag and type=checkbox attribute we can create checkbox.
# Ex:

<input type="checkbox" /> Cricket
<input type="checkbox" /> Hockey

# 5 Dropdown:

If we select single optio from multiple options, then go with select box(dropdown).
Using select, option tags, we can create checkbox.
# Ex:


<select>
    <option>India</option>
    <option>Pak</option>
    <option>China</option>
</select>
    

# 6.textarea:

If you want to write more content in multiple row, then go with textarea
Using textarea tag, we can create textarea.
# Ex:

<textarea cols="30" rows="4"> </textarea>

# 7.File Upload:

Using input tag and type=file attribute we can create File Upload.
# Ex:

<input type="file" />

# HTML TAGS:
# title:
which is used to give title to your html page, which is visible in brower tab.

# script:
which is used to load your .js file into html.
By using 'src' attribute , we can give .js file path.
link:

# We are using link tag in two ways:
1.to load your .css file into html.By using 'href' attribute , we can give .css file path.By using 'rel' attribute, we can tell like this is used for stylesheet.
2.to add favicon to your html file,which is visible in brower tab.By using 'href' attribute , we can give icon file path.By using 'rel' attribute, we can tell like this is used for favicon.
# Ex:
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Page Title</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" type="text/css" media="screen" href=" href="your css file path"" />
    <script src=" href="your js file path""></script>
</head>
<body>
    //content to show in browser
</body>
</html>
    
# iframe:
which is used to load external urls into your html.
If you want's to load any you tube video or any other website in your html
<iframe src="http://www.uijavakit.com"></iframe>
<iframe width="420" height="345" src="https://www.youtube.com/embed/tgbNymZ7vqY"></iframe>

# image:
which is used to load image into your html.
If you want's to load any image, first take that image path, and give that path to src attribute of image tag
<img src="your image path"></img>

# Table:
If you want to display the data in the form of rows and columns, then go with table tag.
The table contains rows.
The rows contains heading or data..
table is representing by 'table' tag, row is representing by 'tr' tag, heading is representing by 'th' and data is representing by 'td' tag..

<table border='1px'>
    <tr>
        <th>Name</th>
        <th>Runs</th>
    </tr>
    <tr>
        <td>Sachin</td>
        <td>20000</td>
    </tr>
    <tr>
        <td>Dhoni</td>
        <td>18000</td>
    </tr>
</table>
    
# ul:
which is used to create unordered list.
we can represent unordered list by using 'ul' tag and the items in the list can represent 'li' tag.
By default unordered list items are displayed with dot(.)

<ul>
    <li>Sachin</li>
    <li>Dhoni</li>
    <li>Kohli</li>
    <li>UV</li>
</ul>
    
# ol:
which is used to create ordered list.
we can represent ordered list by using 'ol' tag and the items in the list can represent 'li' tag.
By default ordered list items are displayed with numbers(1,2,3...)

<ol>
    <li>Sachin</li>
    <li>Dhoni</li>
    <li>Kohli</li>
    <li>UV</li>
</ol>
    
# a(anchor):
which is used to navigate from one page to another page.
First take the path,where you want to navigate, and then give that path to 'href' attribute of 'a' tag.
<a href="http://www.google.com" >Click Here </a>

# HTML5:
It's a open source markup language used to building modern websites. It's a combination of HTML,CSS,JS.
New features introduced in HTML5 are

# Semantic Tag:
Semantic tags are using for better structure of your webpage. It's tells something about the content to the developer by seeing.
We are using Semantic tags to developing E-newspapers.
non-semantic elements: div,p - Tells nothing about its content.
# semantic elements:
header,footer,nav - Clearly tells about its content.
# section: 
This element tells a section in a document.A web page could normally be split into sections.
# article: 
This element tells independent, self-contained content.
# header: 
this element tells about the header part of your webpage. It may contains h1-h6 tags, logos.
# footer: 
this element tells about the footer part of your webpage.
hgroup
# aside: 
This element defines some content aside from the web content.
command
# details: 
It provides additional details that the user can view or hide
# summary: 
Defines a visible heading for a details element.
 <html>
                        <head></head>
                        <body>
                            <details>
                            <summary>HTML5 features ?</summary>
                            <p>Semantic Elements</p>
                            <p>New Inputcontrols</p>
                            <p>New Attributes</p>
                            <p>Web Storages</p>
                            <p>Web workers</p>
                            <p>Web Sockets</p>
                            </details>
                        </body>
                    </html>
                   
                
# figure: 
This tag specifies self-contained content, like diagrams, photos etc.
# figurecaption: 
This element can be placed as child of a figure element, it's tells something about figure.
# nav: 
In this element we can define navigation links.
# mark:
Defines marked/highlighted text.
# time: 
Defines a date/time
# meter: 
If you want to specify the range.

                    <html>
                        <head></head>
                        <body>
                            <h3>50% compelted </h3>
                            <meter value='5' max="10">
                        </body>
                    </html>
                
# Input Controls
In HTML5 introduced below new input controls(type attribute values)
color
email
number
range
search
tel
url
date
datetime
# eg. --> You can use above list items to the input tag with type attribute. <input type="color" />
Attributes

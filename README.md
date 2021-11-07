# html-101

install pljugins
- presentation assistant
- live edit (for debug and open in browser the html page)
- prettier

Live template -> with h1 and tab -> generate the automatically the tag
Live template support Emmet -> create a syntax with keystroke html editing fast

div.jumbotron>div.container>h1{hellow, emmet}+p{this is a sample application}      ,  hit tab
ul>li*5


package json you can run and customize your runs


.editorconfig file - you can customize you rules
of indent size, syntax, spaces , etc

https://editorconfig.org/
EditorConfig helps maintain consistent coding styles for multiple developers working on the same project across various editors and IDEs.
ctlr+alt+l  -> reformat code

prettier -> reformatter

preference -> search code style -> (there is html , css and various languages)

go to plugins and install prettier
also install depencies with npm

npm install --save-dev --save-exact prettier

preference -> prettier  -> see node interpreter have project and prettier package is the actual project path

also check in the package.json, that have prettier dev dependencies

"devDependencies": {
  "parcel-bundler": "^1.12.4",
  "prettier": "2.4.1"
}

we need to add comfiguration file
create file named .prettierrc

add json

{
"trailingComma": "es5",
"tabWidth": 4,
"semi": false,
"singleQuote": true
}

open javascript file
right click -> reformat with prettier to apply

intellij hint you about prettier syntax also

http client

single page application -
option is postman

intellij idea menu tools 0> http client -> test restful web service

you can scretae scrateches -> create http request file
rest-api.http

database

- in the right tab
databases
  + button click
  data source -> choose your databases

add name of data base
host , user and password, credentials

after connect you can see the tables in the right tab
get contents
edit content
add new row

lite database editor sql developer etc.

you can run your sql query in sql console
intellij idea give hint about sql language

also you can download data in different document format the query result, tsv, csv , etc.
different kind of export format


- migration

keymap

intellij idea support eclipse, netbenas, visual studio, sublime text, vs code, vim

configurations -> keymap 0<> you see keymap

plugins -> you can down load vs code keymap

you can use shortcut and key combinations of the original another ides


HTML 101


HTML stands for Hyper Text Markup Language
TML describes the structure of a Web page
HTML consists of a series of elements
HTML elements tell the browser how to display the content


The <!DOCTYPE html> declaration defines that this document is an HTML5 document
The <html> element is the root element of an HTML page
The <head> element contains meta information about the HTML page
The <title> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
The <body> element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
The <h1> element defines a large heading
The <p> element defines a paragraph

An HTML element is defined by a start tag, some content, and an end tag:

<tagname>Content goes here...</tagname>


<br>   breakline and doesnt have end tag
HTML elements with no content are called empty elements.
The <br> tag defines a line break, and is an empty element without a closing tag


HTML history

1989	Tim Berners-Lee invented www
1991	Tim Berners-Lee invented HTML
1993	Dave Raggett drafted HTML+
1995	HTML Working Group defined HTML 2.0
1997	W3C Recommendation: HTML 3.2
1999	W3C Recommendation: HTML 4.01
2000	W3C Recommendation: XHTML 1.0
2008	WHATWG HTML5 First Public Draft
2012	WHATWG HTML5 Living Standard
2014	W3C Recommendation: HTML5
2016	W3C Candidate Recommendation: HTML 5.1
2017	W3C Recommendation: HTML5.1 2nd Edition
2017	W3C Recommendation: HTML5.2


headings
<h1> -> <h6>  type of headers, h1 is the most biggest and h6 is the least big.
h1 is most important and h6 is least important for seo search

parragraphs
<p>

links
<a href="https://www.google.com">google</a>

image - image tag doesnt have end tag or close tag
<img src="imagen.png" alt="image descrition" width="100" height="100">

An HTML element is defined by a start tag, some content, and an end tag.

HTML is Not Case Sensitive
HTML tags are not case sensitive: <P> means the same as <p>.

The HTML standard does not require lowercase tags,
but W3C recommends lowercase in HTML, and demands lowercase for stricter document types like XHTML.

HTML attributes provide additional information about HTML elements.

All HTML elements can have attributes
Attributes provide additional information about elements
Attributes are always specified in the start tag
Attributes usually come in name/value pairs like: name="value"

href attribute

<a href="https://www.w3schools.com">Visit W3Schools</a>

1. Absolute URL - Links to an external image that is hosted on another website. Example: src="https://www.w3schools.com/images/img_girl.jpg".

Notes: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

2. Relative URL - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg"

The <img> tag should also contain the width and height attributes, which specifies the width and height of the image (in pixels)

The required alt attribute for the <img> tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to slow connection, or an error in the src attribute, or if the user uses a screen reader.

The style attribute is used to add styles to an element, such as color, font, size, and more.

You should always include the lang attribute inside the <html> tag, to declare the language of the Web page. This is meant to assist search engines and browsers.

<html lang="en">

Country codes can also be added to the language code in the lang attribute. So, the first two characters define the language of the HTML page, and the last two characters define the country.

<html lang="en-US">

The title attribute defines some extra information about an element.

-> tooltip
<p title="I'm a tooltip">This is a paragraph.</p>

We Suggest: Always Use Lowercase Attributes

However, W3C recommends lowercase attributes in HTML, and demands lowercase attributes for stricter document types like XHTML.


We Suggest: Always Quote Attribute Values
The HTML standard does not require quotes around attribute values.

However, W3C recommends quotes in HTML, and demands quotes for stricter document types like XHTML.

use quote  href="/path"   in attributes, because of the spaces title=About title    can throw error

Double quotes around attribute values are the most common in HTML, but single quotes can also be used.

<p title='John "ShotGun" Nelson'>
<p title="John 'ShotGun' Nelson">

All HTML elements can have attributes
The href attribute of <a> specifies the URL of the page the link goes to
The src attribute of <img> specifies the path to the image to be displayed
The width and height attributes of <img> provide size information for images
The alt attribute of <img> provides an alternate text for an image
The style attribute is used to add styles to an element, such as color, font, size, and more
The lang attribute of the <html> tag declares the language of the Web page
The title attribute defines some extra information about an element


HTML headings are titles or subtitles that you want to display on a webpage.

Search engines use the headings to index the structure and content of your web pages.

Users often skim a page by its headings. It is important to use headings to show the document structure.

<h1> headings should be used for main headings, followed by <h2> headings, then the less important <h3>, and so on.

Each HTML heading has a default size. However, you can specify the size for any heading with the style attribute, using the CSS font-size property:
<h1 style="font-size:60px;">Heading 1</h1>

A paragraph always starts on a new line, and is usually a block of text.
A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before and after a paragraph.

The browser will automatically remove any extra spaces and lines when the page is displayed

The <hr> tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule.

the HTML <br> element defines a line break.

The HTML <pre> element defines preformatted text.

The HTML style attribute is used to add styles to an element, such as color, font, size, and more.

<tagname style="property:value;">

The property is a CSS property. The value is a CSS value.

Use the style attribute for styling HTML elements
Use background-color for background color
Use color for text colors
Use font-family for text fonts
Use font-size for text sizes
Use text-align for text alignment

    HTML Text Formatting

    <b> - Bold text
    <strong> - Important text
    <i> - Italic text
    <em> - Emphasized text
    <mark> - Marked text
    <small> - Smaller text
    <del> - Deleted text
    <ins> - Inserted text
    <sub> - Subscript text
    <sup> - Superscript text

    HTML Quotation and Citation Elements

    In this chapter we will go through the <blockquote>,<q>, <abbr>, <address>, <cite>, and <bdo> HTML elements.

    The HTML <blockquote> element defines a section that is quoted from another source.

    Browsers usually indent <blockquote> elements.

    The HTML <q> tag defines a short quotation.

    <p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>


    The HTML <abbr> tag defines an abbreviation or an acronym, like "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM".
    <p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>

    HTML <address> for Contact Information
    The HTML <address> tag defines the contact information for the author/owner of a document or an article.
    The contact information can be an email address, URL, physical address, phone number, social media handle, etc.

    <address>
    Written by John Doe.<br>
    Visit us at:<br>
    Example.com<br>
    Box 564, Disneyland<br>
    USA
    </address>

    The HTML <cite> tag defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.).

    HTML <bdo> for Bi-Directional Override
    BDO stands for Bi-Directional Override.

    The HTML <bdo> tag is used to override the current text direction:
    <bdo dir="rtl">This text will be written from right to left</bdo>

    HTML comments are not displayed in the browser, but they can help document your HTML source code.

    You can add comments to your HTML source by using the following syntax:

    <!-- Write your comments here -->

    you can add comment, hide content, Hide Inline Content

    <p>This <!-- great text --> is a paragraph.</p>


    HTML colors are specified with predefined color names, or with RGB, HEX, HSL, RGBA, or HSLA values.

    text color

    Color Names  -> color:red;
    140 standard color names

    background color

    <h1 style="background-color:DodgerBlue;">Hello World</h1>

    border color

    <h1 style="border:2px solid Tomato;">Hello World</h1>

    rgb
    rgb(255, 99, 71)

    hex
    #ff6347

    hsl
    hsl(9, 100%, 64%)

    following two <div> elements have their background color set with RGBA and HSLA values, which adds an Alpha channel to the color (here we have 50% transparency):

    rgba
    rgba(255, 99, 71, 0.5)

    hsla
    hsla(9, 100%, 64%, 0.5)

    <h1 style="background-color:rgb(255, 99, 71);">...</h1>
    <h1 style="background-color:#ff6347;">...</h1>
    <h1 style="background-color:hsl(9, 100%, 64%);">...</h1>
    <h1 style="background-color:rgba(255, 99, 71, 0.5);">...</h1>
    <h1 style="background-color:hsla(9, 100%, 64%, 0.5);">...</h1>


    An RGB color value represents RED, GREEN, and BLUE light sources.

    An RGBA color value is an extension of RGB with an Alpha channel (opacity).

    Each parameter (red, green, and blue) defines the intensity of the color with a value between 0 and 255.

    This means that there are 256 x 256 x 256 = 16777216 possible colors!

    The alpha parameter is a number between 0.0 (fully transparent) and 1.0 (not transparent at all):

    A hexadecimal color is specified with: #RRGGBB, where the RR (red), GG (green) and BB (blue

    here rr (red), gg (green) and bb (blue) are hexadecimal values between 00 and ff (same as decimal 0-255).

    For example, #ff0000 is displayed as red, because red is set to its highest value (ff), and the other two (green and blue) are set to 00.

    HSL stands for hue, saturation, and lightness.

    HSLA color values are an extension of HSL with an Alpha channel (opacity).

    Hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green, and 240 is blue.

    Saturation is a percentage value, 0% means a shade of gray, and 100% is the full color.

    Lightness is also a percentage value, 0% is black, and 100% is white.

    Saturation can be described as the intensity of a color.

    100% is pure color, no shades of gray

    50% is 50% gray, but you can still see the color.

    0% is completely gray, you can no longer see the color.

    The lightness of a color can be described as how much light you want to give the color, where 0% means no light (black), 50% means 50% light (neither dark nor light) 100% means full lightness (white).

    HSLA Color Values
    HSLA color values are an extension of HSL color values with an Alpha channel - which specifies the opacity for a color.

    An HSLA color value is specified with:

    hsla(hue, saturation, lightness, alpha)

    The alpha parameter is a number between 0.0 (fully transparent) and 1.0 (not transparent at all):

    CSS stands for Cascading Style Sheets.

    CSS saves a lot of work. It can control the layout of multiple web pages all at once.

    Cascading Style Sheets (CSS) is used to format the layout of a webpage.

    With CSS, you can control the color, font, the size of text, the spacing between elements, how elements are positioned and laid out, what background images or background colors are to be used, different displays for different devices and screen sizes, and much more!

    The word cascading means that a style applied to a parent element will also apply to all children elements within the parent. So, if you set the color of the body text to "blue", all headings, paragraphs, and other text elements within the body will also get the same color (unless you specify something else)!

    CSS can be added to HTML documents in 3 ways:

    Inline - by using the style attribute inside HTML elements
    Internal - by using a <style> element in the <head> section
    External - by using a <link> element to link to an external CSS file


    The most common way to add CSS, is to keep the styles in external CSS files

    Inline CSS
    An inline CSS is used to apply a unique style to a single HTML element.

    <h1 style="color:blue;">A Blue Heading</h1>

    Internal CSS
    An internal CSS is used to define a style for a single HTML page.

    An internal CSS is defined in the <head> section of an HTML page, within a <style> element.

    <style>
    body {background-color: powderblue;}
    h1   {color: blue;}
    p    {color: red;}
    </style>

    External CSS
    An external style sheet is used to define the style for many HTML pages.

    <head>
      <link rel="stylesheet" href="styles.css">
    </head>

    styles.css file :

    body {
      background-color: powderblue;
    }

    The CSS color property defines the text color to be used.

    The CSS font-family property defines the font to be used.

    The CSS font-size property defines the text size to be used.

    The CSS border property defines a border around an HTML element.

    The CSS padding property defines a padding (space) between the text and the border.

    The CSS margin property defines a margin (space) outside the border.

    External style sheets can be referenced with a full URL or with a path relative to the current web page.

    <link rel="stylesheet" href="https://www.w3schools.com/html/styles.css">


    h1 {
      color: blue;
      font-family: verdana;
      font-size: 300%;
      border: 2px solid powderblue;
      padding: 30px;
      margin: 50px;
    }


    Use the HTML style attribute for inline styling
    Use the HTML <style> element to define internal CSS
    Use the HTML <link> element to refer to an external CSS file
    Use the HTML <head> element to store <style> and <link> elements
    Use the CSS color property for text colors
    Use the CSS font-family property for text fonts
    Use the CSS font-size property for text sizes
    Use the CSS border property for borders
    Use the CSS padding property for space inside the border
    Use the CSS margin property for space outside the border

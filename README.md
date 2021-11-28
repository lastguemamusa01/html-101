# html-101

---

## install plugins

* presentation assistant
* live edit (for debug and open in browser the html page)
* prettier

## live template features

Live template -> with h1 and tab -> generate the automatically the tag

Live template support Emmet -> create a syntax with keystroke html editing fast

execute : hit tab

```html
div.jumbotron>div.container>h1{hellow, emmet}+p{this is a sample application}

ul>li*5
```

## edit config file

package json you can run and customize your runs

.editorconfig file - you can customize you rules of indent size, syntax, spaces , etc

https://editorconfig.org/

EditorConfig helps maintain consistent coding styles for multiple developers working on the same project across various editors and IDEs.

ctlr+alt+l  -> reformat code

## prettier

prettier -> reformatter

preference -> search code style -> (there is html , css and various languages)

go to plugins and install prettier

also install depencies with npm

npm install --save-dev --save-exact prettier

preference -> prettier  -> see node interpreter have project and prettier package is the actual project path

also check in the package.json, that have prettier dev dependencies

```
"devDependencies": {
  "parcel-bundler": "^1.12.4",
  "prettier": "2.4.1"
}
```

we need to add comfiguration file

create file named .prettierrc

add json

```json
{
  "trailingComma": "es5",
  "tabWidth": 4,
  "semi": false,
  "singleQuote": true
}
```

open javascript file

right click -> reformat with prettier to apply

intellij hint you about prettier syntax also

http client

single page application -

option is postman

intellij idea menu tools 0> http client -> test restful web service

you can scretae scrateches -> create http request file

rest-api.http

## database

in the right tab -> databases -> + button click data source -> choose your databases

add name of data base host , user and password, credentials

after connect you can see the tables in the right tab
* get contents
* edit content
* add new row

lite database editor sql developer etc.

you can run your sql query in sql console

intellij idea give hint about sql language

also you can download data in different document format the query result, tsv, csv , etc.
different kind of export format


## migration

keymap

intellij idea support eclipse, netbenas, visual studio, sublime text, vs code, vim

configurations -> keymap 0<> you see keymap

plugins -> you can down load vs code keymap

you can use shortcut and key combinations of the original another ides

---

# MarkDown

WYSWYG - what you see is what you get

Lightweight markup language with a plain text formatting syntax

Can be coverted into HTML/XHTML and other formats

It's main purpose is readability and ease of use

## Where is used for ?

* readme files(github,etc)
* forum & blog posts
* used in many static site generators

## Basic type of formatting

Headings, lists, emphasis, links, blocks of code, images, blockquotes, horizontal rules

they are some extensions like php markdown, github has special flavor of markdown

## markdown editors :

text editor extensions (VS code, atom, etc), markpad, haroopad, markdownpad 2 and typora

## cheatsheet

we can use for comment as html style

<!-- Headings -->
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

<!-- italics -->
*This text* is italic
_This text_ is italic

<!-- strong -->
**This text** is strong
__This text__ is strong

<!-- Strikethrough -->
~~This text~~ is strikethrough

<!-- Horizontal Rule -->

triple underscole or just triple minus

---
___

<!-- Blockquote -->
> This is a quote

<!-- Links -->
[Traversy Media](http://www.traversymedia.com)

link with title

[Traversy Media](http://www.traversymedia.com "Traversy Media")


<!-- UL -->
* Item 1
* Item 2
* Item 3
  * Nested Item 1
  * Nested Item 2

<!-- 0L -->
1. Item 1
1. Item 2
1. Item 3

<!-- Inline Code Block -->
`<p>This is paragraph</p>`

<!-- Images -->
![Mardown Logo](https://markdown-here.com/img/icon256.png)



<!-- Github Markdown -->

<!-- Code Blocks-->
```bash
  npm install

  npm start
```

```javascript
  function add(num1, num2) {
    return num1 + num2;
  }
```

```python
  def add(num1, num2):
    return num1 + num2
```

<!-- Tables -->

| Name       | Email         |
|------------|---------------|
| John Doe   | joh@email.com |
| min ku nam | min@email.com |

<!-- Task Lists(checkbox) -->

* [x] Task 1
* [ ] task 2

---

## HTML 101

### html

HTML stands for Hyper Text Markup Language

TML describes the structure of a Web page

HTML consists of a series of elements

HTML elements tell the browser how to display the content

```
The <!DOCTYPE html> declaration defines that this document is an HTML5 document

The <html> element is the root element of an HTML page

The <head> element contains meta information about the HTML page

The <title> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)

The <body> element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.

The <h1> element defines a large heading

The <p> element defines a paragraph

An HTML element is defined by a start tag, some content, and an end tag:
```

```html
<tagname>Content goes here...</tagname>
```

```
<br> breakline and doesnt have end tag

HTML elements with no content are called empty elements.

The <br> tag defines a line break, and is an empty element without a closing tag
```


### HTML history

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


### headings

html elements : `<h1> to <h6>`

type of headers, h1 is the most biggest and h6 is the least big.
h1 is most important and h6 is least important for seo search

### paragraphs
`<p>`

### links
`<a href="https://www.google.com">google</a>`


### image

image tag doesn't have end tag or close tag

`<img src="imagen.png" alt="image descrition" width="100" height="100">`

An HTML element is defined by a start tag, some content, and an end tag.

HTML is Not Case Sensitive

HTML tags are not case sensitive: `<P> means the same as <p>`.

The HTML standard does not require lowercase tags,
but W3C recommends lowercase in HTML, and demands lowercase for stricter document types like XHTML.

### html attributes

HTML attributes provide additional information about HTML elements.

All HTML elements can have attributes

Attributes provide additional information about elements

Attributes are always specified in the start tag

Attributes usually come in name/value pairs like: name="value"

### href attribute

`<a href="https://www.w3schools.com">Visit W3Schools</a>`

1. Absolute URL - Links to an external image that is hosted on another website. Example: src="https://www.w3schools.com/images/img_girl.jpg".

Notes: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

2. Relative URL - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg"

The <img> tag should also contain the width and height attributes, which specifies the width and height of the image (in pixels)

The required alt attribute for the <img> tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to slow connection, or an error in the src attribute, or if the user uses a screen reader.

The style attribute is used to add styles to an element, such as color, font, size, and more.

You should always include the lang attribute inside the <html> tag, to declare the language of the Web page. This is meant to assist search engines and browsers.

`<html lang="en">`

Country codes can also be added to the language code in the lang attribute. So, the first two characters define the language of the HTML page, and the last two characters define the country.

`<html lang="en-US">`

The title attribute defines some extra information about an element.

### tooltip
`<p title="I'm a tooltip">This is a paragraph.</p>`

We Suggest: Always Use Lowercase Attributes

However, W3C recommends lowercase attributes in HTML, and demands lowercase attributes for stricter document types like XHTML.

We Suggest: Always Quote Attribute Values

The HTML standard does not require quotes around attribute values.

However, W3C recommends quotes in HTML, and demands quotes for stricter document types like XHTML.

use quote  href="/path"   in attributes, because of the spaces title=About title    can throw error

Double quotes around attribute values are the most common in HTML, but single quotes can also be used.

`<p title='John "ShotGun" Nelson'>`

`<p title="John 'ShotGun' Nelson">`

All HTML elements can have attributes

```
The href attribute of <a> specifies the URL of the page the link goes to
The src attribute of <img> specifies the path to the image to be displayed
The width and height attributes of <img> provide size information for images
The alt attribute of <img> provides an alternate text for an image
The style attribute is used to add styles to an element, such as color, font, size, and more
The lang attribute of the <html> tag declares the language of the Web page
The title attribute defines some extra information about an element
```

HTML headings are titles or subtitles that you want to display on a webpage.

Search engines use the headings to index the structure and content of your web pages.

Users often skim a page by its headings. It is important to use headings to show the document structure.

```
<h1> headings should be used for main headings, followed by <h2> headings, then the less important <h3>, and so on.

Each HTML heading has a default size. However, you can specify the size for any heading with the style attribute, using the CSS font-size property:
<h1 style="font-size:60px;">Heading 1</h1>
```

A paragraph always starts on a new line, and is usually a block of text.

A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before and after a paragraph.

The browser will automatically remove any extra spaces and lines when the page is displayed

```
The <hr> tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule.

the HTML <br> element defines a line break.

The HTML <pre> element defines preformatted text.

The HTML style attribute is used to add styles to an element, such as color, font, size, and more.

<tagname style="property:value;">
```


The property is a CSS property. The value is a CSS value.

Use the style attribute for styling HTML elements

Use background-color for background color

Use color for text colors

Use font-family for text fonts

Use font-size for text sizes

Use text-align for text alignment

### HTML Text Formatting

```
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
```

### HTML Quotation and Citation Elements

```
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
```


HTML comments are not displayed in the browser, but they can help document your HTML source code.

You can add comments to your HTML source by using the following syntax:

`<!-- Write your comments here -->`

you can add comment, hide content, Hide Inline Content

`<p>This <!-- great text --> is a paragraph.</p>`

### HTML colors

are specified with predefined color names, or with RGB, HEX, HSL, RGBA, or HSLA values.

text color

Color Names  -> color:red;

140 standard color names

background color

`<h1 style="background-color:DodgerBlue;">Hello World</h1>`

border color

`<h1 style="border:2px solid Tomato;">Hello World</h1>`

rgb

`rgb(255, 99, 71)`

hex

`#ff6347`

hsl

`hsl(9, 100%, 64%)`

`following two <div> elements have their background color set with RGBA and HSLA values, which adds an Alpha channel to the color (here we have 50% transparency):`

rgba

`rgba(255, 99, 71, 0.5)`

hsla

`hsla(9, 100%, 64%, 0.5)`

```
<h1 style="background-color:rgb(255, 99, 71);">...</h1>
<h1 style="background-color:#ff6347;">...</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">...</h1>
<h1 style="background-color:rgba(255, 99, 71, 0.5);">...</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">...</h1>
```


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

### CSS

stands for Cascading Style Sheets.

CSS saves a lot of work. It can control the layout of multiple web pages all at once.

Cascading Style Sheets (CSS) is used to format the layout of a webpage.

With CSS, you can control the color, font, the size of text, the spacing between elements, how elements are positioned and laid out, what background images or background colors are to be used, different displays for different devices and screen sizes, and much more!

The word cascading means that a style applied to a parent element will also apply to all children elements within the parent. So, if you set the color of the body text to "blue", all headings, paragraphs, and other text elements within the body will also get the same color (unless you specify something else)!

CSS can be added to HTML documents in 3 ways:

```
Inline - by using the style attribute inside HTML elements
Internal - by using a <style> element in the <head> section
External - by using a <link> element to link to an external CSS file
```

The most common way to add CSS, is to keep the styles in external CSS files

#### Inline CSS

An inline CSS is used to apply a unique style to a single HTML element.

`<h1 style="color:blue;">A Blue Heading</h1>`

#### Internal CSS

An internal CSS is used to define a style for a single HTML page.

`An internal CSS is defined in the <head> section of an HTML page, within a <style> element.`

```html
<style>
  body {background-color: powderblue;}
  h1   {color: blue;}
  p    {color: red;}
</style>

```

#### External CSS

An external style sheet is used to define the style for many HTML pages.

```
<head>
  <link rel="stylesheet" href="styles.css">
</head>
```

styles.css file :

```css
body {
  background-color: powderblue;
}
```

The CSS color property defines the text color to be used.

The CSS font-family property defines the font to be used.

The CSS font-size property defines the text size to be used.

The CSS border property defines a border around an HTML element.

The CSS padding property defines a padding (space) between the text and the border.

The CSS margin property defines a margin (space) outside the border.

External style sheets can be referenced with a full URL or with a path relative to the current web page.

`<link rel="stylesheet" href="https://www.w3schools.com/html/styles.css">`

```
h1 {
  color: blue;
  font-family: verdana;
  font-size: 300%;
  border: 2px solid powderblue;
  padding: 30px;
  margin: 50px;
}
```

```
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
```

### html links

Links are found in nearly all web pages. Links allow users to click their way from page to page.

HTML links are hyperlinks.

You can click on a link and jump to another document.

When you move the mouse over a link, the mouse arrow will turn into a little hand.

The title attribute specifies extra information about an element. The information is most often shown as a tooltip text when the mouse moves over the element

`<a href="https://www.w3schools.com/" title="go to the w3schools">Visit W3Schools.com!</a>`

By default, links will appear as follows in all browsers:

* An unvisited link is underlined and blue
* A visited link is underlined and purple
* An active link is underlined and red

By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link.

The target attribute specifies where to open the linked document.

The target attribute can have one of the following values:

* _self - Default. Opens the document in the same window/tab as it was clicked
* _blank - Opens the document in a new window or tab
* _parent - Opens the document in the parent frame
* _top - Opens the document in the full body of the window

#### Absolute URLs vs. Relative URLs

Both examples above are using an absolute URL (a full web address) in the href attribute.

A local link (a link to a page within the same website) is specified with a relative URL (without the "https://www" part):

```html
<h2>Absolute URLs</h2>
<p><a href="https://www.w3.org/">W3C</a></p>
<p><a href="https://www.google.com/">Google</a></p>

<h2>Relative URLs</h2>
<p><a href="html_images.asp">HTML Images</a></p>
<p><a href="/css/default.asp">CSS Tutorial</a></p>
```

relative urls

html_iamges.asp is in the root folder asp file

/css/default.asp  in the root folder there are css folder y in there are default.asp file


#### use image as link

```html
<a href="default.asp">
    <img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>
```

#### link to an email address

```html
<a href="mailto:someone@example.com">Send email</a>
```

#### Button as a Link
```html
<button onclick="document.location='default.asp'">HTML Tutorial</button>
```

```
Use the <a> element to define a link
Use the href attribute to define the link address
Use the target attribute to define where to open the linked document
Use the <img> element (inside <a>) to use an image as a link
Use the mailto: scheme inside the href attribute to create a link that opens the user's email program
```

you can applied to link or link button styles :

```html
<style>
a:link {
  color: green;
  background-color: transparent;
  text-decoration: none;
}

a:visited {
  color: pink;
  background-color: transparent;
  text-decoration: none;
}

a:hover {
  color: red;
  background-color: transparent;
  text-decoration: underline;
}

a:active {
  color: yellow;
  background-color: transparent;
  text-decoration: underline;
}
</style>

<style>
  a:link, a:visited {
    background-color: #f44336;
    color: white;
    padding: 15px 25px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
  }

  a:hover, a:active {
    background-color: red;
  }
</style>
```

### html links - create bookmarks

HTML links can be used to create bookmarks, so that readers can jump to specific parts of a web page.

You can also add a link to a bookmark on another page:

```html
<h2 id="C4">Chapter 4</h2>
<a href="#C4">Jump to Chapter 4</a>

<a href="html_demo.html#C4">Jump to Chapter 4</a>
```

### Images

```
The HTML <img> tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.

The <img> tag is empty, it contains attributes only, and does not have a closing tag.

The <img> tag has two required attributes:

src - Specifies the path to the image
alt - Specifies an alternate text for the image
```

The required src attribute specifies the path (URL) to the image.

The width and height attributes always define the width and height of the image in pixels.

However, we suggest using the style attribute. It prevents styles sheets from changing the size of images:

#### Images in Another Folder

If you have your images in a sub-folder, you must include the folder name in the src attribute:

#### Images on Another Server/Website

Some web sites point to an image on another server.

To point to an image on another server, you must specify an absolute (full) URL in the src attribute

#### Animated Images

HTML allows animated GIFs:

```html
<style>
  img {
    width: 100%;
  }
</style>

<img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600">

<img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">

<img src="/images/html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;">

<img src="https://www.w3schools.com/images/w3schools_green.jpg" alt="W3Schools.com">

<img src="programming.gif" alt="Computer Man" style="width:48px;height:48px;">

```

#### Image Floating

Use the CSS float property to let the image float to the right or to the left of a text:

```html
<p><img src="smiley.gif" alt="Smiley face" style="float:right;width:42px;height:42px;">
The image will float to the right of the text.</p>

<p><img src="smiley.gif" alt="Smiley face" style="float:left;width:42px;height:42px;">
The image will float to the left of the text.</p>
```

#### Common Image Formats

Here are the most common image file types, which are supported in all browsers (Chrome, Edge, Firefox, Safari, Opera):


| Abbreviation	| File Format	File                      | Extension                       |
|---------------|---------------------------------------|---------------------------------|
| APNG	        | Animated Portable Network Graphics	  | .apng                           |
| GIF	          | Graphics Interchange Format	          | .gif                            |
| ICO	          | Microsoft Icon	                      | .ico, .cur                      |
| JPEG	        | Joint Photographic Expert Group image	| .jpg, .jpeg, .jfif, .pjpeg, .pjp|
| PNG	          | Portable Network Graphics	            | .png                            |
| SVG           |	Scalable Vector Graphics	            | .svg                            |


```
Use the HTML <img> element to define an image
Use the HTML src attribute to define the URL of the image
Use the HTML alt attribute to define an alternate text for an image, if it cannot be displayed
Use the HTML width and height attributes or the CSS width and height properties to define the size of the image
Use the CSS float property to let the image float to the left or to the right
```

#### HTML Image Maps

With HTML image maps, you can create clickable areas on an image

`The HTML <map> tag defines an image map. An image map is an image with clickable areas. The areas are defined with one or more <area> tags.`

Shape

You must define the shape of the clickable area, and you can choose one of these values:

* rect - defines a rectangular region
* circle - defines a circular region
* poly - defines a polygonal region
* default - defines the entire region

A clickable area can also trigger a JavaScript function.

```html
<img src="workplace.jpg" alt="Workplace" usemap="#workmap">

<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">
  <area shape="circle" coords="337,300,44" alt="Coffee" href="coffee.htm">
</map>

<area shape="poly" coords="140,121,181,116,204,160,204,222,191,270,140,329,85,355,58,352,37,322,40,259,103,161,128,147" href="croissant.htm">


<map name="workmap">
  <area shape="circle" coords="337,300,44" href="coffee.htm" onclick="myFunction()">
</map>

<script>
  function myFunction() {
    alert("You clicked the coffee cup!");
  }
</script>

```

```
Use the HTML <map> element to define an image map
Use the HTML <area> element to define the clickable areas in the image map
Use the HTML usemap attribute of the <img> element to point to an image map
```

#### Background Image on a HTML element

To add a background image on an HTML element, use the HTML style attribute and the CSS background-image property:

`You can also specify the background image in the <style> element, in the <head> section:`

`If you want the entire page to have a background image, you must specify the background image on the <body> element:`

If the background image is smaller than the element, the image will repeat itself, horizontally and vertically, until it reaches the end of the element:

```html
<div style="background-image: url('img_girl.jpg');">

<style>
  div {
    background-image: url('img_girl.jpg');
  }
</style>

<style>
  body {
    background-image: url('img_girl.jpg');
  }
</style>

```

To avoid the background image from repeating itself, set the background-repeat property to no-repeat.

```html
<style>
body {
  background-image: url('example_img_girl.jpg');
  background-repeat: no-repeat;
}
</style>
```

##### Background Cover

If you want the background image to cover the entire element, you can set the background-size property to cover.

Also, to make sure the entire element is always covered, set the background-attachment property to fixed:

This way, the background image will cover the entire element, with no stretching (the image will keep its original proportions):

If you want the background image to stretch to fit the entire element, you can set the background-size property to 100% 100%:

```html
<style>
  body {
    background-image: url('img_girl.jpg');
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: cover;
  }
</style>

<style>
  body {
    background-image: url('img_girl.jpg');
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100% 100%;
  }
</style>
```

##### HTML picture Element

`The HTML <picture> element allows you to display different pictures for different devices or screen sizes.`

```
The HTML <picture> element gives web developers more flexibility in specifying image resources.

The <picture> element contains one or more <source> elements, each referring to different images through the srcset attribute. This way the browser can choose the image that best fits the current view and/or device.

Each <source> element has a media attribute that defines when the image is the most suitable.
```

```html
<picture>
  <source media="(min-width: 650px)" srcset="img_food.jpg">
  <source media="(min-width: 465px)" srcset="img_car.jpg">
  <img src="img_girl.jpg">
</picture>

<picture>
  <source srcset="img_avatar.png">
  <source srcset="img_girl.jpg">
  <img src="img_beatles.gif" alt="Beatles" style="width:auto;">
</picture>
```
> Note: Always specify an <img> element as the last child element of the <picture> element. The <img> element is used by browsers that do not support the <picture> element, or if none of the <source> tags match.

When to use the Picture Element

1. Bandwidth - If you have a small screen or device, it is not necessary to load a large image file. The browser will use the first <source> element with matching attribute values, and ignore any of the following elements.

1. `Format Support - Some browsers or devices may not support all image formats. By using the <picture> element, you can add images of all formats, and the browser will use the first format it recognizes, and ignore any of the following elements.`

#### HTML Favicon

A favicon is a small image displayed next to the page title in the browser tab.

```
To add a favicon to your website, either save your favicon image to the root directory
of your webserver, or create a folder in the root directory called images, and save
your favicon image in this folder. A common name for a favicon image is "favicon.ico".

Next, add a <link> element to your "index.html" file, after the <title> element,
like this:
```

```html
<head>
  <link rel="icon" type="image/x-icon" href="/images/favicon.ico">
</head>

```

all browsers support all images(ico, png, gif jpeg, svg) format as fav icons


#### HTML Tables

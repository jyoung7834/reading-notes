# Images

## Controlling size of images in CSS

You can control the size of an image using the width and height properties in CSS, just like you can for any other box. 

## Aligning Images Using CSS\

The float property can be used to move an element to the left or the right of its containing block, allowing text to flow around it. 

The float property is increasingly being used to alighn images.  There are two ways. 

 * The float property is added to the class that was created to represent the size of the image.

 *  New classes are created with names such as align-left or align-right to aligh the images to the left or right of the page.  These class names are used in addition to classes that indicate the size of the image. 


## Centering Images using CSS

The image should be turned into a block-level element using the display property with a value of block then there are two common ways in which you cn horizontally center an image. 
1)  on the containing element, you can use the text-align property with a value of center. 
2)  On the image itsel, you can use the margin property and set the values of the left and right margins to auto. 

## Adding background images

The background-image property allows you to place an image behind any HTML element.  This could be the entire page or just part of the page.  By default, a backgroud image will repeat to fill the entire box.  The path to the image follows the letters url, and it is put inside parentheses and quotes. 

`body, p, etc. {
  background-image:  Url("images/pattern.gif");
}`

## Repeating Images
### background-repeat
### background-attachment

The background-repeat: property can have four values:

- Repeat
- repeat-x
- repeat-y
- no-repeat
- no-repeat
- fixed
- scroll

backgroud-position:

- left top
- left center
- left bottom
- center top
- center center
- center bottom
- right top
- right center
- right bottom

### Shorthand
#### backgound

background:
background-color
background-image
background-repeat
background-attachment
background-position

### Image Rollovers & sprites

`#gradient {
  background-image:  -webkit-linear-gradient(#XXXXXX, #XXXXXy);
}

* You can specify te demensions of images using CSS.  This is very helpful when you use the same sized images on several pages of your site. 

* Images can be aligned both horizontally and vertically using CSS

*You can use a background image behind the box created by an element on a page. 

*Background images can appear just once or be repeated across the background of the box. 

*  You can create image rollover effects by moving the background position of an image

*  To reduce the number of images your browser has to load, you can create image sprites. 

### Practical Information

> Search engine optimization helps visitors find your sites when using search engines. 

> Analytics tools such as Google Analytics allow you to see how many people visit your site, how they find it, and what they do when they get there. 

> To put your site on the web, you will need to obtain a domain name and web hosting. 

> FTP programs allow you to transfer files from your local computer to your web server. 

> Many companies provide platforms for blogging, email newsletters, e- commerce and other popular website tools (to save you writing them from scratch). 









# AJAX & JSON
Ajax is a technique for loading data into part of a page without having to refresh the entire page.  The data is often sent in a format called JavaScript.

* Ajax refers to a group of technologies that allow you to update just one part of the page (rather than reload a whole page).

* You can incorporate HTML, XML, or JSON data into your pages. (JSON is becoming increasingly popular.)

* To load JSON from a different domain, you can use JSONP but only if the code is from a trusted source. 

* JQuery has methods that make it easier to use AJax.

* .load() is the simplest way to load HTML into your pages and allow you to update just a part of the pages. 

* .ajax() is more powerful and more complex.  (Several shorthand methods are also offered.)

*  It is important to consider how the site will work if the user does not have JavaScript enabled, or if the page is not able to access the data from a server. 
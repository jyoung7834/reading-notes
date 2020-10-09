# Read 04 HTML Links, CSS Layout, JS Functions

## Chapter 4 Links (pp 74-93)

### Writing Links
Links are created using the `<a>`element.  Users can click on anything between the opening `<a>` tag and the closing `</a>` tag.  You specify which page you want to link to using the href attribute. The link between each tag is known as link text. 

`<a href="http://www.imdb.com">IMDB</a>`

### Linking to other sites
When you link to a different website, the value of the href attribute will be the full web address for the site, whis is know as an **absolute** URls
`<a href="http://www.imdb.com">IMDB</a>`

### Creating links between pages
When you are linking to other pages within the same site, you do not need to specify the domain name in the URL.  You can use a shorthand known as a relative URL. 
`<a href="name of the page">IMDB</a>`

### Email links
When you are linking to an e-mail address you will use the 
`<a href="mailto: xxxxxxx@xxx.com>Jon Doe email</a>`

### Opening Links in a New Window
If you want to link to open in a new window, you can use the target attribute on the opening `<a>` The value of this attribute shoud be _blank.
`<a href="http://www.imdb.com" target=_blank>IMDB</a>`

### Linking to a Specific Part of the Same Page 
You will use an id attribute "id="top" in the tag you would like to link to.  

Your link will look like `<a href="#top">Top</a>`

### Linking to a Specific Part of Another Page. 
href attribute will contain the address for the page (either an absolute URL or a relative URL), followed by the # symbol, followed by the value of the id attribute that is used on the element your are linking to.

## Summary Links
- Links are created using the `<a>` element.
- The `<a>` element uses the href attribute to indicate the page you are linking to. 
- If you are linking to a page within your own site, it is best to use relative links rather than qualified URLs. 
- You can create links to open email programs with an email address in the "to" field. 
- You can use the id attribute to target elements within a page that can be linked to. 

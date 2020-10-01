# Chapter 2 - Text (pp. 44-61)
  - Headings and Paragraphs
    - `<h1>` is used for main headings

    - `<h2>` is a level 2 heading and so on.

    - `<p>` A paragraph consists of one or more sentences that form a sel-contained unit of disclurse.

  - Bold, italic, emphasis
    - `<b>` bold
    - `<i>` italic
    - `<sup>` on the 4`<sup>`th`</sup>` shows up as the 4<sup>th</sup> 
    - `<sub>` H<sub>2</sub>O
  - Structural and semantic markup 
    - White Space 2 or more spaces is treated like a single space.  Two or more line breaks displays a single space as well.

  - Line Breaks & Horizontal Rules
    - `<br/>` line break
    - `<hr/>` horizontal rule 

  - Semantic Marup - add extra information to the pages.
    - Strong & Emphasis
      - `<strong>` simular to bold
      - `<em>` simular to italic
    
    - Quotations
      - `<blockquote>` indents the whole sentence or phrase
      - `<q>` is used for shorter quotes that sit within a sentence. 

    - Abbreviatins & Acronyms
      - `<abbr>` used for an appreviation or acronyms

      - `<cite>` when you are referencing a piece of work such as a book. simular to italic. 
      - `<dfn>` defining instance is used the first time you explain some new terminology.  simular to italics in some browsers. 

    - Author Details
        - `<address>` italics

    - Changes to Content
      - `<ins>` place to show when content has been inserted.  It will underline. 
      - `<del>` place to show when contend is deleted.  This will show with a line through. 
      - `<s>` when something should be removed but not deleted.  This show with a line through.  

HTML elements are used to describe the structure of the page (e.g. headings, subheadings, paragraphs).

They also provide semantic information (e.g. where emphasis should be placed, the definition of any acronyms used, when given text is a quoation).



# Chapter 10 Introducing CSS (pp.226-245)

- What CSS does
- How CSS works
- Rules, properties, and values

- Understanding CSS;  Thinking Inside the Box

  - CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented. 

  CSS Associates Style Rules with HTML Elements

  - Selector `<p>` indicate which element the rule applies to.  The same rule can apply to more than one element if you separate the element names

  - Declaration `{font-family:  Arial;}` indicate how the elements referred to in the selector shouldbe styled.  Declarations are split into two parts (a property and a value), and are separated bya a colon. 

CSS Properties Affect How Elements are Displayed. 
  - CSS declarations sit inside curly brackets and each is made up of two parts:  a property and a value, separated by a colon.  You can specify several properties in one declaration, each separated by a semi-colon. 

  ` h1, h2, h3 {
    font-family: Arial;
    color: yellow;}
    property | Value`

Using external CSS

`<link>`, href, type, rel

Using internal CSS
`<style>`

CSS selectors (see pg 238)

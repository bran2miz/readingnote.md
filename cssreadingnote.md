# Design Web Pages with CSS

## CSS

**CSS**- Cascading Style Sheets
- stylized way of creating beautiful and exciting web pages.
- how a document is seen on the page.

### Document 
- Text-based and uses mark-up language

**Presenting** a document
- Modifying a document to make the page easily visible for everyone.

### CSS  is a rule based language
- Defines rules on how certain elements should be on your website.

### Selector
- Essentially the *selector* in CSS is equivalent to an opening tag in HTML.

>ie h1 {
>        color: red;
>        font-size: sem;
>      }

### Declarations
- what stylistic changes the user wants to be implemented.
- These changes are made using *brackets* 
- Changes made in the brackets are through **property** and **value pairs**.

#### Property
- defines the modification

#### Value
- specifications of that modification
- various size units

#### CSS Specfication

- Documents that define standard web text. 

## Ways to Insert CSS

### 1. External CSS
- one file can alter the entire website. 
    - reference tag for CSS.

### 2. Internal CSS
- used if a particular part of the website is different.
    - use CSS by utilizing the style element: < style>

### 3. Inline CSS
- used to make a particular element-style altered.

> ie < h1 style="color:blue; text-align= "center"> This is a heading < /h1>
- *Use this method sparingly* 

## Multiple Style Sheets

An occurance can happen when there are two different style sheets for the same content. 
    - The last read style sheet supersedes the original.
    - However the internal style element will supersed the external style element if defined after.

[<== Back](README.md)

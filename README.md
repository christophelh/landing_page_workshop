## Background & Objectives
A simple challenge to create a basic HTML landing page with CSS 
A picture is worth a thousand words, so here is what we'll build today ....
https://christophelh.github.io/landing_page_workshop/



## About HTML

- HTML stands for Hyper Text Markup Language

- HTML is the standard markup language for Web pages

- HTML elements are the building blocks of HTML pages

- HTML elements are represented by <> tags


### HTML Skeleton

HTML Boilerplate to use when you are starting a new project.

```
<!DOCTYPE html>
<html>
  <head>

    <!-- Page's intelligence = meta tags -->

  </head>
  <body>

    <!-- Page's content = displayed on the page -->

  </body>
</html>
<!-- end of file -->
```


### HTML Skeleton - Head

The <head> element is a container for metadata (data about data) and is placed between the <html> tag and the <body> tag.

HTML metadata is data about the HTML document. Metadata is not displayed.

Metadata typically define the document title, character set, styles, scripts, and other meta information.

The following tags describe metadata: <title>, <style>, <meta>, <link>, <script>, and <base>.


```
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title. Maximum length 60-70 characters</title>
    <meta name="description" content="Page description. No longer than 155 characters.">
    <meta charset="utf-8">
  </head>
  <body>

  </body>
</html>
<!-- end of file -->
```


### HTML Skeleton - Body 


The <body> tag defines the document's body.

The <body> element contains all the contents of an HTML document, such as text, hyperlinks, images, tables, lists, etc.

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Hello world</title>
  </head>
  <body>
    <h1>Hello buddies!</h1>
  </body>
</html>
<!-- end of file -->
```

## HTML Elements


### HTML Syntax

![Linking HTML](https://github.com/christophelh/landing_page_workshop/blob/master/htmlsyntax.png)

Exemple 

```
<a href="https://www.opentechcamp.com" target="_blank">
  Learn to code the best way possible 👨🏽‍💻
</a>
```

### Titles

```
<h1>[... Your Title ....]</h1>  <!-- Only one per page! SEO important -->

<h2>[... Your TagLine ... ]</h2>
<h3>[...]</h3>
<h4>[...]</h4>
<h5>[...]</h5>
<h6>[...]</h6>

```

### Paragraphs

```
<p>
  Lorem ipsum dolor sit amet, consectetur adipisicing elit.
  Veritatis laboriosam mollitia autem at ab omnis iure quis
  asperiores inventore eos nam aut iusto officiis deserunt
  nihil, sequi tempore impedit quae?
</p>
```

### Emphasize

```
<p>
  You can emphasize <em>some words</em>,
  and even <strong>more if needed</strong>
</p>


```

### List

```
<h2>Shopping List</h2>
<ul>
  <li>Milk</li>
  <li>Butter</li>
</ul>

```

### Images

```

<img src="logo.png" alt="Company Logo">
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/ic

```


### Forms

```

<form>
  <input type="email">
  <input type="password">
  <input type="submit" value="Log in">
</form>

```


### Live Code (20min)

### Setup 

- Create a folder called `workshop` on your desktop
- Open the folder within your code editor
- Create a file called `index.html`


### Instructions 

- Build a simple HTML Medium article page with the following elements (use the right HTML tags):


- Start with a HTML Skeleton 
- Add a page title within the `<head> </head> `
- Within the body tag `<body> </body>` 
  - Add a picture
  - Add a button 
  - Add a H1 tag 
  - Add Multiple h2 tags
  - Write paragraphs after each H2

A picture is worth a thousand words, so here is what you should build in this challenge
[Example](https://medium.com/@Skyscanner/everybody-can-write-code-dd6adbe0bc9)



## CSS

- CSS stands for Cascading Style Sheets
- CSS describes how HTML elements are to be displayed


### Linking stylesheet to HTML page

You have to link your `CSS` to your `HTML` File.

![Linking HTML](https://github.com/christophelh/landing_page_workshop/blob/master/linking.png)

### CSS Syntax

![CSS Syntax](https://github.com/christophelh/landing_page_workshop/blob/master/csssyntax.png)


### CSS Vocabulary 

![CSS Vocabulary](https://github.com/christophelh/landing_page_workshop/blob/master/cssvocabulary.png)

### CSS Example

![Example](https://github.com/christophelh/landing_page_workshop/blob/master/cssexemple.png)


### Colors

[Website to choose your colors](https://coolors.co/browser/latest/1)


```
color: #FF530D;
color: rgb(255, 83, 13);
color: rgba(255, 83, 13, 1.0);
```

### Background Color

```
body{
  background-color: white;
 }
 ```

### Text Color

```
h1 h2 p{
  color: grey;
 }
 ```
 
 ### Background image
 

```

body{
  background-image: url(landcape.png)
}
 
 ```

### font-family

```
h1 h2 p{
  font-family: Times, serif;
}
 
h1 h2 p{
  font-family: Arial, serif;
}
 
```


### Include Google-font library to your website

Fonts - Google fonts
[Make your shopping on Google fonts](https://fonts.google.com/)

```

<head>
  ...
  <link href="https://fonts.googleapis.com/css?family=Roboto&display=swap" rel="stylesheet">
  ...
</head>
```


 
### Fonts - weight

```

h1 h2 p{
  font-weight: bold;
}

```
 
### Live Code (10 min)

### Setup 

- create a file called `style.css`
- link your `style.css` to your `index.html`


### Instructions 

- Add a grey background color to your `body`
- Apply a Open-Sans font to your `h1` and `h2`
- Apply a Montserrat font to your `body`
- Change the color of your button 
- Change the color & text-decoration of all the links


## DIV & Box Model 

All HTML elements can be considered as boxes. In CSS, the term "box model" is used when talking about design and layout. The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. ... Margin - Clears an area outside the border.

![Box Model ](https://github.com/christophelh/landing_page_workshop/blob/master/boxmodel.png)




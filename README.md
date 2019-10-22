## Background & Objectives
A simple challenge to create a basic HTML landing page with CSS 
A picture is worth a thousand words, so here is what we'll build today ....
https://christophelh.github.io/landing_page_workshop/

## Setup 

- Create a folder called coding workshop on your desktop
- Open your code editor 
- Create a file called index.html the folder you created


## About HTML

![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/600px-HTML5_logo_and_wordmark.svg.png)



- HTML stands for Hyper Text Markup Language

- HTML is the standard markup language for Web pages

- HTML elements are the building blocks of HTML pages

- HTML elements are represented by <> tags

### HTML Skeleton

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

### Titles

```
<h1>[...]</h1>  <!-- Only one per page! SEO important -->

<h2>[...]</h2>
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


# Introduction to Programming
## Usages
1. Software Development
2. Web Development
3. Machine Learning
4. Artificial Intelligence

## Web Development
1. Content Management System
2. Programming

### Content Management System
- No developer control
- Faster
Eg. Wordpress, Hugo

### Programming
- Developer Control
- Slower
Languages: HTML, CSS, JS, TS,.....

# Computer Languages
1. Markup Languages
2. Programming Languages

## Markup Languages
Languages that do not perform calculation

Eg. HTML, XML, TOML, PPTX, DOCX, XLSX

## Programming Languages
Languages that perform calculation

1. Static Language
2. Dynamic Language

### Static Language
1. A language that necessary to show datatype is called static languages

### Dynamic language
2. A language that doesn't necessary to show datatype is called dynamic language

# HTML
HTML: Hyper Text Markup Language
A Langugae that manages the element of the websites

## index.html
A default html file for home page

## Website vs Webpage
Website contains multiple webpages where as webpage is only a single page of website.

## Typography
### Headers

```html
    <h1>Hello World</h1>     <!-- Header 1 -->
    <h2>Hello World</h2>    <!-- Header 2 -->
    <h3>Hello World</h3>    <!-- Header 3 -->
    <h4>Hello World</h4>    <!-- Header 4 -->
    <h5>Hello World</h5>    <!-- Header 5 -->
    <h6>Hello World</h6>    <!-- Header 6 -->
```

### Texts
```html
    <p>Hello World</p> <!-- paragraph-->
    <b>Hello World</b>  <!-- bold-->
    <i>Hello World</i>  <!-- itallic-->
    <u>Hello World</u>  <!-- underlined-->

```

# Styles
Cascading Style Sheets
**Styling HTML elements**
written in style attribute


## Display Properties
### display: block;
- takes full width
```html
    <!--Block elements-->
    <h1>Hello World</h1>
    <h2>Hello World</h2>
    <h3>Hello World</h3>
    <h4>Hello World</h4>
    <h5>Hello World</h5>
    <h6>Hello World</h6>
    <p>Hello World</p>
```
### display: flex;
- does not take full width, give the space to element next to it
```html
<!-- flex elements -->
    <b>Hello World</b>
    <i>Hello World</i>
    <u>Hello World</u>
```

## Color
1. Text color
2. Background color

### Text Color
Color of the text, can be define with 'color' cascade.
```html
        <b style="color: red; ">Hello World</b>
```

### Background Color
Color of Background, can be define with 'background-color' cascade.

```html
    <b style="background-color: aqua;">Hello World</b>
```

# Images
'img' tag includes 2 attributes.
1. src (source)
2. alt (alternative)

## src
source of image
2 types of path to find source
1. absolute path
2. relative path

### absolute path
Define specific path of the file
Example:
```
    C:\Users\DELL\Desktop\Batch5Programming\Lesson1\assets\cat.jpg
```

### relative path
Do not define the full path. Display the paths using dots

``` 
./assets/cat.jpg
```

## alt
Name of the image
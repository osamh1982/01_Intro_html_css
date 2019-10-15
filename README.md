![GeneralAssemb.ly](https://media.git.generalassemb.ly/user/19273/files/dd69e280-400c-11e9-9578-20ebfc4e5812)

# FEWD-JED

### Class 1 -

***

### Objectives
- Review Git / Github
- Review our Git process and submission of assignments
- Set up our IDE's - Individual Development Environments
- Describe the anatomy of a web page and create the basic structure of a page in HTML
- Apply basic HTML tags to page content
- Introduction to CSS Basics

***


### Git & Github

##### What is Git / Github?
- Git is a distributed version-control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. Its goals include speed, data integrity, and support for distributed, non-linear workflows.
- GitHub is a that platform makes it easy to manage git repositories.
- Stores files like Dropbox or Google Drive, but stores code.
- Stores a history of files and the changes that happens within each changed document.
- Hosts files on the cloud so you can share the finished product with other people.
- Git - the technology that Github is based on top of - was designed to allow for multiple engineers to work on the same project.

##### Why is GitHub Valuable? Why do developers use GitHub?
- Since GitHub stores a history of the code, it allows developers to go back in time if something breaks.
- GitHub allows multiple developers to work on the same project. Much like Dropbox or Google Drive lets multiple people collaborate on the same document, GitHub allows this for code.
- GitHub tracks changes so you can see who worked on what.
- GitHub allows for feedback to be given on the code, which hopefully, increases code quality. Much like an editor updates a Word document using Track Changes, GitHub allows a similar environment.

##### How does GitHub work in a collaborative environment?
- Each GitHub project is called a "repository". Engineers joining a team start by "cloning" the repository (or repo, for short). <em>Remember: "Clone" means that we are copying our GitHub repository from the cloud and saving it as a local folder on our computer.</em>
- The main, stable version of the codebase is on the default "branch" in GitHub which is called "master". <em>Engineers typically create new branches for certain features or portions of the code they will work on, but we won't be creating branches in this class in this class.</em>
- As engineers are working on a project, they "add" and "commit" their changes. This establishes a saved version of a project and creates a history of what they are working on. With these saved versions, engineers are able to revert to an earlier version if an issue arises that cannot be fixed.
- If there are multiple engineers working on a project, other engineers can review the code that is committed and provide feedback. For this class, the instructors will be reviewing and providing feedback on your code.
- We will be working with our own default "master" branch for each of our projects.

***

### GitHub Setup

#### Follow Along!

***


### Setting up your IDE

#### Choosing an IDE

- Sublime Text3 will frequently ask you to purchase before proceeding to save your life
- Both <a href="https://atom.io/">Atom</a> and <a href="https://code.visualstudio.com/">Visual Studio Code</a> are free and also great editors
- I will be using Atom so if you want to ensure consistency, you should too but it's your call

#### File Structure
- <strong>Do Not Use</strong> spaces, caps, or special characters to name files or folders
- Always create a new folder for each new website you're creating
- Create a folder for your images inside the website folder (conventionally, we name it <strong>images</strong>).
- Create a folder for your css files inside the website folder (conventionally we name it <strong>css</strong> or <strong>styles</strong>
- Your HTML files goes directly into the website folder

#### The Index File

- Your homepage should <strong>always</strong> be named index.html
- The index.html is special. By default, a web server will look for a file that is named index so it knows which file to send when there is no file name specified

***

### How the internet works
[How the internet Works](https://www.youtube.com/embed/kBXQZMmiA4s)

#### How do Web Pages Work?
    -   HTML
    -   CSS
    -   JavaScript

#### HTML
Hyper Text Markup Language
- HTML provides the structure of a webpage - think of it as the skeleton and bones

#### CSS
Cascading Style Sheets
- CSS defines how the webpage should look - think of it as the color of eyes, skin color, height, gender, etc

#### JavaScript
- JavaScript adds interactivity and logic -  think of it has how to walk, talk, etc.
- *JavaScript IS NOT THE SAME as Java!!!*

#### History of Web Technologies
![timeline_of_web_technologies](https://media.git.generalassemb.ly/user/19273/files/ce9ee800-3de0-11e9-85f7-15e3ac178fc3)

***

### HTML Basics

#### HTML Syntax

![tags](https://media.git.generalassemb.ly/user/19273/files/20943d80-3de2-11e9-86b8-2b6a2b457f4a)

- <strong>HEADS UP:</strong> Some tags only have a start tag

#### Adding Attributes
![tags_attributes](https://media.git.generalassemb.ly/user/19273/files/43beed00-3de2-11e9-8ae3-6096d03a8fe1)


#### Whats up DOC?
- This doctype tells the browser to treat everything that follows as HTML5
- Case-insensitive but conventionally written as

```html
<!DOCTYPE html>
```

#### Anatomy of a Webpage

- Every HTML page has the same foundational structure

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>Page Title</title>
    </head>
    <body>

        <!-- Page content goes here -->
    </body>
</html>

```

### Content Tags

#### Heading Tags

```html
<h1>Header one</h1> <!-- 200%  base font-size -->

<h2>Header two</h2>

<h3>Header three</h3>

<h4>Header four</h4> <!-- base font-size -->

<h5>Header five</h5>

<h6>Header six</h6> <!-- 67%  base font-size -->

```

#### Text Elements

```html
<p>Paragraph Tag</p>
<blockquote>This is a block quote</blockquote>
```

#### Unordered List
```html
<ul>
    <li>List Item</li>

    <li>Another List item</li>
</ul>
```

#### Anchor Tag (Links)

```html
<a href="url-or-link-to-page">Link</a>
```

***

## Code Along
![code_along](https://media.git.generalassemb.ly/user/19273/files/40c4fc00-3de4-11e9-94f7-6f779d726056)

[Press Release](https://git.generalassemb.ly/berziiiii/FEWD-BOS-37/tree/master/Week_01/01_html_basics/starter_code/ga_press_release)

***

### Additional HTML elements

#### Block Elements
- Block elements <strong>block</strong> other elements from sitting next to them.
```html
<p>I am a  block element</p>

<div>I am also a block element</div>
```

#### Inline Elements
- Inline elements <strong>wrap</strong> inside their containing elements.
```html
<p>
 Both a <span>span</span> and
 a <a href="link">anchor</a>
 are inline elements
</p>
```

#### Webpage building blocks
- <strong>header:</strong> used for repetitive elements at the top of the page such as branding and menus.
- <strong>nav:</strong> used to wrap any kind of navigation menu.
- <strong>main:</strong> used for the main content of the page.
- <strong>aside:</strong> used for ancillary content.
- <strong>article:</strong> used for articles, blog posts and similar content.
- <strong>section:</strong> a general purpose section commonly wraps divs.
- <strong>div:</strong> a general purpose section (division).
- <strong>footer:</strong> used to wrap the page footer contents.

<strong>HEADS UP:</strong> Don't confuse <strong>header</strong> with <strong>head</strong>.

#### Helpful Inline Tags
- <strong>span:</strong> a general purpose tag.
- <strong>strong:</strong> used to add weight (replace the b tag).
- <strong>em:</strong> used to add emphasis(replaced the i tag).
- <strong>a:</strong> anchor tags creating links to different content on the page or external pages on the web.
- <strong>code:</strong> used to wrap example code.
- <strong>img:</strong> the img (image) tag is a little but of both, but technically inline!

For more details, see [Block-level Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements) and [Inline-level Elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Inline_elements) on MDN.

#### Don't Forget These
- What you name your files matters. Your home page <strong>must</strong> be name index.html.
- Use lowercase <strong>exclusively</strong> in HTML and CSS. The only exception should be in the DOCTYPE.
- Always create a new folder for each exercise and don't co-mingle files.

***

### Lab
![lab](https://media.git.generalassemb.ly/user/19273/files/250e2580-3de5-11e9-9d7c-356b23c70c24)

[Cookie Recipe](https://git.generalassemb.ly/berziiiii/FEWD-BOS-37/tree/master/Week_01/01_html_basics/starter_code/cookie_recipe)

***

### CSS Basics


#### Selectors, Properties, Values - Oh My!

```css
selector {
    property: value
}
```

#### CSS Selectors

Selectors <strong>target</strong> the elements you want to style. They can be:

- <strong>Element Tags</strong>
- Classes & IDs Attributes
- Pseudo Classes
- Combinations

#### Properties

Properties are the styles you want to apply to the targeted elements:

- border
- color
- background-color

#### Values

<strong>Acceptable Values</strong> are specific to the property:

- border has values for the width, color and style
- color and background-color accept a color value

#### Style Tag

CSS <strong>can</strong> be added to your HTML page with a style tag

```html
<html>
    <head>
        <style>
            h1 {
                color: blue
            }
        </style>
    </head>

    <body>
        ...
    </body>
</html>
```

#### CSS Example

```html
<style>
    h1 {
        color: blue;
        font-family: sans-serif;
    }
    h2 {
        color: red;
        font-family: sans-serif;
    }
    body {
        background-color lightgray;
        font-family: sans-serif;
        border: 5px solid black;
        padding: 10px;
    }
</style>
```

#### Color Properties

The <strong>color</strong> property sets the font color
```css
/* Make the fonts one the page blue */

body {
    color: blue;
}
```
The <strong>background-color</strong> property sets the fill color

```css
/*  make the page red */

body {
    background-color: red;
}

```

#### Border Properties

```css
/* Border is shorthand for:
 border-width
 border-style
 border-color */

ul {
    border: 1px solid darkgray;
}
```

#### Font Properties

```css
/* 'font' is shorthand for:
font-style, font-variant, font-weight,
font-size, line-height, font-family */

p {
    font-family: sans-serif;
    font-size: 30px;
}
```
<strong>HEADS UP:</strong> The shorthand for font requires at least the font-family and font-size, and font-family must appear last.

***

### Code Along
![code_along](https://media.git.generalassemb.ly/user/19273/files/40c4fc00-3de4-11e9-94f7-6f779d726056)

[CSS Basics](https://git.generalassemb.ly/berziiiii/FEWD-BOS-37/tree/master/Week_01/01_html_basics/starter_code/ga_press_release)


***

### External Stylesheets

#### Linking Files
```html
<head>
    ...
    <link rel="stylesheet" href="css/styles.css">
    ...
</head>

```
<strong>HEADS UP:</strong> No style tags are used!

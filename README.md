Hello there! If you're reading this, chances are you're taking my beginner's workshop on HTML, CSS and prepping to create your very first webpage!

# Welcome!

Today you will learn:
 - Use a text editor to author an HTML page
 - Use tags to denote paragraphs, emphasis or type
 - Create hyperlinks to other webpages
 - Add images to your page
 - Customize your page with colors, fonts and icons.

# HTML

> Hypertext Markup Language
The set of markup symbols or codes inserted in a file intended for display on a World Wide Web browser page. The markup tells the Web browser how to display a Web page's words and images for the user.

**Tags** - HTML element names surrounded by angle brackets
(usually in pairs)

>example: <p> </p> OR <body> </body>

**Elements** - Everything from the start tag to the end tag
example: <p>My Very First Webpage</p>

**Attributes** -  Additional information about HTML elements
(always specified in the start tag)

>example: <p class="about-me">"All About Me"</p>

Today we are going to use Semantic HTML to assist us in laying out our page. Semantic HTML is the use of HTML markup to reinforce the meaning, of the information in webpages and web applications rather than merely to define its presentation or look. For example, we will use <section></section> tags to refer to specific sections of our page.

Here are some HTML resources:
 - [Semantic HTML Tutorial] (https://codepen.io/mi-lee/post/an-overview-of-html5-semantics)
 - [MDN HTML resources] (https://developer.mozilla.org/en-US/docs/Web/HTML)
 - [MDN HTML beginners tutorial] (https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)

### CSS

> Cascading Style Sheet
Describes how HTML elements are displayed on a page and controls page layout.

**External Style Sheet** - Used to define the style for multiple pages. With an external style sheet, you can make easy changes to your webpage style in one file.

**Linking your CSS file** - The CSS file and HTML file need to speak to each other in order to render style.

```sh
<head>
 <link rel="stylesheet" href="styles.css">
</head>
```

**Typical format in a CSS Style Sheet** - Elements can have style applied without an id or class. Id's are used once in an application and are denoted by a '#' in front of the id name. Classes can be used by multiple elements and are denoted by a '.' in front of the class name.

```sh
body {
  background-color: pink;
}
.about-me {
  width: 600px;
}
.nav-bar {
  color: blue;
}
```

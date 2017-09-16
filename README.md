Hello there! If you're reading this, chances are you're taking my beginner's workshop series on HTML, CSS and prepping to create your very first webpage!

# Welcome to Part 1!

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

```sh
example: <p> </p> OR <body> </body>
```

**Elements** - Everything from the start tag to the end tag

```sh
example: <p>My Very First Webpage</p>
```
**Attributes** -  Additional information about HTML elements
(always specified in the start tag)

```sh
example: <p class="about-me">"All About Me"</p>
```

Here are some HTML resources:
 - [MDN HTML resources] (https://developer.mozilla.org/en-US/docs/Web/HTML)
 - [MDN HTML beginners tutorial] (https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)
 - [HTML Cheat Sheet] (http://www.hostingreviewbox.com/wp-content/uploads/2016/02/html5-cheat-sheet-1.png)

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

Here are some CSS resources:
 - [MDN CSS] (https://developer.mozilla.org/en-US/docs/Web/CSS)
 - [MDN CSS beginner's basic tutorial] (https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)
 - [CSS Layouts] (http://learnlayout.com/inline-block.html)
 - [CSS Cheat Sheet] (https://www.smashingmagazine.com/wp-content/uploads/images/css3-cheat-sheet/css3-cheat-sheet.pdf)

 Here are some other resources:
  - [Font Awesome] (http://fontawesome.io/icons/)
  - [Google Fonts] (https://fonts.google.com/)
  - [Coolors Themes] (https://coolors.co/browser/latest/1)


# Welcome to Part 2!

Today you will learn (and expand upon) the following:
 - Semantic HTML layout
 - CSS: Box-shadowing, Border-radius
 - Add multiple images to your page
 - Customize your page with colors, fonts and icons.
 - Deploy your site using Heroku

If you are here for the first time, take the time to go through the above content in Part 1. As always, please reach out if you have any questions or concerns!

**Semantic HTML** - HTML markup used to reinforce the meaning behind information on webpages rather than just by appearance. It gives the developer insight to the content on the page and how it should be organized.

Here are some HTML resources:
 - [Semantic HTML Tutorial] (https://codepen.io/mi-lee/post/an-overview-of-html5-semantics)
 - [Semantic HTML Resource] (https://internetingishard.com/html-and-css/semantic-html/)
Header/Footer
 - Can define the entire document, or a specific section.
Section
 - Defines a section of a document. Usually is organized based on a common theme. One section can have multiple paragraphs and usually is preceded with a header.
Article
 - Defines an independent set of content such as a news article or blog post. Ask yourself: Can this content be read independently of everything on my page?
Aside
 - Defines content aside from the content it is placed in. Think a sidebar.
Figure/Figcaption
 - A caption for an image/diagram.

 Now let's give it a try. Copy the code in the semantic.html file and let's create our own semantic HTML page!

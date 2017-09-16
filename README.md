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
 - Semantic HTML layout to build a resume page
 - Link multiple pages to your site
 - CSS: Box-shadowing, Border-radius
 - Add multiple images to your pages
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

 Now let's give it a try. Copy or open the code in the semantic.html file and let's create our own semantic HTML resume page!

 In this page we will work on the following:
 - Use Semantic HTML to separate content on a resume page
 - Link our resume page to our homepage
 - Use external links to social media
 - Insert a picture
 - Insert a table
 - Use CSS to style our resume page

 **Tables in HTML**

 If you've ever used Microsoft Excel, you may be familiar with tables. Tables are made up of rows and columns. Rows and columns are typically denoted by headers and contain cells. Cells contain data. Tables in HTML are quite similar, but take a specific format. Today you will learn how to build your own table and how to style it appropriately.

 - A table is formulated in HTML with opening and closing <table> </table> Tags.
 - Table Rows are denoted by opening and closing <tr> </tr> Tags.
 - Table Headers, or column headers are denoted by opening and closing <th> </th> Tags. It is important that table header tags go inside of a table row.
 - Table Data, or cell content is denoted by opening and closing <td> </td> tags. <td> stands for Table Data.

 The main thing to consider when making a table is to apply appropriate padding to your <tr></tr> and <td></td> tags.

 th, td {
    padding: 1.5px;
}

 Another thing to consider when making a table is whether or not you want borders (or the grid) to divide you table.

 To use borders or a grid on your table, you can structure your CSS like so:

 table, th, td {
    border: 1px solid black;
}

To only have one border around the entire table, you can structure your CSS like so:
table, th, td {
    border: 1px solid black;
    border-collapse: collapse;
}

**Deploying your site to Heroku**

What is Heroku?
 - Heroku is a cloud platform as a service (PAAS) that is used as a web application deployment model. Developers can easily deploy their applications so that customers and the public can easily access.

Checklist of things you will need:
1. Go to (https://signup.heroku.com/) and sign up for a FREE account on Heroku
2. Make sure you can access your computer's command line (if you are using a mac, terminal)
2. Once you have these, you can follow along with the tutorial here: (https://devcenter.heroku.com/articles/getting-started-with-nodejs#set-up)

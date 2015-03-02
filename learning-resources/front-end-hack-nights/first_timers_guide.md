## WWCDC Front End Hack night first timer's guide

### What is Front End?

When someone says “frontend” of the web, what they really mean is the part of the website or web application that a person can visually see and interact with. As the name states “Front-End” is the part of the code that is on the front of the application. The main purpose of the front-end code is to interact with user, as well as present the data in a well-defined style, and structure. It usually consists of two parts: 

* the design - aesthetics of the website or application, understanding element arrangements on the screen, the color and font choices

* front end web development or client-side development- development of those elements of a website that the user sees and interacts with directly. This piece involves programming skills, comprising mainly of **HTML**, **CSS**, and **Javascript** but certainly not limited to them.

### What is Front End Development?

The focus of this study group is **Front End Development**, we appreciate designers to join and share their wisdom, but the purpose of the group is to encourage every one to code. 

A front end developer is the bridge connecting the designer and the back end developer. A web designer creates visual design and layout of the website,  the web developer takes that design and vision from a static design to a fully working website that is online and available to the world. A back-end developer builts the underderlying architecture and functionality of the app around it. 

Almost all the elements that you see, and interact with on any website is a mixture of HTML, CSS, and JavaScript, which are all controlled by the browser. For example, if you’re using Google Chrome, Firefox or Safari, the browser is what translates all of the code in a manner for you to be able to see, and interact with. Such as fonts, colors, drop-down menus, images, forms, etc. 

### What tools do I need?

* Laptop/PC: Front end development is not restricted by the machine you are using, you can start coding on PCs, Macs, or Linux machines. 

* Text Editor: we donot and should not code in regular word processors, you would need user-friendly text editors that does syntax highlighting. These are some that we recommend:
  * [Sublime Text](http://www.sublimetext.com/)
  * [TextWrangler](http://www.barebones.com/products/textwrangler/) - MAC only
  * [Notepad++](http://notepad-plus-plus.org/)
  
* Git and GitHub: Version control is a really important part of any professional developer's toolkit. It helps with backing up your work, collaboration, and managing changes through iterative versions. You would need Git installed on your computer, and an account on [Github](https://github.com). For an introduction to Git and Github, refer our [Intro to Git presentation](http://nupurkapoor.github.io/intro-to-git/#/)

* [JSFiddle](http://jsfiddle.net/): An online custom environment to test your HTML, CSS, and Javascript. You can save the fiddles you create and share them with others. Refer [official docs](http://doc.jsfiddle.net/tutorial.html).

* Dedication, Patience and Support from each other! 

### Basics

There are many technologies and programming languages that contribute to the web, we'll discuss what lies within the group's focus. The web comprises of three layers— *content, presentation, and behavior*

![web-layers](http://dab1nmslvvntp.cloudfront.net/wp-content/uploads/2014/09/1409729756css_three-layers.png)

#### 1. HTML (Hyper Text Markup Language) 
HTML is an example of a widely known and used markup language. It is responsible for creating a markup of your website's content, letting the browser read it and display it correctly. Markup is the structure of the page, layout of your content, it is the foundation of websites, vital for search engine optimization (SEO). A markup language specifies code for formatting, both the layout, and style, within a text file. The code used to specify the formatting are called tags. 

HTML creates the `content layer` of a web page. It comprises the information the website wishes to convey, embedded within HTML markup that defines its structure and semantics. Most of the content on the Web is text, but content can also be provided through images, animations, sound, video, and whatever else an author wants to publish.
A HTML file's extension is **.html**

#### 2. CSS (Cascading Style Sheet)
CSS is the place where we bring all the colors, backgrounds, font sizes, layouts, grids etc. to life, it helps define the look and feel of the markup generated by HTML. A single CSS change can affect the entire mood and tone of a Web site. The term *Style sheet* refers to the document itself. A web page can have one or multiple style sheets. 

CSS creates the `presentation layer`, it defines how the content will appear when someone accesses it. The conventional way to view a web page is with a regular web browser, of course, but that’s only one of many possible access methods. 
A CSS file's extension is **.css**

*Html And CSS Are The Building Blocks Of Web Development. Every web page is written in HTML. So It’s Important To Know These Two Technologies Really Well. Together They Form The Bare Bones Of A Web Page, So Being Able To Write Custom HTML And CSS Is An Extremely Important Skill. It's Also Very Important To Understand How These Two Technologies Work Together: HTML Sets The Structure Of The Page And CSS Styles The Way It Looks.*

#### 3. Javascript (JS)

JavaScript is the third and final pillar of modern web development (the other two being HTML and CSS). JavaScript is the most advanced language of all three which enables us to interact with users in form of sliders, drop-down menus, quizzes, and many more interactive elements where sky is the limit. It’s what makes modern web the interactive, animated, vibrant place that it is. 

The `behavior layer` involves real-time user interaction with the document. This is usually handled by Javacript. The interaction can be anything from a trivial validation that ensures a required field is filled in before an email subscription form can be submitted, to sophisticated web applications that work much like ordinary desktop programs. 

When a user requests an HTML page with JavaScript in it, the script is sent to the browser and it's up to the browser to do the "magic" with it. JavaScript is *NOT* the same as Java. Their names may be similar, purely for marketing reasons, but they are two completely different programming languages. A JS file's extension is **.js**
  
For an introduction to Javascript, refer our [Intro to JS presentation](http://nupurkapoor.github.io/js-study-group/).

*It’s Possible To Embed All Three Layers Within The Same Document, But Keeping Them Separate Gives Us One Valuable Advantage: We Can Modify Or Replace Any Of The Layers Without Having To Change The Others.*

### How do I get started?

Awesome, congrats on taking the first step to learning how to code, now how should we get started? Believe it or not, its by **Building Your First Web Page!!**


HTML and CSS are independent of one another and should remain that way. CSS should not be written inside of a HTML document and vice versa. As a rule, HTML will always be the `content layer`, and CSS will always be the `presentation layer`. Now that you understand the importance of each, lets get started!

##### Common HTML Terms

###### Elements

HTML documents are made up by HTML elements. `Elements` are the bits that make up web pages, they are the designators that define the structure and content of different pieces within a page. These pieces could be textual, image, media, or links. Some commonly used HTML elements are:

* `<p>` - Paragraph, to place a text paragraph on a web page.
* `<img>` - Image.
* `<h1>` through `<h6>` - Multiple levels of page headings.
* `<a>` - Anchor/hyperlink.

As you must have noticed, all elements are identified by the use of less-than and greater-than angle brackets, `< >`, surrounding the element name. Together these angle brackets and the element name form a `Tag` 
 

###### Tags

The use of `<` and `>` angle brackets surrounding an element creates what is known as a `tag`. Tags most commonly occur in pairs of opening and closing tags, but there are some exceptions whree tags do not require a closing tag. 

An opening tag marks the beginning of an element. It consists of a less-than sign followed by an element’s name, and then ends with a greater-than sign; for example, `<a>`. A closing tag marks the end of an element. It consists of a less-than sign followed by a forward slash and the element’s name, and then ends with a greater-than sign; for example, `</a>`. What falls between these two tags will be the content of the anchor link.

###### Attributes

`Attributes` are properties used to provide additional information about an element. The most common attributes include the `id` attribute, which identifies an element and the `class` attribute which classifies an element. 

Attributes are defined within the opening tag, after an element’s name. Generally attributes include a name and a value. The format for these attributes consists of the attribute name followed by an `=` sign and then a quoted attribute value. For eg, an `<a>` tag including an `href attribute` would look like the following:

![HTML-1](https://raw.githubusercontent.com/nupurkapoor/WWCDC-FEHN-FTGuide/master/assets/images/HTML-1.png)

##### In Practice - Hello HTML!

Lets create your first HTML page. 

1. Open our text editor, create a new file named hello.html, and save it to a location you won't forget.

2. In the hello.html file, add the document structure, the `<!DOCTYPE html>` document type, and the `<html>`, `<head>`, and `<body>` elements.

	```
	<!DOCTYPE html>
	<html lang="en">
	  <head>
	  </head>
	  <body>
	  </body>
	</html>
	```

3. Inside the `<head>` element, let’s add `<meta>` and `<title>` element. Here meta elelemnt defines the data (information) about data better called as the metadata of the page. Metadata will not be displayed on the page, but will be machine or browser readable. In this particular case we'll use to define the specify the character encoding for the HTML document. As the name suggests title tag will define the title of the page.  

	```
	<!DOCTYPE html>
	<html lang="en">
	  <head>
       <meta charset="utf-8">
       <title>My first html page</title>
      </head>
	  <body>
	  </body>
	</html>
	```
	
4. Inside the `<body>` element, let’s add `<h1>` and `<h1>` elements. The `<h1>` element should include the heading we wish to include and the `<p>` element should include a simple paragraph.

	```
	<!DOCTYPE html>
	<html lang="en">
	  <head>
       <meta charset="utf-8">
       <title>My first html page</title>
      </head>
	  <body>
	   <h1> Hello World!! </h1>
	   <p> This isn't just any page, this is my begining. </p>
	  </body>
	</html>
	```

5. Now its time to open this page in a browser! Locate your hello.html file, double clicking the file or uisng the open-with option into a web browser will open it for us to review. This is how it looks in the text editor that I am using,

	
![HTML-2](https://raw.githubusercontent.com/nupurkapoor/WWCDC-FEHN-FTGuide/master/assets/images/HTML-2.png)

And this is how it looked when I accessed the page in Chrome:

![HTML-3](https://raw.githubusercontent.com/nupurkapoor/WWCDC-FEHN-FTGuide/master/assets/images/HTML-3.png)

Voila! You just created you first HTML page. Congratulation. Now lets take a look at CSS. 


##### Common CSS Terms

###### Selectors

`Selectors` are one of the most vital aspects of CSS as they are used to "select" elements on an HTML page, so that they can be styled. Selectors can be a combination of different qualifiers to select unique elements or a single qualifier to select multiple elements.

Before we start looking into different types of selectors, a quick intro to the syntax of a CSS file. CSS syntax is different from the HTML, but its really simple to pick up! The general format looks like this: 

```
selector {
    property: value;
}

```
So for example, if we wish to change the `color` property of a paragraph tag to blue, this is how we would do it:

```
p {
	color: blue;
}
```

Now the above code would change color to blue for ALL the paragraph tags on that page, for granuality we use other attributes as well, to be able target specific elements.

```
p#container {
	color: blue;
}

p.error {
	color: red;
}

```

In above code, every `<p>` tag with an `id` attribute of container will be colored blue, and every `class` attribute of error will be red. As you can see, `id` attribute is selected using `#` hash/pound symbol, and `class` attribute is selected using `.` the dot or period symbol.

**Common Selectors:**

1. `*` - Universal selector. The star symbol will target every single element on the page. It literally means 'ALL'. Be very careful while using this selector as it would apply the style on every single element of your web page.
2. `#id` - Id Selectors. To select an element by its `id` attribute. 
3. `.class` - Class selectors. To select an element by its `class` attribute. 
4. `h1`, `p`, `body`, `div`  - Type selectors. To select an element by its tag-type.
5. `div.article table` - Descendant Selectors. When you want to apply a style rule to a particular element only when it lies inside a particular element, in this case the CSS rule would only be applied if a `table` is inside a `div` with `class` attribute of 'article' 


##### Referencing CSS from within a HTML page

For our CSS and HTML files to talk to each other we need to reference our CSS file within our HTML. The best practice is to include all of our styles in a single external style sheet, which is referenced from within the `<head>` element of our HTML document, like so:

```
<head>
  <link rel="stylesheet" href="main.css">
</head>
```

##### In Practice - styling Hello HTML!

1. Create a new file with the extension `.css`, lets call it `main.css`. Save this file in the same folder as your `hello.html`.
2. Using our text editor, lets add some color and font to the `<h1>` tag, and some font to the `<p>` tag

```
h1 {
	font-family: Arial;
	color: blue;
}

p {
	font-family: Arial;
}

```

Now, the Gurus of programming have wisely adviced us to always be DRY. Donot Repeat Yourself. But we are! Both of our elements have the exact same font! Now there are two ways to resolve this, 

* If the file is as simple as ours, with nothing else but just a `<h1>` and a `<p>` tag, we can really just apply the `font-family` to the `<body>` tag of the page, so it shall then affect everything within the body tag.

```
body {
	font-family: Arial;
}

h1 {
	color: blue;
}
```

* But, if there were other elements too, and we only wanted to target the `<h1>` and the `<p>` tag, we can apply styles to both using `,` as a separator!

```
h1, p {
	font-family: Arial;
}

h1 {
	color: blue;
}

```

![MAIN-css-1](https://raw.githubusercontent.com/nupurkapoor/WWCDC-FEHN-FTGuide/master/assets/images/MAIN-css-1.png)

Now we need to reference this css file from within our html file:

```
<!DOCTYPE html>
<html lang="en">
  <head>
     <meta charset="utf-8">
     <title>My first html page</title>
     <link rel="stylesheet" href="main.css">
    </head>
  <body>
   <h1> Hello World!! </h1>
   <p> This isn't just any page, this is my begining. </p>
  </body>
</html>
```

Let's access the HTML file in browser, to see the styling in action.

![HTML-4](https://raw.githubusercontent.com/nupurkapoor/WWCDC-FEHN-FTGuide/master/assets/images/HTML-4.png)

Yayyyyy!!!

### Okay, what next?

The only logical next step is to NOT STOP! Refer our resources section, and continue your journey. All the best, and Congratulations!

### Resources?

* [Front End hack night resource list](https://github.com/womenwhocodedc/organization/tree/master/learning-resources/front-end-hack-nights)
* [Git Guide.](https://github.com/womenwhocodedc/organization/blob/master/learning-resources/git_guide.md)
* [Intro to JS](http://nupurkapoor.github.io/js-study-group/#/)
* [Intro to Git and Github](http://nupurkapoor.github.io/intro-to-git/#/)
* We use [Slack](https://slack.com/) as our internal chat system! To understand Slack better refer the [Slack guide](https://github.com/womenwhocodedc/organization/blob/master/slack_guide.md). 

#### What to follow?
* [Dash](https://dash.generalassemb.ly/)
* [Khan Academy - HTML + CSS](https://www.khanacademy.org/computing/computer-programming/html-css)
* [Khan Academy - HTML + CSS + JS](https://www.khanacademy.org/computing/computer-programming/html-css-js)

##### Keep in touch!
* Meet with us via [Meetup](http://www.meetup.com/Women-Who-Code-DC/).
* [Tweet](https://twitter.com/WomenWhoCodeDC) us.
* Email us - WWCodeDC@gmail.com
* Check us out on [Github](https://github.com/womenwhocodedc).
* Check our [website](http://womenwhocodedc.github.io/).
* Join our [Slack](https://docs.google.com/forms/d/1BXxIJuCawYt3pEzN7-6CgdT6XrhvG0KYQpOqdmv98DY/viewform) group.



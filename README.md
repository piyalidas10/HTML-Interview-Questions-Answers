# HTML-Interview-Questions-Answers

| No. | Questions & Answers                                                                                                                                                  |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | What does a DOCTYPE do? <br/><br/> Doctype is the abbreviation for the “Document type”. The Doctype declaration informs the web browser about the type and version of HTML used in building the web document like HTML5, HTML4.0, XHTML1.0.
| 2   | What happens when DOCTYPE is not given? <br/><br/> The web page is rendered in quirks mode. The web browsers engines use quirks mode to support older browsers which does not follow the W3C specifications. In quirks mode CSS class and id names are case insensitive. In standards mode they are case sensitive.
| 3   | What is the difference between a span and a div? <br/><br/> <strong>div</strong> is a block level element which means it will render it on it's own line with a width of a 100% of the parent element. <strong>span</strong> is an inline element which means it will render on the same line as the previous element, if it is also an inline element, and it's width will be determined by it's content.
| 4   | Name 5 common block-level and inline HTML elements? <br/><br/> block elements `<h1> to <h6>, <p>, <ul>, <ol>, <li>` tags. inline elements `<span>, <a>, <strong>, <i>, <img>`
| 5   | What are semantic and non-semantic elements? <br/><br/> Semantic elements: clearly describes its meaning to both the browser and the developer. For example: `<form>, <table>, <article>, <aside>, <details>, <figcaption>, <figure>, <footer>, <header>, <main>, <mark>, <nav>, <section>, <summary>, <time>` clearly defines its content. Non-semantic elements: `<div>` and `<span>` tells nothing about its content.
| 6   | What is the purpose of main element? <br/><br/> The HTML `<main>` element represents the dominant content of the `<body>` of a document. The main content area consists of content that is directly related to or expands upon the central topic of a document, or the central functionality of an application.
```
<main role="main">
    <p>Geckos are a group of usually small, usually nocturnal lizards. 
       They are found on every continent except Australia.</p>
    <p>Many species of gecko have adhesive toe pads which enable them to climb walls and even windows.</p>
</main>
```
| No. | Questions & Answers                                                                                                                                                  |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 7   | Define semantic markup. What are the semantic meanings for <strong>section, article, aside, nav, header, footer tags</strong> and when/how should each be used in structuring html markup? <br/><br/> <strong>header tag</strong> is used to contain introductory and navigational information about a section of the page. This can include the section heading, the author’s name, time and date of publication, table of contents, or other navigational information. <strong>article tag</strong> is meant to house a self-contained composition that can logically be independently recreated outside of the page without losing it’s meaining. Individual blog posts or news stories are good examples. <strong>section tag</strong> is a flexible container for holding content that shares a common informational theme or purpose. <strong>footer</strong> is used to hold information that should appear at the end of a section of content and contain additional information about the section. Author’s name, copyright information, and related links are typical examples of such content.
| 8   | When should you use section, div or article? <br/><br/> <strong>section</strong>, group of content inside is related to a single theme, and should appear as an entry in an outline of the page. It’s a chunk of related content, like a subsection of a long article, a major part of the page (eg the news section on the homepage), or a page in a webapp’s tabbed interface. A section normally has a heading (title) and maybe a footer too. <strong>article tag</strong>, represents a complete, or self-contained, composition in a document, page, application, or site and that is, in principle, independently distributable or reusable, e.g. in syndication. This could be a forum post, a magazine or newspaper article, a blog entry, a user-submitted comment, an interactive widget or gadget, or any other independent item of content. <strong>div tag</strong>, on the other hand, does not convey any meaning, aside from any found in its class, lang and title attributes.
| 9   | What is Character Encoding? <br/><br/> Character encoding is a method of converting bytes into characters. To validate or display an HTML document properly, a program must choose a proper character encoding. This is specified in the tag: `<meta charset="utf-8"/>`
| 10   | Can you have 2 `<head>` tags in HTML? <br/><br/> There should only be one <head> element in the HTML which contains all critical metadata for the document. Browsers and Googlebot will combine metadata from subsequent <head> elements if they are both before the `<body>`, however this should not be relied upon and is open to potential mix ups. Any <head> tags after the <body> starts will be ignored.
| 11   | Can you have 2 `<header>` tags in HTML? <br/><br/> You can have several <header> elements in one HTML document. The <header> is used to mark the header of e.g. articles in newspaper, so if you have multiple articles you can use multiple <header>.
| 12   | Can you have 2 `<header>` tags in HTML? <br/><br/> You can have as many `<SCRIPT></SCRIPT>` tags as you would like in a document. The `<SCRIPT>` tags are processed as they are encountered.
| 13   | Can I have two `<main>` tags in HTML? <br/><br/> A document mustn't have more than one `<main>` element that doesn't have the hidden attribute specified. The content inside the `<main>` element should be unique to the document. It should not contain any content that is repeated across documents such as sidebars, navigation links, copyright information, site logos, and search forms.
| 14   | Can have multiple `<html><body>` </html></body> in same file? <br/><br/> An HTML document can only have one html tag and one body tag. If you just put several HTML document together, it will be an invalid document, and the browsers may have problems displaying it.
| 15   | Can HTML have multiple titles? <br/><br/> The HTML standard specifies that there may be only one title tag for a page. If there is more than one title tag present, search engines may be confused about which tag to use. As a result, the search engine may combine the titles, ignore them altogether, or pick up one at random.
| 16   | What does HTML stand for? <br/><br/> HTML stands for Hyper Text Markup Language. HTML is the standard markup language for creating Web pages.
| 17   | Is h1 an empty tag? <br/><br/> The header 1 (h1) tag is considered important to help both users and search engines to quickly understand what content they can expect to find on the page. If the h1 is empty, this represents a missed optimization opportunity.
| 18   | What is the difference between div and P? <br/><br/> P is use for Paragraphs Div is use for grouping elements. They have semantic difference - a `<div>` element is designed to describe a container of data whereas a `<p>` element is designed to describe a paragraph of content. The semantics make all the difference.
| 19   | Which one is an empty tag? <br/><br/> Elements with no closing tag are known as an empty tag. For eg: `<br>, <link>, <img>, <hr>, <meta>, <source>` etc. Since we can not specify anything in between those. HTML element which does not have a closing tag are called Empty elements.
| 20   | Which is container tag? <br/><br/> Container tags require a starting as well as an ending tag. `<HTML>and </HTML>, <TITLE> and </TITLE>` are examples of container tags.
| 21   | Why is div called div? <br/><br/> `<div>` stands for division. The elements allow semantic attributes `(e.g. lang="en-US" )`, CSS styling `(e.g., color and typography)`, or client-side scripting `(e.g., animation, hiding, and augmentation)` to be applied.
| 22   | difference between body and main tag? <br/><br/> The main element is used to differentiate the main content of the page from other content such as navigation links or ads. In summary, the body element represents all the content on the webpage, while the main element represents the main content of the webpage.
| 23   | What is the difference between “display: none” and “visibility: hidden”? <br/><br/> “visibility: hidden” for element will be hidden from the webpage but still takes up space. “display: none” for the element will be hidden, and also it won’t take up any space on the webpage.
| 24   | When to use scripts in the head and when to use scripts in the body? <br/><br/> 1) Place library scripts or event scripts in the head section. 2) Place normal scripts that do not write anything on the page, in the head section until there is any performance issue. 3) Place scripts that render something on the web page at the bottom of the body section.
| 25   | What is the difference between `<figure>` tag and <img> tag? <br/><br/> The `<figure>` tag specifies the self-contained content, like diagrams, images, code snippets, etc. `<figure>` tag is used to semantically organize the contents of an image like image, image caption, etc., whereas the `<img>` tag is used to embed the picture in the HTML5 document.
| 26   | How to specify the metadata in HTML5? <br/><br/> `<meta>` tag which is a void tag,i.e., it does not have a closing tag. Some of the attributes used with meta tags are name, content, http-equiv, etc. 
| 27   | What type of audio files can be played using HTML5? <br/><br/> HTML5 supports the following three types of audio file formats: 1) Mp3 2) WAV 3) Ogg
| 22   | In how many ways can we position an HTML element? Or what are the permissible values of the position attribute? <br/><br/> 
```
There are mainly 7 values of position attribute that can be used to position an HTML element:

static: Default value. Here the element is positioned according to the normal flow of the document.
absolute: Here the element is positioned relative to its parent element. The final position is determined by the values of left, right, top, bottom.
fixed: This is similar to absolute except here the elements are positioned relative to the <html> element.
relative: Here the element is positioned according to the normal flow of the document and positioned relative to its original/ normal position.
initial: This resets the property to its default value.
inherit: Here the element inherits or takes the property of its parent.
```
| 22   | In how many ways you can display HTML elements? <br/><br/> 
```
inline: Using this we can display any block-level element as an inline element. The height and width attribute values of the element will not affect.
block: using this, we can display any inline element as a block-level element. 
inline-block: This property is similar to inline, except by using the display as inline-block, we can actually format the element using height and width values.
flex: It displays the container and element as a flexible structure. It follows flexbox property.
inline-flex: It displays the flex container as an inline element while its content follows the flexbox properties.
grid: It displays the HTML elements as a grid container.
none: Using this property we can hide the HTML element.


Below are some of the display types which are rarely used:

table
inline-table
table-cell
table-column
table-row
inline-grid
list-item
inherit
initial
table-caption
```
| 22   | Explain new input types provided by HTML5 for forms? <br/><br/> Following are the significant new data types offered by HTML5:
```
Date - Only select date by using type = "date"
Week - Pick a week by using type = "week"
Month - Only select month by using type = "month"
Time - Only select time by using type = "time".
Datetime - Combination of date and time by using type = "datetime"
Datetime-local - Combination of  date and time by using type = "datetime-local." but ignoring the timezone
Color - Accepts multiple colors using type = "color"
Email - Accepts one or more email addresses using type = "email"
Number - Accepts a numerical value with additional checks like min and max using type = "number"
Search - Allows searching queries by inputting text using type = "search"
Tel - Allows different phone numbers by using type = "tel"
Placeholder - To display a short hint in the input fields before entering a value using type = "placeholder"
Range - Accepts a numerical value within a specific range using type = "range"
Url - Accepts a web address using type = "url”
```
```
<form>  
        <div>
            <label>Date:</label>
            <input type="date" id="date" />
            <br>
            <label>Week:</label>
            <input type="week" id="week" />
            <br>
            <label>Month:</label>
            <input type="month" id="month" />
            <br>
            <label>Time:</label>
            <input type="time" id="time" />
            <br>
            <label>Datetime:</label>
            <input type="datetime" id="datetime" />
            <br>
            <label>Datetime Local:</label>
            <input type="datetime-local" id="datetime-local" />
            <br>
            <label>Color:</label>
            <input type="color" id="color"/>
            <br>
            <label>Email:</label>
            <input type="email" id="email" placeholder="email address" />
            <br>
            <label>Number:</label>
            <input type="number" id="number" />
            <br>
            <label>Search:</label>
            <input type="search" id="search" />
            <br>
            <label>Phone:</label>
            <input type="tel" id="phone" placeholder="Phone Number" pattern="\d{10}$" />
            <br>
            <label>Range:</label>
            <input type="range" id="range" />
            <br>
            <label>URL:</label>
            <input type="url" id="url"/>
        </div>  
    </form>
```
| 22   | What are the New tags in Media Elements in HTML5? <br/><br/> 
```
<audio> - Used for sounds, audio streams, or music, embed audio content without any additional plug-in.
<video> - Used for video streams, embed video content etc.
<source> - Used for multiple media resources in media elements, such as audio, video, etc.
<embed> - Used for an external application or embedded content.
<track> - Used for subtitles in the media elements such as video or audio.
<label>
       Video:
   </label>
    <video width="320" height="240" controls>
        <source src="video.mp4" type="video/mp4">
        <track src="subtitles.vtt" kind="subtitles" srclang="en" label="English">
    </video>
    <br>
    <label>
        Embed:
    </label>
    <embed type="video/webm" src="https://www.youtube.com/embed/MpoE6s2psCw" width="400" height="300">
    <br>
    <label>
        Audio:
    </label>
    <audio controls>
        <source src="audio.mp3" type="audio/mpeg">
    </audio>
```




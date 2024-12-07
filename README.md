# HTML-Interview-Questions-Answers

| No. | Questions & Answers                                                                                                                                                  |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | What does a DOCTYPE do? <br/><br/> Doctype is the abbreviation for the “Document type”. The Doctype declaration informs the web browser about the type and version of HTML used in building the web document like HTML5, HTML4.0, XHTML1.0.
| 2   | What happens when DOCTYPE is not given? <br/><br/> The web page is rendered in quirks mode. The web browsers engines use quirks mode to support older browsers which does not follow the W3C specifications. In quirks mode CSS class and id names are case insensitive. In standards mode they are case sensitive.
| 3   | What is the difference between a span and a div? <br/><br/> <strong>div</strong> is a block level element which means it will render it on it's own line with a width of a 100% of the parent element. <strong>span</strong> is an inline element which means it will render on the same line as the previous element, if it is also an inline element, and it's width will be determined by it's content.
| 4   | Name 5 common block-level and inline HTML elements? <br/><br/> block elements ht to h6, p, ul, ol, li . inline elements span, a, strong, i, img
| 5   | What are semantic and non-semantic elements? <br/><br/> Semantic elements: clearly describes its meaning to both the browser and the developer. For example: form, table, article, aside, details, figcaption, figure, "<footer>, <header>, <main>, <mark>, <nav>, <section>, <summary>, <time>" clearly defines its content. Non-semantic elements: div and span tells nothing about its content.
| 6   | What is the purpose of main element? <br/><br/> The HTML <main> element represents the dominant content of the <body> of a document. The main content area consists of content that is directly related to or expands upon the central topic of a document, or the central functionality of an application.
```
<main role="main">
    <p>Geckos are a group of usually small, usually nocturnal lizards. 
       They are found on every continent except Australia.</p>
    <p>Many species of gecko have adhesive toe pads which enable them to climb walls and even windows.</p>
</main>
```
| 7   | Define semantic markup. What are the semantic meanings for <section>, <article>, <aside>, <nav>, <header>, <footer> and when/how should each be used in structuring html markup? <br/><br/> <header> is used to contain introductory and navigational information about a section of the page. This can include the section heading, the author’s name, time and date of publication, table of contents, or other navigational information. <article> is meant to house a self-contained composition that can logically be independently recreated outside of the page without losing it’s meaining. Individual blog posts or news stories are good examples. <section> is a flexible container for holding content that shares a common informational theme or purpose. <footer> is used to hold information that should appear at the end of a section of content and contain additional information about the section. Author’s name, copyright information, and related links are typical examples of such content.
| 8   | When should you use section, div or article? <br/><br/> <section>, group of content inside is related to a single theme, and should appear as an entry in an outline of the page. It’s a chunk of related content, like a subsection of a long article, a major part of the page (eg the news section on the homepage), or a page in a webapp’s tabbed interface. A section normally has a heading (title) and maybe a footer too. <article>, represents a complete, or self-contained, composition in a document, page, application, or site and that is, in principle, independently distributable or reusable, e.g. in syndication. This could be a forum post, a magazine or newspaper article, a blog entry, a user-submitted comment, an interactive widget or gadget, or any other independent item of content. <div>, on the other hand, does not convey any meaning, aside from any found in its class, lang and title attributes.
| 9   | What is Character Encoding? <br/><br/> Character encoding is a method of converting bytes into characters. To validate or display an HTML document properly, a program must choose a proper character encoding. This is specified in the tag: <meta charset="utf-8"/>
| 10   | Can you have 2 <head> tags in HTML? <br/><br/> There should only be one <head> element in the HTML which contains all critical metadata for the document. Browsers and Googlebot will combine metadata from subsequent <head> elements if they are both before the <body>, however this should not be relied upon and is open to potential mix ups. Any <head> tags after the <body> starts will be ignored.
| 11   | Can you have 2 <header> tags in HTML? <br/><br/> You can have several <header> elements in one HTML document. The <header> is used to mark the header of e.g. articles in newspaper, so if you have multiple articles you can use multiple <header>.
| 12   | Can you have 2 <header> tags in HTML? <br/><br/> You can have as many <SCRIPT></SCRIPT> tags as you would like in a document. The <SCRIPT> tags are processed as they are encountered.
| 13   | Can I have two <main> tags in HTML? <br/><br/> A document mustn't have more than one <main> element that doesn't have the hidden attribute specified. The content inside the <main> element should be unique to the document. It should not contain any content that is repeated across documents such as sidebars, navigation links, copyright information, site logos, and search forms.
| 14   | Can have multiple <html><body> </html></body> in same file? <br/><br/> An HTML document can only have one html tag and one body tag. If you just put several HTML document together, it will be an invalid document, and the browsers may have problems displaying it.
| 15   | Can HTML have multiple titles? <br/><br/> The HTML standard specifies that there may be only one title tag for a page. If there is more than one title tag present, search engines may be confused about which tag to use. As a result, the search engine may combine the titles, ignore them altogether, or pick up one at random.
| 16   | What does HTML stand for? <br/><br/> HTML stands for Hyper Text Markup Language. HTML is the standard markup language for creating Web pages.
| 17   | Is h1 an empty tag? <br/><br/> The header 1 (h1) tag is considered important to help both users and search engines to quickly understand what content they can expect to find on the page. If the h1 is empty, this represents a missed optimization opportunity.
| 18   | What is the difference between div and P? <br/><br/> P is use for Paragraphs Div is use for grouping elements. They have semantic difference - a <div> element is designed to describe a container of data whereas a <p> element is designed to describe a paragraph of content. The semantics make all the difference.
| 19   | Which one is an empty tag? <br/><br/> Elements with no closing tag are known as an empty tag. For eg: <br>, <link>, <img>, <hr>, <meta>, <source> etc. Since we can not specify anything in between those. HTML element which does not have a closing tag are called Empty elements.
| 20   | Which is container tag? <br/><br/> Container tags require a starting as well as an ending tag. <HTML>and </HTML>, <TITLE> and </TITLE> are examples of container tags.
| 21   | Why is div called div? <br/><br/> <div> stands for division. The elements allow semantic attributes (e.g. lang="en-US" ), CSS styling (e.g., color and typography), or client-side scripting (e.g., animation, hiding, and augmentation) to be applied.
| 22   | difference between body and main tag? <br/><br/> The main element is used to differentiate the main content of the page from other content such as navigation links or ads. In summary, the body element represents all the content on the webpage, while the main element represents the main content of the webpage.



# HTML-Interview-Questions-Answers
| 1   | What does a <DOCTYPE html> do? <br/><br/> Doctype is the abbreviation for the “Document type”. The Doctype declaration informs the web browser about the type and version of HTML used in building the web document (e.g. HTML5, HTML4.0, XHTML1.0)
| 2   | What happens when DOCTYPE is not given? <br/><br/> The web page is rendered in quirks mode. The web browsers engines use quirks mode to support older browsers which does not follow the W3C specifications. In quirks mode CSS class and id names are case insensitive. In standards mode they are case sensitive.
| 3   | What is the difference between a <span> and a <div>? <br/><br/> <div> is a block level element which means it will render it on it's own line with a width of a 100% of the parent element. <span> is an inline element which means it will render on the same line as the previous element, if it is also an inline element, and it's width will be determined by it's content.
| 4   | Name 5 common block-level and inline HTML elements? <br/><br/> block elements <h1> to <h6>, <p>, <ul>, <ol>, <li> . inline elements <span>, <a>, <strong>, <i>, <img>
| 5   | What are semantic and non-semantic elements? <br/><br/> Semantic elements: clearly describes its meaning to both the browser and the developer. For example: <form>, <table>, <article>, <aside>, <details>, <figcaption>, <figure>, <footer>, <header>, <main>, <mark>, <nav>, <section>, <summary>, <time> clearly defines its content. Non-semantic elements: <div> and <span> tells nothing about its content.
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


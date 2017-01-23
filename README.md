#Interview Questions
######I have been through a lot of interviews in my life, both in person and phone screens. I have also taught a bunch of developers on how to crack interviews. 

######This page will list the most common questions I have faced in the recent years. This collection will focus primarily on front-end. I will expand to other areas if there is interest. To start with, I'll focus on four primary front-end technologies:

* HTML
* CSS
* Javascript
* jQuery

###HTML
####Q: What is the difference between HTML elements and tags?
A: HTML elements communicate to the browser how to render text. When surrounded by angular brackets **<>** they form HTML tags. For the most part, tags come in pairs and surround text.

####Q: Do all HTML tags have end tag?
A: No. There are some HTML tags that don't need a closing tag. For example: **<image>** tag, **<br>** tag.

####Q: What is semantic HTML?

Semantic HTML is a coding style. It is the use of HTML markup to reinforce the semantics or meaning of the content. For example: In semantic HTML <b> </b> tag is not used for bold statement as well as <i> </i> tag is used for italic. Instead of these we use <strong></strong> and <em></em> tags. 

####Q: What does DOCTYPE mean?
A: The term **DOCTYPE** tells the browser which type of HTML is used on a webpage. In turn, the browsers use **DOCTYPE** to determine how to render a page. Failing to use **DOCTYPE** or using a wrong **DOCTYPE** may load your page in Quirks Mode. 

See example:

For HTML 4.01

```<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd"> ```

For HTML5

```<!DOCTYPE HTML> ```

####Q: What are some new HTML5 markup elements?
A: HTML5 introduced a lot of new tags. Some of them are:

```<article>, <aside>, <bdi>, <command>, <details>, <figure>, <figcaption>, <summary>, <header>, <footer>, <hgroup>, <mark>, <meter>, <nav>, <progress>, <ruby>, <rt>, <section>, <time>, and <wpr>```

####Q: What are the new <input> types for form validation in HTML5?

The new input types for form validation are **email**, **url**, **number**, **tel** and **date**.

####Q: What is data-* attribute?
A: Back in the old XHTML/HTML4 days, developers had few options when storing arbitrary data associated with the DOM. Fortunately, HTML5 introduces custom data attributes. You can use any lowercase name prefixed with data-, e.g.

```<div class="user-info" data-user="parwinder" data-identifier="u-12345" data-usertype="cool"></div>```

P.S. The * may be replaced by any name following the production rule of xml names with the following restrictions:

* the name must not start with xml, whatever case is used for these letters;
* the name must not contain any semicolon (U+003A);
* the name must not contain capital A to Z letters.

####Q:  Describe the difference between cookies, sessionStorage, and localStorage.

Cookies are small text files that websites place in a browser for tracking or login purposes. Meanwhile, **localStorage** and **sessionStorage** are new objects, both of which are storage specifications but vary in scope and duration. 

The difference between localStorage and sessionStorage involves the lifetime and scope of the storage.

Of the two, **localStorage** is permanent and website-specific whereas **sessionStorage** only lasts as long as the duration of the longest open tab.

Both forms of storage are scoped to the document origin so that documents with different origins will never share the stored objects. But sessionStorage is also scoped on a per-window basis. If a user has two browser tabs displaying documents from the same origin, those two tabs have separate sessionStorage data: the scripts running in one tab cannot read or overwrite the data written by scripts in the other tab, even if both tabs are visiting exactly the same page and are running exactly the same scripts.

####Q: What are Web Workers?
A: Web Workers do all the computationally expensive tasks without interrupting the user interface and typically run on separate threads.

Web Workers allow for long-running scripts that are not interrupted by scripts that respond to clicks or other user interactions, and allows long tasks to be executed without yielding to keep the page responsive.

Web workers at long last bring multi-threading to JavaScript.


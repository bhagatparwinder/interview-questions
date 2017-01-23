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

####Q: What is data-* attribute?
A: Back in the old XHTML/HTML4 days, developers had few options when storing arbitrary data associated with the DOM. Fortunately, HTML5 introduces custom data attributes. You can use any lowercase name prefixed with data-, e.g.

```<div class="user-info" data-user="parwinder" data-identifier="u-12345" data-usertype="cool"></div>```

P.S. The * may be replaced by any name following the production rule of xml names with the following restrictions:

* the name must not start with xml, whatever case is used for these letters;
* the name must not contain any semicolon (U+003A);
* the name must not contain capital A to Z letters.
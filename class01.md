# Class 1 Reading Notes

## These topics are important because they lay the foundation of essential learning upon which more complex issues being taught later are built

### Describe how HTML, CSS, and JS files are “parsed” in the browser.  (Source [MDN web docs](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works))

* Browsers request HTML files that often contain CSS stylesheets and JavaScript elements.  
* The browser parses HTML first.  While this is happening, the browser recognizes references to stylesheets and script elements.  As HTML is parsing, the browser sends requests or the files found in the links and scripts.
* The browser, having parsed the HTML, generates Document Object Model (DOM)  and the CSS Object Model (CSSOM), and compiles and executes the JavaScript.
* The browser builds the DOM tree, applies the styles in the CSSOMand and executes the JavaScript, and displays the representation on the screen .

### How can you find images to add to a Website?  Source [mdn web docs](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like))

One can simply go to [Google Images[(https://www.google.com/imghp?gws_rd=ssl) and search.  One must be careful, however, to not use images that are copyrighted.  Using a license filter on Google Images (by clicking on _Tools_, _Usage Rights_ , and selecting _Creative Commons_.  

### How do you create a String vs a Number in JavaScript? (From [mdn web docs](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics))

* To create a string, while creating a variable, enclose the value in quotes.

    > String example - myName = “Joe”;

* Numbers are created by simply typing the number without quotes.

    > Number example - myNum = 117;

### What is a Variable and why are they important in JavaScript?  

Variables are used as containers to store values.  They are important in JavaScript because they can hold values that can be recalled later, as well as allowing them, in certain cases, to be changed.
# simple-word2html
Simple to use word to html converter with very limited functionality.

http://unblu.github.io/simple-word2html/

Converts the rich text or html format of Word-like editors when using copy/paste into a simple html format. The resulting html format is much cleaner and leaner, but of course also drops a lot of original attributes and meta-informations. It is mainly suited to use text written in Word in a web page with only simple formatting applied (paragraph, bold). 

Text can be copied from many sources in fact (it does not necessarily have to be Word). Most of the functionality is done by the browser itself by using contenteditable property which is supported by a wide variety of modern browser (see http://caniuse.com/#feat=contenteditable to get an idea).  

Has been tested on Google Chrome mainly - should work on most other modern browsers as well.

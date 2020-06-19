# Code Refactor by emilyresch
Assignment 1.
In this Code Refactoring assignment, I aimed to clean up the code given to me by:

- Removing errors/extranneous code in the html *
- Giving more semantic meaning to the html **
- Adding accessibility elements to the html ***
- Removing repetitive CSS properties/values %
- Changing or adding id's and classes to streamline the CSS file %%

*I removed/fixed some errors I noticed. One such error was the incorrect linking within the html - When you clicked on the navbar options, they are meant to bounce you to that blurb on the page. One link did not because the id attribute was missing in the spot the page was meant to jump. 
I also removed an extranneous </img> that I saw and a few stray "/". 

** To add semantic meaning, I changed some `<div>` tags to more descriptive tags, such as `<section>`, `<nav>`, `<footer>`, etc.

*** Webpages absolutely need to be accessible!! To do this I did what I mentioned above, as well as descriptive "alt"s to all of the images 

% Many of the selectors in the CSS file were extranneous or repetitive. A lot of the attributes were able to be consolidated under just one selector.

%% Basically a continuation of what I did in the previous section, I added some classes to images etc so that there didn't have to be so many selectors in the CSS. 

And overall, I added comments in the html and the css to organize the code and make it easier for other developers to edit if necessary.

# Horiseon Homepage

##Description

Refactored provided source code for the homepage of a fictional company 
called Horiseon in order to add accessability features, incorporate semantic
HTMLtags, and otherwise clean up existing code.

##Changes made

###Accessibility

Added alt-text to images to allow description by screen-reader software.

###Semantic HTML

    - Nested in-page links within nav tag.
    - Renamed div for "benefits" sidebar to an aside tag.
    - Renamed divs with header and footer tags as appropriate.

###Additional changes

    - Added title to head of index folder.
    - Fixed broken nav link to the Search Engine Optimization section by adding id attribute.
    - Renamed classes of content and sidebar divs in order to remove redundant css blocks (same results now achievable with one block).

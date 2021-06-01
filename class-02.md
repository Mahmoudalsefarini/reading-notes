# Basics of HTML, CSS & JS

* Strong & Emphasis

* strong>
The use of the strong>
element indicates that its
content has strong importance.
For example, the words
contained in this element might
be said with strong emphasis.
By default, browsers will show
the contents of a strong>
element in bold.

* em>
The em> element indicates
emphasis that subtly changes
the meaning of a sentence.
By default browsers will show
the contents of an em> element
in italic.

* address> 

The address> element has
quite a specific use: to contain
contact details for the author of
the page.
It can contain a physical address,
but it does not have to. For
example, it may also contain a
phone number or email address.
Browsers often display the
content of the address>
element in italics.
You may also be interested in
something called the hCard
microformat for adding physical
address information to your
markup.


# Using External CSS

* link> 

external-css.html HTML
The link> element can be used
in an HTML document to tell the
browser where to find the CSS
file used to style the page. It is an
empty element (meaning it does
not need a closing tag), and it
lives inside the head> element.
It should use three attributes:

1-href
This specifies the path to the
CSS file (which is often placed in
a folder called css or styles).
type
This attribute specifies the type
of document being linked to. The
value should be text/css.

2-rel
This specifies the relationship
between the HTML page and
the file it is linked to. The value
should be stylesheet when
linking to a CSS file.
An HTML page can use more
than one CSS style sheet. To
do this it could have a link>
element for every CSS file it
uses. For example, some authors
use one CSS file to control the
presentation (such as fonts and
colors) and a second to control
the layout.
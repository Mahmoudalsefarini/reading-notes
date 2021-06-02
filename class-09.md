# Forms and JS Events

# Form Structure

* form>
Form controls live inside a
form> element. This element
should always carry the action
attribute and will usually have a
method and id attribute too.
action
Every form> element requires
an action attribute. Its value
is the URL for the page on the
server that will receive the
information in the form when it
is submitted.
method
Forms can be sent using one of
two methods: get or post.

# Password Input

* input>
* type="password"
When the type attribute has
a value of password it creates
a text box that acts just like a
single-line text input, except
the characters are blocked out.
They are hidden in this way so
that if someone is looking over
the user's shoulder, they cannot
see sensitive data such as
passwords.

* name
The name attribute indicates
the name of the password input,
which is sent to the server with
the password the user enters.

* size, maxlength
It can also carry the size and
maxlength attributes like the
the single-line text input.



# HOW EVENTS TRIGGER JAVASCRIPT CODE

* When the user interacts with the HTML on a web page, there are three
steps involved in getting it to trigger some JavaScript code.
Together these steps are known as event handling.

* 1-Select t he element
node(s) you want the
script to respond to.

* 2-Indicate which event on
the selected node(s) will
trigger the response.

* 3-State the code you want
to run when the event
occurs.
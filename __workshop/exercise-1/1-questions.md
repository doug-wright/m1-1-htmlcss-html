# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [false] `<div><span>hello</div></span>`

b) [false]

```html
<ul>
<li>one</li>
</ol>
```

c) [false] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

A screenreader will interpret visual elements on a screen and then present them as synthisized voice for people who are visually impaired.  They are important because it allows people with visual impairments to interact with your web site.  In some jurisdictions it is also required by law to provide this means of accessibility.

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

img tags

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

Some 'ul' and 'li' tags perhaps to list the websites and 'a' tags to create the links to the remote content.

c) You want to sell designer hats. You need to receive orders from the user.

For a simple order form you could create an HTML form which would require a 'form' tag, some `<input type="checkbox">` tags to check off what you would like to order, some `<input type="text">` tags to provide contact information and then an `<input type="submit">` tag to submit the form to the server.

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

No.  The content model of the button element states that there must be no interactive content children of this element. So no elements that would require user interaction. 

https://html.spec.whatwg.org/multipage/form-elements.html#the-button-element

## Q5 - What is the most generic tag you can use?

A comment tag. 

## Q6 - What do the following achronyms stand for?

a) `a` anchor

b) `ol` ordered list

c) `ul` unordered list

d) `li` list item

e) `tr` table row

f) `th` table header

g) `td` table data

## Q7 - Usually, `td` elements are children of what kind of elements?

tr elements.

## Q8 - What is the difference between td and th?

A th creates a header cell in a table with the text automatically in bold and centered in the cell.  A td creates a data cell which will have no specific formatting unless you style it.

## Q9 - Which tag makes the text appear bigger: h1 or h3?

h1

## Q10 - In which situation can you use self closing tags?

Where the tag does not act on some inline content would be one situation.  For example a '`<strong>`This is strong`</strong>` would act only on the "This is strong" text.  Tags like br, img, link, etc. don't act on the content.  These are also known as void tags.

## Q11 - What is autofilling and why is it important?

Autofilling using the autocomplete attribute is used to automatically fill in values in an input field.  For example, if you've previously filled in the form and do it again, the browser will display your last value allowing you to select it rather than typing it all over again.  It's important because it will save the user time when completing forms.

## Q12 - Which attributes are always present in an img element?

src

## Q13 - Which attribute is always present for an anchor tag?

href
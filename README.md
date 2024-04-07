# HTML Basics

## What is HTML

- Essential for developing any web apps
- Focusing on only HTML in this session
- Describes content in the webpage
- All websites are written in HTML
- It is just a file like text or word but written in HTML
  <br><br>
- HTML stands for "Hypertext Markup Language"
  - The Hypertext part describes the web itself.
    - How the documents are hyperlinked and these websites are, which are built with HTML and accessible from a browser.
    - They can also be linked with each other.
  - The Markup Language part is what actually describes what HTML is. - A markup language is what wraps content with more information about that content. - It is, in essence a data structure, Telling the program that;s running it, what content it's intertpreting.
    <br><br>
- HTML is a descriptive markup language. In our case it describes the content part of a website.Like words, images, videos etc...
- The parts that describe this content are called elements or tags.
- Elements can be inside other elements just like a content can wrap other content.
  - In this case the element inside/nested element is called/reffered as the child of its encasing/outer element. Also the encasing/outer element is called parent element.
- `index.html` file is the default file loaded if no other file is specified.

## HTML Language Essentials

### HTML Syntax

- HTML syntax is used to write the HTML files using lots differernt elements which come together to form a web page.
- All HTML Elements follow the same format.
  - Write the name of the element inside angular brackets and then you can write the content after. Then we close the element by writing the same element again, inside angular brackets, but this time put a forward slash "/" after the first angular bracket.
- Headings
  - `<h1> Hello World! </h1>`
  - `<h2> H2 heading </h2>`
  - `<h3> H3 heading </h3>`
  - `<h4> H4 heading </h4>`
  - `<h5> H5 heading </h5>`
  - `<h6> H6 heading </h6>`
- `<p> Thsi is a paragraph. </p>`
- Image element
  - has some predefined attributes which are also called required attributes and optional attributes.
  - `<img src="assets/html5-logo.png" alt="Html5 Logo" />`
  - `<img src="assets/html5-logo-black.png.png" alt="Html5 Logo Black" />`
- `<!-- This is a comment -->`

### Page Structure

- First thing need is a doctype declaration to the program this is a HTML documnent and specifically we'll be using HTML5.
  - `<!doctype html>`
- Everything inside a HTML file is written inside a `html` element.
- It is always a good practice to close the element at same time to you open the element.
- Specify language used in HTML file with the `lang` attribtue
  - `<html lang="en">`
- Inside the `html` element there are two important child elements we need. `head` and `body` elements.
  - Everything the browser shows the user is written inside the `body` element. All of the content.
  - Most of the work is done inside the `body` element.

### Head Information

- The `head` element gives more information about the documnet itself.
- Most of this information is not shown to the user.
- `<meta charset="utf-8">`
- `<meta name="viewport" content="width=device-width,initial-scale=1">`
- `<meta name="description" content="HTML Basics Training">`
- `<title>My Website</title>`

### Heading Elements

- `<h1> H1 heading </h1>`
- `<h2> H2 heading </h2>`
- `<h3> H3 heading </h3>`
- `<h4> H4 heading </h4>`
- `<h5> H5 heading </h5>`
- `<h6> H6 heading </h6>`

### Paragraphs & Text

- `<p> This is a paragraph. </p>`
- `<p> This is a <strong>important</strong> text.</p>`
- `<p> This is a <b>bold</b> text.</p>`
- `<p> This is a <span>other</span> text.</p>`

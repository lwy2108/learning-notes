# html_basic

Referenced from [freeCodeCamp/Responsive Web Design/Basic HTML and HTML5](https://www.freecodecamp.org/learn/responsive-web-design/)

## Summary of elements

```html
<!--This is a comment, allowing inactive code (usually for other
developers).-->

<h1>Header1</h1>
<h2>Header2</h2>
<!--h1 for main headings, h2-h6 for different levels of subheadings.-->

<p>Paragraph</p>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
<!--Lorem ipsum text is traditionally used as placeholder text.-->

<main>
    <h1>Header1</h1>
    <p>Lorem ipsum...</p>
</main>
<!--Other descriptive tags include header, footer, nav, video, article,
section.-->

<img src="(url)" alt="...">

<a href="(url)" target="_blank">link to somewhere</a>
<!--The target attribute is optional, causing the link to open in a new
tab.-->

<a href="#(id)">Body</a>
...
<h2 id="(id, e.g. gallery-header)">Gallery</h2>
<!--The id must be assigned for the anchor to work.-->

<p> Please click <a href="..." target="_blank">here</a> for more
resources.</p>

<a href="#">link</a>
<!--Creates a dead link temporarily or for JavaScript.-->

<a href="#"><img src="..." alt="..."></a>
<!--Turn an image into a link by nesting it in a dead link-->

<ul>
    <li>item1</li>
    <li>item2</li>
</ul>
<!--Unordered (bullet point) list-->

<ol>
    <li>First</li>
    <li>Second</li>
</ol>
<!--Ordered (numbered) list-->

<form action="server-url-for-submission">
    <input type="text" placeholder="empty" required>
    <!--Text field for user input (self-closing)-->
    <!--Optionally, a placeholder text can be set for before any input-->
    <!--The required attribute is optional-->
    <button type="submit">Go</button>
    <!--This element sends data to the server specified by action-->
    <label for="indoor">
        <input id="indoor" type="radio" name="indoor-outdoor">Indoor
    </label>
    <!--Below is the preferred way, but both will have the same result-->
    <input id="outdoor" type="radio" name="indoor-outdoor">
    <label for="outdoor">Outdoor</label>
    <!--Nesting radio buttons in individual labels allows the user to
    click on the text to select the button by associating them-->
    <!--Related radio buttons should have an identical name attribute
    so that selecting one will deselect the other-->
    <!--Best practice: set a for attribute on the label element that
    matches the id of the input element, allowing assistive technologies
    to work-->
</form>
<!--With action, a web form can be made to submit input data to a server
with only pure HTML-->
```

## Tags

Written in lowercase

Closing tags have an added '/'

Self-closing elements are closed with '>' only

## Descriptive tags

From HTML5 onwards

Provide structure, readability, SEO and accessibility

## Image element

Self-closing

**Must** contain the ```alt``` attribute for accessibility (screen readers)

The ```alt``` attribute provides a description on failure to load

The `alt` attribute should not contain special characters

Best practice for **decorative images** is an empty ```alt``` attribute

## Anchor element

The ```a``` element links to content within or outside of the web page

The ```href``` attribute (with destination) and anchor text (which is displayed as a link) are **required**

The ```id``` attribute should uniquely describe the target element

The ```a``` element can be nested within other elements

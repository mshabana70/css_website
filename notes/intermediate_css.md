NOTES (Sec 5, Lec 42)

- Favicons: Favorite Icons, they are the icons that are displayed in your webpage's browser tab.
- you can design your own favicons [here](https://www.favicon.cc/)

NOTES (Sec 5, Lec 43)

- All HTML elements are boxes
- One way to format your webpage is by using the <div></div> element
- The HTML Content Division element (<div>) is the generic container for flow content. It has no effect on the content or layout until styled using CSS.
- You can use the chrome developer tool to test out CSS live on your webpage. All code written here will not be saved and lost once the page is refreshed.

NOTES (Sec 5, Lec 44, "CSS BOX MODEL")

- Imagine every element as a box
- Whenever resizing an element, elements around it are displaced according to the resizing
- When adding a border, you are adding to the size of the element.
- {border-top: 0px;} This makes the top border of the element zero pixels
- {border-width: 0px 10px 20px 30px;} 0px at top, 10px at right, 20px at bottom, 30px at left. Clockwise around a box! (top, right, bottom, left)
- Padding is a CSS shorthand property that sets the padding area on all four sides of an elements content at once.
- [Padding Visual](images/padding_screenshot.png)
- [Margin Visual](images/margin_screenshot.png)
- Border and padding change the size of the div or other elements
- Margin has no effect on the size of the element

NOTES (Sec 5, Lec 45, "DISPLAY PROPERTY")

- CSS Display is a module of CSS that defines how the CSS formatting box tree is generated from the document element tree and defines properties controlling it.
- The Display property has four different values; Block, Inline, Inline-Block, None.
- Block: Displays an element as a block element (like <p>). It starts on a new line, and takes up the whole width of the screen.
- Common Block Elements:
  - Paragraphs (<p></p>)
  - Headers (<h1> through <h6>)
  - Divisions (<div>)
  - Lists and list items (<ol>, <ul>, and <li>)
  - Forms (<form>)
- How can I target a specific character set within an HTML element? (<p> a programmer. </p>, i want to style the "pro")
- Use the <span> element
- Span: a generic inline container for phrasing content, which does not inherently represnet anythng. It can be used to group elements for styling purposes (using the class or id attributes), or because they share attribute values, such as lang. It should be used only when no other semantic element is appropriate. <span> is very much like a <div> is a block-level element whereas a <span> is an inline element.
- <span> elements dont do very much unless they are used in conjunction with CSS, similar to <div>
- Common Inline Elements:
  - Spans (<span>)
  - Images (<img>)
  - Anchors (<a>)
- Inline elements cannot have the width changed directly through CSS
- Instead, you can change the element type through the display property in CSS.
- what if you want to be able to do both?
- Inline-Block: Displays an element as an inline-level block container. The element itself is formatted as an inline element, but you can apply height and width values.
- Image elements are basically inline-block by default
- None: The element is completely removed, like it doesnt exist.
- None and Visibility are similary, although one is a property and another is a value of the Display property.
- Visibility CSS property shows or hides an element without changing the layout of a document. The property can also hide rows or columns in a <table>.
- Although this helps us format webpages how we like, there are rules that websites should abide by to get [beautiful designs](https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/19655686/#overview)


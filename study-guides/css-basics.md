# CSS Basics

In order to style the element on a page, CSS uses rule sets that contain specific properties and their values to apply to the elements. Let's take a look at the syntax of a rule set and explore deeper into its meaning.

HTML files typically contain things like:

- the text contents of a web page, structured into a hierarchy of page elements
- hyperlinks to other pages
- references to other files like images, CSS files, and JavaScript files
- definitions for interactive controls like buttons and text fields
- metadata to help web browsers understand the contents of the page

| Selector | Description | Syntax |
|----------|-------------|--------|
| [Universal Selector](https://developer.mozilla.org/en-US/docs/Web/CSS/Universal_selectors) | This selector uses the `*` symbol to apply styling rules to all elements on the website. | `* { property: value; }` |
| [Type Selector](https://developer.mozilla.org/en-US/docs/Web/CSS/Type_selectors) | This selector uses the name of an HTML element to apply styling rules to a specific type of elements | `element { property: value; }` |
| [Class Selector](https://developer.mozilla.org/en-US/docs/Web/CSS/Class_selectors) | This selector uses the `.` symbol followed by the class name (as identified by the attributes of some elements in the HTML document) to apply styling rules to all elements with the same class name. | `.className { property: value; }` |
| [Id Selector](https://developer.mozilla.org/en-US/docs/Web/CSS/ID_selectors) | This selector uses the `#` symbol followed by the id name to apply styling rules to a single element. | `#idName { property: value; }` |


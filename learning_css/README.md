# CSS

+ CSS is the language we use to style an HTML document, describes how HTML elements should be displayed.

## There are three Ways to Insert CSS in an HTML documment

1. External CSS

 With an external style sheet, you can change the look of an entire website by changing just one file!

Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.

2. Internal CSS

An internal style sheet may be used if one single HTML page has a unique style.

The internal style is defined inside the style element, inside the head section.

3. Inline CSS

An inline style may be used to apply a unique style for a single element.

To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

## CSS selectors

CSS selectors are used to "find" (or select) the HTML elements you want to style.

+ All CSS Simple Selectors:

| Selector | Example | Description |
| :---        |    :----:   |      ---: |
| #id | #firstname | Selects the element with id="firstname" |
| .class | .intro | Selects all elements with class="intro" |
element.class	p.intro	Selects only ```<p>``` elements with class="intro" |
| * | * | Selects all elements |
| element	| p | Selects all ```<p>``` elements |
| element,element,..	div, | p | Selects all ```<div>``` elements and all ```<p>``` elements |

## REFERENCE

[W3school](https://www.w3schools.com/css/)

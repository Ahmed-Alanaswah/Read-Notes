# What is CSS?

**CSS** (Cascading Style Sheets) allows you to create great-looking web pages,the web would be a boring place if all websites looked like that. Using CSS you can control exactly how HTML elements look in the browser, presenting your markup using whatever design you like.


## What is CSS for?

As we have mentioned before, CSS is a language for specifying how documents are presented to users — how they are styled, laid out, etc.

CSS can be used for very basic document text styling — for example changing the color and size of headings and links. It can be used to create layout — for example turning a single column of text into a layout with a main content area and a sidebar for related information. It can even be used for effects such as animation. Have a look at the links in this paragraph for specific examples.

## CSS syntax

>h1 {
    color: red;
    font-size: 5em;
}

## How To Add CSS

When a browser reads a style sheet, it will format the HTML document according to the information in the style sheet.

## Three Ways to Insert CSS

There are three ways of inserting a style sheet:

- External CSS
- Internal CSS
- Inline CSS

### External CSS
With an external style sheet, you can change the look of an entire website by changing just one file!

Each HTML page must include a reference to the external style sheet file inside the `<link>` element, inside the head section.

### Internal CSS
An internal style sheet may be used if one single HTML page has a unique style.

The internal style is defined inside the `<style> element, inside the head section.`


### Inline CSS
An inline style may be used to apply a unique style for a single element.

To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.
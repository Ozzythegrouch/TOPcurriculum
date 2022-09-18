# HTML

## Elements and Tags

- almost all have opening and closing tags
- <> open
- </> closing
- content goes between open and closing tag
- elements are containers for content

- predefined tags for [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

## Working with Text

- How to create paragraphs
    <p></p> 
    wraps all content so text doesn't appear all on one line
- How to create headings
    Provides hierarchy to content
    <h1>Largest</h1>
    <h2></h2>
    <h3></h3>
    <h4></h4>
    <h5></h5>    
    <h6>Smallest</h6>
    
- How to create bold text
    <strong>Makes Text Bold</strong>
- How to create italicized text
    <em>Makes Text Italicized</em>
- The relationships between nested elements
    Nested elements are the children in the relationship. The child element is nested in the parent element
- How to create HTML comments
    <!-- This creates HTML comments -->

## Lists

#### Unordered list
- order of items does not matter
- <ul></ul>
- within the ul you put <li></li> for list
- list will have bullet points
#### Ordered list
- order matters
- <ol></ol>
- <li></li> for items
- list items have numbered order

## Anchor Element
- <a></a>
- anchor tag on its own doesn't know where to go
- creates link
- <a href="">makes link clickable</a>
- attribute gives additional information an HTML element
- attribute is made up of two parts, name and value

### Absolute Links
- Links to pages on other websites
- always contains the protocol and domain of destination
- protocol://domain/path

### Relative Link
- Links to other pages within our website
- ./ makes code look for file directory reelative to the current directory

### Images
- <img>
- Does not need a closing tag
- src attribute needed to display image
- <img src="">
- ../ to go up in the path 

### Alt attribute
- alternative text attributeß
- Describes an image
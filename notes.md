# Table of Contents

[Slides](#slides)

[Session 1 - HTML and CSS](#session-1---html-and-css)

# Slides

[Session 0](https://docs.google.com/presentation/d/1YDLnu2izdXAPugegnC6_VTLPRpyskd-Hcz-Yai4ye9Y/edit)

[Session 1](https://docs.google.com/presentation/d/1UeeeqP4xZ2r_ykNOLOZfKaOWVbhgrW9bHaAn81_3CGQ/edit#slide=id.gb87fb862e2_0_368)

[Session 2]

[Session 3]

[Session 4]

[Session 5]

[Session 6]

[Session 7]

[Session 8]

# Session 1 - HTML and CSS

- tags can be nested.
- attributes are values within a tag like `href` for `<a>`
- make the visual changes with CSS.
- CSS can be used
  - inline in the tags `<p style="color:red;<other item>">`
  - use a style tag
    - Make all h1 a certain style
    - can be in html file or can be in sepatate file (which is then linked in the HTML)
- CSS is usually quite long as a style sheet and can be easier to keep outside of the file.
  - prefix with `#` for (??), `.` for class, or no prefix for tag
- Can target a class in css style tags by prefixing with a `.`
  - You can assign classes to any tag to apply that style to that tag instead of generalizing by tag type.
- IDs are unique per file and can be used to uniwuely identify blocks (super useful with javascript)
- emmet shortcuts can be used in CSS for nested patterns (CCS selectors)
  - Research more about emmet stuff
    > use ! at the top of a blank file to get a full skeleton for an HTML page

## Common tags

`<hX>` is a header tag where X can go from 1-6

`<p>` is a paragraph tag which is for regular text

`<a>` is an anchor tag which you can use to link items - `<a href=<url> target=<openning location>>`

`<br>` is a new line break tag without a closing tag

`<img>` is an image tag without a closing tag

`<ol>` is an ordered list outter tag

`<ul>` is an unordered list outter tag

`<li>` is a list item to be nested in a list outter tag

`<div>` is a divider which groups items nested within. This is super useful with CSS

`<!-- Comment -->` is a comment tag which will not appear and allows code commenting

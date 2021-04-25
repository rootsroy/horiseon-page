# Code Refactor Starter Code

## User Story

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

## Acceptance Criteria

GIVEN a webpage meets accessibility standards

- [x] WHEN I view the source code, THEN I find semantic HTML elements

- [x] WHEN I view the structure of the HTML elements, THEN I find that the elements follow a logical structure independent of styling and positioning
- [ ] WHEN I view the image elements, THEN I find accessible alt attributes
- [ ] WHEN I view the heading attributes, THEN they fall in sequential order
- [ ] WHEN I view the title element, THEN I find a concise, descriptive title

# Semantic HTML Implementation

> WHEN I view the source code, THEN I find semantic HTML elements

Following the W3 standards, the html was updated to inmplement `header`, `nav`, `section`, `article` and `footer` . More details [here](https://www.w3schools.com/html/html5_semantic_elements.asp)

# HTML Structucture Implementation

> WHEN I view the structure of the HTML elements, THEN I find that the elements follow a logical structure independent of styling and positioning

As a best practice we installed the "prettier" formatter for VSCode as to ensure code follows convention standards. It was applied both to the HTML and CSS.

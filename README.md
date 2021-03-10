# 01 HTML CSS Git: Code Refactor

- [CONTRIBUTOR(S)](#CONTRIBUTOR(s))
- [USER STORY](#USER-STORY)
- [DESCRIPTION](#DESCRIPTION)
- [REFERENCE LINKS](#REFERENCE-LINKS)
- [FUTURE DEVELOPMENT](#FUTURE-DEVELOPMENT)

---


## CONTRIBUTOR(s)
Dale Kittendorf

<br>

---

## USER STORY

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

---

- GIVEN a webpage meets accessibility standards
- WHEN I view the source code
- THEN I find semantic HTML elements
- WHEN I view the structure of the HTML elements
- THEN I find that the elements follow a logical  structure independent of styling and positioning
- WHEN I view the image elements
- THEN I find accessible alt attributes
- WHEN I view the heading attributes
- THEN they fall in sequential order
- WHEN I view the title element
- THEN I find a concise, descriptive title
---
<Br>

## DESCRIPTION

Converted a number of div tags to Semantic HTML. These included: Header, Nav, Aside and Footer.

Reduced the amount of necessary CSS, reusing single section(s) of code rather than repeating identical effects through multiple class tags.

Added alt-tags to images that will replace the images in cases where they won't display properly.

Reordered the code so that it seems more intuitive (to me anyway), following the ordered flow of the page.

Added a title element, which helps with seo and appears in the tab of the web browser.

---

## REFERENCE LINKS

* https://drkittendorf.github.io/01CodeRefactor/

* https://github.com/drkittendorf/01CodeRefactor

---

## FUTURE DEVELOPMENT

* Switch the float elements out for flex box and add a CSS reset.
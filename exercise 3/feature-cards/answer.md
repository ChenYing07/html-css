# Style feature cards with selectors: my answers

## 1. Which selector styles the full page or the page background?
body

## 2. Which selector styles the design that all cards use?
features

## 3. Which selector styles an element inside a section or a card?
card-grid

## 4. Which selector uses `>`?
.site-nav > a 

## 5. Which selector changes the page on hover?
.button-link:hover,

## 6. Which selector changes the page on focus?
.button-link:focus

## 7. Which two rules set the same property on one element, and which rule wins? Give the selectors, the property, the value that shows, and the reason.
.button-link {background-color: #3b82f6;} and .features .button-link {background-color: #3cd8ff;}, the second one wins.
In the browser the button-link show the #3cd8ff. The second one wins because it has higher specificity.
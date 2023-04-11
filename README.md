# conquering-responsive-layouts-challenges

Solutions to Kevin Powell's Conquering Responsive Layouts Course

## Challenge #1

---

### Instructions

1. Limit the total width of the `.intro-conent` to about half of it's parent
2. Stop the text from overflowing out the bottom at small screen widths

### Solutions

1. Added width property to `.intro-content` class
2. Removed the `height` property and added `padding:2rem` from the container.

## Challenge #2

---

### Instructions

1. Keep the text inside .intro-content in the same place, but have the background extend from one side of the viewport to the other, no matter how wide or narrow the browser is.
2. Limit the maximum width of the text in the bottom area.

### Solutions

1. The following changes were made:
   a. Created a header element with a `.header` class with the appropriate styles.
   b. Refactored `.container` class to only hold container specific styles.
   c. Added the styles `.intro-content` specific styles.
2. Wrapped the new text with a `div` element with the class `.container` class.

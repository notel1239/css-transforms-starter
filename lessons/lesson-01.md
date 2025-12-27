# Lesson 1: 2D Rotation

## Objective
Learn how to rotate elements in 2D space using the CSS `transform` property with the `rotate()` function.

## Concept
The `rotate()` function rotates an element around a fixed point (by default, its center) by a specified angle. Positive angles rotate clockwise, negative angles rotate counterclockwise.

## Your Task

1. In `index.html`, add a new `<div>` element with the class `rotation-demo`.
2. Style this element in `css/styles.css`:
   - Give it a width and height of 200px
   - Give it a background color of your choice
   - Add some padding and text content so you can see it
3. Apply a 2D rotation of 45 degrees using `transform: rotate(45deg);`
4. Experiment with different angles and observe the effect.

## Advanced Challenge
- Try changing the `transform-origin` property to rotate around a different point (e.g., `top left` or `20% 80%`).
- Add a smooth transition so the rotation animates when you hover over the element.

## Discussion Points
- How does rotation affect the element's layout flow?
- What happens to child elements when a parent is rotated?
- How does `transform-origin` change the visual result?

## Next Steps
Once you've completed this exercise, create an issue titled "Lesson 01: 2D Rotation" with this content, assign it to yourself, and proceed with the GitHub workflow.
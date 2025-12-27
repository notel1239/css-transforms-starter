# Lesson 2: Scaling

## Objective
Learn how to scale elements up and down using the CSS `transform` property with the `scale()` function.

## Concept
The `scale()` function changes the size of an element along the X and Y axes. You can scale uniformly (`scale(2)`) or independently (`scale(1.5, 0.5)`). Scaling does not affect the element's layout position—it only visually transforms the element.

## Your Task

1. In `index.html`, add a new `<div>` element with the class `scaling-demo`.
2. Style this element in `css/styles.css`:
   - Give it a width and height of 150px
   - Give it a distinct background color
   - Add some text so you can see the scaling effect
3. Apply a 2D scaling transformation:
   - Use `transform: scale(1.5);` to enlarge the element by 50%
   - Experiment with `scale(0.5)` to shrink it
4. Try scaling only horizontally: `transform: scaleX(1.8);` or vertically: `transform: scaleY(0.7);`

## Advanced Challenge
- Combine scaling with a transition to create a smooth "grow on hover" effect.
- Use `transform-origin` to control from which point the scaling expands (e.g., `bottom right`).
- Create a pulsing animation using `@keyframes` that repeatedly scales the element up and down.

## Discussion Points
- How does scaling affect the element's content (text, images)?
- What is the difference between `scale()` and changing `width`/`height`?
- How does scaling interact with other transforms like rotation?

## Next Steps
Once you've completed this exercise, create an issue titled "Lesson 02: Scaling" with this content, assign it to yourself, and proceed with the GitHub workflow.
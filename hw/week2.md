### Homework 2 (due Sunday, September 18, 2016)

**This homework has two parts:** complete the [in-class sketches](../README.md#recreating-sketches) and submit them in your homework repository (label these sketches `inclass-1.js` etc.); below, complete the programming practice problems by **Sunday night**.

#### Programming Practice (due Sunday)

- **Assignment: Pick 5 of the 15 sketches below and recreate them; at least one must be animated.** Bonus points for adding flourishes to your sketches. Create a new repository for this asignment, and then create a new file for each of your five sketches -- include the sketch number in the file name. Email a link to your repository [to us](mailto:jzamfirescupereira@cca.edu,mshiloh@cca.edu) by **Sunday, September 18**.

- Not all these sketches are equally difficult -- in fact some are very challenging!

- You may find the following [Processing tutorials](https://processing.org/tutorials/) helpful, but keep in mind the examples won't run exactly as written -- we're using JavaScript in P5.js, whereas Processing uses Java. (There's a guide for converting between the two [here](https://github.com/processing/p5.js/wiki/Processing-transition) -- but in general, any variable types (e.g., `int`, `float`) can be replaced with `var`, except for function paramters, which don't need the `var`, and function definitions use `function` in place of `void`.
  - The [Processing Overview](https://processing.org/tutorials/overview)
  - [Coordinate System and Shapes](https://processing.org/tutorials/drawing)
  - [Color](https://processing.org/tutorials/color)

- It may also help to read through the [P5.js reference](http://p5js.org/reference/) to understand all the various functions available to you.

- For extra programming help, consider following the [Khan Academy programming tutorials using Processing](https://www.khanacademy.org/computing/computer-programming/programming) -- but again, remember that we are using P5.js, not Processing, and your code won't look exactly the same.

- For hands-on, in-person help, stop by the Hybrid Lab and speak with a lab monitor, or make an appointment with one of the [Software or Math/Science coaches at the Learning Resources Center](https://www.cca.edu/students/resources/appointments).


Without further ado, here are the sketches:

1. Circles in a diagonal line. Use a while loop to draw the balls in sequence. What do you know about the x and y coordinates of each ball? (Spoiler: They're the same!)
   
   ![ball-diagonal](img/hw2/ball-diagonal.png)

2. Circles in a grid. You will likely need a while loop inside another while loop!
   
   ![ball-grid](img/hw2/ball-grid.png)

3. Colored circles in a grid, random version. Check out the `colorMode` function, and HSB, in the [P5.js reference](http://p5js.org/reference).
   
   ![ball-grid-randoms](img/hw2/ball-grid-randoms.png)

4. Colored circles in a grid, sequential version. Check out the `colorMode` function, and HSB, in the [P5.js reference](http://p5js.org/reference). Note that the colors shift from left to right *and* from top to bottom!

   ![ball-grid-rainbows](img/hw2/ball-grid-rainbows.png)

5. Circles in an triangle.

   ![ball-triangle](img/hw2/ball-triangle.png)
   
6. Circles in an hourglass.

   ![ball-hourglass](img/hw2/ball-hourglass.png)

7. The grid.
   
   ![grid](img/hw2/grid.png)
   
8. Diagonal lines.

   ![diagonal-lines](img/hw2/diagonal-lines.png)

9. Diagonal lines, interrupted.

   ![big-p](img/hw2/big-p.png)

10. Random bars.

   ![random-bars](img/hw2/random-bars.png)

11. Random bars, animated.

   [![random-bars-animated](img/hw2/random-bars-animated.png)](http://youtu.be/EA9MqlY56LM)

12. Animated bars, mouse-sensitive. Check out the P5.js-defined variables `mouseX` and `mouseY` in the [P5.js reference](http://p5js.org/reference).

   [![random-bars-mouse](img/hw2/random-bars-mouse.png)](http://youtu.be/3OAKqXS5Lkw)

13. Bouncing balls, just two.

   [![bouncing-balls](img/hw2/bouncing-balls.png)](http://youtu.be/7sfC4-4VoM4)

14. **Challenge:** Bouncing balls, more added by clicking. You may need to use an `Array` or two.

   [![bouncing-balls-with-clicks](img/hw2/bouncing-balls-with-clicks.png)](http://youtu.be/Tnkhya3Tqu0)

15. **Challenge:** Fireworks! They should track the mouse and appear on clicks.

   [![fireworks](img/hw2/fireworks.png)](http://youtu.be/yNTUEe9cof8)
   

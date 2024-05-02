# xwan0876_quiz_8

## Part1: Imaging Technique Inspiration

### 1.1 Introduction of the Design 
 According to the following picture, the design work generates a series of randomly growing trees and leaves on the canvas by clicking the mouse. 

![inspiration](readmeImages/mar.png)

This is the initial state that the trees are generated once you click the mouse.

![the image of initial state](readmeImages/initial.jpg)

And this is the final display that the portrait will be seen when there are enough leaves.

![the image of final display](readmeImages/final.jpg)

### 1.2 Insights
I discovered some things worth learning from the above works:
- **Dynamic effect** 
  Randomness and dynamic changes are used to simulate the growth process of trees. This dynamic effect can attract the user's attention and increase the interest and charm of the artwork. **In my major project, I can also consider setting a scene theme.**
- **Portrait processing** 
  The two elements of leaves and portraits are connected. Pixel information is used to fill in the color of the leaves, thereby achieving a map effect of the leaves, creating a more vivid and textured effect. **In subsequent designs, I will consider adding connections between two different elements instead of separating them.**
- **Interaction design** 
  At the beginning, the effect of sowing seeds is simulated through mouse events (click). With such a setting, the interactive scene will be stronger. **When giving interactive events, I can have a more story-like feel, such as adding scenes or music.**
![click 1](readmeImages/click1.jpg)
![click 1](readmeImages/click2.jpg)

## Part2: Coding Technique Exploration

### 2.1 Code Example and Analysis
link:https://editor.p5js.org/codingtrain/sketches/r9pxis9g-
- **How to create trees**
  ![tree code1](readmeImages/tree1.png)
  ![tree code1](readmeImages/tree2.png)
- **How to create branches**
  ![tree code1](readmeImages/branche.png)
- **How to create leaves**
  **this.pos = createVector(random(width), random(height - 100));** 
  
  Create an attribute pos in the leaf object, and use the createVector() function to function to generate a two-dimensional vector at a random position to prevent the leaves from appearing on the bottom edge of the canvas.

  **this.reached = false;** 
  Create an attribute reached in the leaf object to indicate whether the leaf has reached the target position.
  ![tree code1](readmeImages/leave.png)




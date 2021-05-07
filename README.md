# Connect-Lines

## Description
This project comes with a blank GUI and create a point whenever the user clicks on the screen. That point will automatically draw a line to the closest point. However, when a point has 5 or more connections, that point is deleted and all lines connected to the deleted point are redrawn to their closest point. The goal of the project is to practice **architectural design patterns**. Architectural patterns are general, reusable solutions to commonly occuring problem in software architecture. The architectural patterns use here are the **Model-View-Controller pattern** and **Blackboard pattern**. The design pattern decisions is explained in *Design_Explaination.pdf*. The structure of the project can be found in *UML_diagram.JPG*. 

## Source Code in Java
https://drive.google.com/drive/folders/1KW7A7MmGcVhX72zrIuOlDTUEcmeZx9bW?usp=sharing

## Example GUI pictures:
The user clicked 3 times:  
![3 dots and 2 lines appear](https://github.com/toantnguyen99/Connect-Lines/blob/main/pic1.JPG)

The user clicked a few more times:  
![A new line and a new point appear](https://github.com/toantnguyen99/Connect-Lines/blob/main/pic2.JPG)![A new line and a new point appear](https://github.com/toantnguyen99/Connect-Lines/blob/main/pic3.JPG)![A new line and a new point appear](https://github.com/toantnguyen99/Connect-Lines/blob/main/pic4.JPG)

The user clicked next to a point that already have 4 connected lines  
That point was deleted and new lines formed between the closest points:  
![The 4 lines were redrawed](https://github.com/toantnguyen99/Connect-Lines/blob/main/pic5Redraw.JPG)

The user clicked many more times, notices no point has 5 or more lines:
![Many points and many lines](https://github.com/toantnguyen99/Connect-Lines/blob/main/pic6All.JPG)

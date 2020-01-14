# Shape-App

## General Info 
In this assignment, I used several Object Oriented programming principles such as inheritance, polymorphism, and interfaces. Furthermore, I created my own LinkedList and Node classes in Java in order to ameliorate my understanding of algorithm complexity analysis and basic data structures.  

## How to Use Application
This program will allow you to enter a colour for a shape and select a shape of either an ellipse or a rectangle. Once the shape and colour are selected, you can draw the shape with its selected colour on the box titled “Draw Here” which is a panel on the right. When you draw a shape, it will also be stored in my own LinkedList class and will be shown in left box titled “List of Shapes” which acts as a simple database. A shape can be removed from the List of Shapes by selecting it in the related box and clicking “Remove Data” button then the selected graphical shape that was drawn will also be removed from the “Draw Here”. You can also clear all the drawings (entire list of shapes) from two panels by “Clear Drawing” button. The application is capable of restoring the data (list of text and created shapes) by clicking “Restore Data” button and getting the stored data from the ArrayList.

## Setup
To run this project, please cd into the project directory. Then compile AppViewer.java to run the Java program. 

```
$ cd ../Shape-App
$ javac AppViewer.java
$ java AppViewer
```
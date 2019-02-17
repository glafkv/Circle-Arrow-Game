# Circle-Arrow-Game
This is the first part of the circle arrow game.
{ Author: Gabi Appel

  Due Date: 2/4/19

  Class: CS4500 Sec. 1

  Program description: The point of this game is to follow arrows
  and make sure all the circles are checked. It will take in a file
  that has the number of circles, number of total arrows, and the the
  to and from arrows, it will then "set up" the game. If the circle
  has multiple arrows going out, it will randomly choose a direction to go.
  It will do this until all circles are checked. Then it will output the
  number of circles and total arrows it took in, the total number of checks in
  all the circles, the average number of checks marked in the circles, and
  the maximum number of any checks in one circle.

  Central data structures: I used arrays as my main data structures.
  The first one is an array of boolean values that I used to see if a
  circle had an out arrow. The second array is an array of the record oneCircle.
  I used a record so I can have elements of different types for my array

  Potential issue: I could not figure out how to catch if the input file wasn't
  formatted correctly}

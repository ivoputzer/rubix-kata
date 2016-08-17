rubik's cube kata
===

you are requested [to model][0] a rubik's cube behaviour in a language of your choice:

- the cube should be initialized to a given dimension:
  ```
  Rubix cube = new Rubix(3)
  ```

- the cube should have a method that randomizes internal bits:
  ```
  Rubix cube = Rubix(3)
  cube.randomize()
  ---
  Rubix randomized = Rubix.randomized()
  ```

- the cube should have a method to move layers individually either clockwise and counterclockwise:
  ```
  cube.move([R|Ri|L|Li|U|Ui|D|Di|B|Bi|F|Fi])
  ---
  cube.right([direction])
  cube.left([direction])
  cube.up([direction])
  cube.down([direction])
  cube.back([direction])
  cube.front([direction])
  ```

- the cube should know whether or not it is in a final position:
  ```
  Boolean done = cube.done()
  ```

Cheers!

[0]: https://en.wikipedia.org/wiki/All_models_are_wrong

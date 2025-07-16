Date: 16th July 2025
Youtube: https://www.youtube.com/watch?v=Ip3X9LOh2dk&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab&index=7
Website: https://www.3blue1brown.com/lessons/determinant

What I learnt:
Linear Transformation is something that moves, stretches, or compressed the 2d plane or either the 3d space. This is done by applying a
matrix to vectors.

<img width="1340" height="681" alt="image" src="https://github.com/user-attachments/assets/487be9ed-fc93-4133-9910-b9c25b236651" />

If I know the area of how much that one single unit square changes, I can determine the area about any possible region in space changes also.
What happens to one square on the grid, the same has to happen to any other square on the grid regardless of size.

The scaling factor is called the "determinant" of a transformation. Determinant of a 2d transformation is 0 if it squishes all of space onto a single line / point.

If the determinant is greater than 1, the area increases, less than 1 but greater than 0 means area shrinks and < 0 is same as others but the space is flipped.
Whenever the orientation of the space is inverted, the determinant will be negative and the actual value still tells you the factor of the area that has been scaled.

In 3d-space, the determinant tells you the area is scaled by, however, in addition to this, it tells you the amount of volume which gets scaled also.
It's easy to hink of this by imagining a cub in 3d space. After the transformation has been applied, this cube might get "warped" into a different shape. This shape is called
the "Parallelipiped". The determinant is the volume of the cube is turned into.

In order to compute the determinants in a 2x2 matrix, the formula is: 
<img width="1013" height="375" alt="image" src="https://github.com/user-attachments/assets/75ccb561-4f1d-4023-92fa-2d2a8b7df684" />

![calculating-determinants-2x2and-3x3](https://github.com/user-attachments/assets/9fef3b34-ea85-4e5e-868f-100ec6b4149f)

What does Wx + b actually mean geometrically?

Let us break it down :
x -> input vector(your data).
W -> Weight matrix
b -> bias vector

Tranform the input -> then shift it.

Lets go deeper,


Step-1: What does Wx mean?


->  When x is multiplied  by weight  matrix W it is a linear transformation.

Tranformation is just movement. The movement of the input vector.

A  transformation is said to  br linear if it has  two properties:
1) All lines must remain lines without  getting curved.
2) Origin must be fixed in its place.

So in MACHINE  LEARNING TERMS,
                "W extracts  patterns/features from input vector x"

Step-2: What does Adding b does to the Wx?

By adding b  is a shift to the transformation i.e. translation

It moves everything:
1) up/down
2) left/right
3) in higher dimensions: along  axes

So it simply means Wx + b ---------------> Wx for transformation and b for shift that  gives us  "Transform, then shift".

This is a affine transformation.

Much more about it might be learned by  me in neural networks


This is  end of my Day-1 of learning  ai-ml.

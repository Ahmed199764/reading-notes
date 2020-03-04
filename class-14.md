# Class-14

# Transforms
it is a property that alternative ways to size, position, and change elements.

### Transform syntax
div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}

### 2D Transforms
Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes.

### 3D Transforms
Three-dimensional transforms work on both the x and y axes, as well as the z axis.

### 2D rotate
on HTML 
< figure class="box-1">Box 1</ figure>
< figure class="box-2">Box 2</ figure>

while on CSS 
.box-1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: rotate(-55deg);
}

### 2D Scale
HTML 
< figure class="box-1">Box 1</ figure>
< figure class="box-2">Box 2</ figure>

CSS 
.box-1 {
  transform: scale(.75);
}
.box-2 {
  transform: scale(1.25);
}

Notice : we can also scale only the x or y or even the z.

### 2D Translate
HTML 
< figure class="box-1">Box 1< /figure>
< figure class="box-2">Box 2< /figure>
< figure class="box-3">Box 3< /figure>

CSS
.box-1 {
  transform: translateX(-10px);
}
.box-2 {
  transform: translateY(25%);
}
.box-3 {
  transform: translate(-10px, 25%);
}

# Transitions
element must have a change in state, and different styles must be identified for each state.
we can play on the transitions by :-
1. :hover
2. :foucs 
3. :active
4. :target

### The most wow transitions for users:
1. fade in
2. change color
3. Grow&Shrink
4. Rotate element
5. Square to circle
6. 3D shadow
7. Swing
8. Inset border






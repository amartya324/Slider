![image](https://github.com/amartya324/Slider/assets/77157125/abcc394d-9b8c-49ed-a568-393c405d3873)

#### Main Logic

To move the slides back and forth, use the transform property with a translateX value. For example, to move the slides to the left, you can use the transform:translateX(-100%) property however to move the slides to the right, you can use the transform:translateX(100%) property. For the active slide we will use transform:translateX(0)

#### Current Person

Create a currentPerson state value in App.jsx and set it to 0 initially. This will allow you to keep track of the current slide being displayed.

#### Prev and Next

Implemented the prev and next functionality using the setCurrentPerson function to update the currentPerson state value.

#### Auto Slide

Implement the auto slide functionality using the setInterval function to change the currentPerson state value at regular intervals.

#### React Slick Library

[React Slick Docs](https://react-slick.neostack.com/)

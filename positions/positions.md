There are 5 types of position property - static, relative, absolute, fixed and sticky.

### 1\. position : static

When we define an element in HTML file it has an already existing position for itself And this position is static position of that element.

This is default position for any element in html file. We can not change position of element by using this property. We can not use properties top, bottom, left and right properties by using this property.

### 2\. position : relative

Static position of an element is also relative position of that element. But by defining this property we can move element from its static position. With this property We can use properties like top, left, right and bottom. For example , If we want move an element from its static position to left side . We can just use below code

```plaintext
.selected-element {
    position : relative;
    left : 20px;
}
```

This will move element to left side to 20px away from its relative position.

### 3\. position absolute

when we give position absolute to an element it is no longer be on its static position. It means element is removed from the normal document flow, and no space is created for the element in the page layout.

Now it will be positioned from its parent or ancestor element's position which has position relative. if his parent element has position relative then it will be positioned from its parent element's position and if his parent element does not have position relative then it will be positioned from its ancestor element's position which has position relative. if his parent and ancestors does not have position relative then it will be positioned from body element. after understanding this we can use right, left, top, bottom properties to position it.

### 4\. position : fixed

An element with positioned fixed behaves same as an element with position absolute. The only difference is that position fixed element is unaffected by scrolling and it always stays in the same place. We have to position it with top, right, bottom and left properties.

### 5\. position : sticky

An element with positioned sticky behaves same as an element with position relative until the scroll location of the viewport reaches a specified threshold, at which point the element takes a fixed position where it is told to stick.
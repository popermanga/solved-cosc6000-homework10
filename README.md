Download Link: https://assignmentchef.com/product/solved-cosc6000-homework10
<br>
Develop <u>a template class</u>, <strong>ShiftArray</strong> that has following features.

template parameters are <u>data type</u> and<u> size</u> of array. Overload operator [] member function <strong>circshift(int n)</strong> that circularly shifts the elements in the array by <strong>n</strong> positions.

<strong>n</strong> is a int type.

If <strong>n</strong> is positive, shift elements towards right. If <strong>n</strong> is negative, shift elements towards left.

For example :

1 2 3 4 5     Initial array elements




5 1 2 3 4      <strong>circshift(1) </strong>




1 2 3 4 5      <strong>circshift(­1) </strong>




4 5 1 2 3      <strong>circshift(2)</strong>

Use code below to test your class:

https://tulane.instructure.com/courses/2165899/assignments/13470336                                                                                                                                   1/2

output will be:



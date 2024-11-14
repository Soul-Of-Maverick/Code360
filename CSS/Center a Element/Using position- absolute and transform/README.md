Explanation:

position: absolute: The element is positioned relative to the nearest positioned ancestor (in this case, .container).
top: 50% and left: 50%: Positions the top-left corner of the element at the center of the container.
transform: translate(-50%, -50%): Offsets the element by half of its own width and height, fully centering it.

<img src="image.png" >

This method works well for precise centering and can be particularly useful if Flexbox and Grid are not options.
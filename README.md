# Web-Development-Day-18
CSS Box Model
The CSS Box model defines how elements are rendered and how their dimensions are calculated. It describes the structure of an element as a rectangular box that has content, padding, a border, and a margin. The box model consists of four main components, which are:
1. Content
The innermost component of the box model is the actual content of the element. It can be text, image, video, etc.
The content area is defined by the width and height properties.
2. Padding
The space between the actual content and the border of the element is the padding.
The padding area is defined by the property padding. 
3. Border
The border surrounds the content and padding and gives the visual border of the element.
The border properties can be controlled using the border keyword.
4. Margin
The margin is the space outside the element that separates it from other elements in the layout.
The margin of the element is controlled by the margin property.
Calculating the total dimension of the element
The total width and height of the element is calculated with the formula:
Total Width = Width + Left Padding + Right Padding + Left Border + Right Border + Left Margin + Right Margin
Total Height = Height + Top Padding + Bottom Padding + Top Border + Bottom Border + Top Margin + Bottom Margin
Playaround:
To view the dimension of any element follow the steps or video:
Right-click and click on Inspect.
Click on the arrow key in the top left corner.
Select the element.
Unhide the computed styles sidebar.
Toggle the properties.

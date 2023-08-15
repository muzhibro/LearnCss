##The areas of the box model
You start with content box, which is the area that the content lives in. As you learned before: this content can control the size of its parent, so is usually the most variably sized area.

The padding box surrounds the content box and is the space created by the padding property. Because padding is inside the box, the background of the box will be visible in the space that it creates. If our box has overflow rules set, such as overflow: auto or overflow: scroll, the scrollbars will occupy this space too.

The border box surrounds the padding box and its space is occupied by the border value. The border box is the bounds of your box and the border edge is the limit of what you can visually see. The border property is used to visually frame an element.

The final area, the margin box, is the space around your box, defined by the margin rule on your box. Properties such as outline and box-shadow occupy this space too because they are painted on top, so they don't affect the size of our box. You could have an outline-width of 200px on our box and everything inside and including the border box would be exactly the same size.

###A useful analogy:
The box model is complex to understand,so let's recap what you've learned with an analogy.
In this diagram,you have three photo frames,mounted to a wall ,next to each other .The diagram has labels that associate elements of the frame with box modle.

To break this analogy down:
- the content box is the artwork.
- the padding box is the white matte,between the frame and the artwodk.
- the border box is the frame,providing a literal border for the artwork.
- the margin box is the space between each frame,
- the shadow occupies the same space as the margin box.

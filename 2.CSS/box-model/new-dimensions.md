If padding, margin, etc are added to a div for example, then the new dimensions of the div would be:

newHeight = originalHeight + paddingTop + paddingBottom + marginTop + marginBottom + borderTop + borderBottom;

newWidth = originalWidth + paddingLeft + paddingRight + marginLeft + marginRight + borderLeft + borderRight;

These kind of questions, where you have to find the new size/dimensions of a div after border, padding etc are added to are somewhat common in web developer interviews. Therefore it is best to learn how to calculate the same as mentioned in here.

!!!NOTE!!!
Outlines are not taken into account when calculating the dimensions of an element(div, etc).
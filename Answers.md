1.  box3 would have the most specificity on the html side, since it's farthest to the right.  This can be offset by how the css file is laid out.  for example, if you called .box3 {}, you would have a certain level of specificity, but if you laid the path out, such as, body container box1, that could create a higher specificity on your css.  Also, placement on the css page could affect specificity.

2.  display block wants to take up the width of the container its in, also it will create its own line.   dispaly inline will only take up the amount of room the content is using and will not create its own line.

3.  you would be centering on the cross axis.  of course this could be reversed if you changed the flex-direction to column.  then it would be using the main axis to center.

4.  Fixed layout is going to look the same across all devices.  No media queries, and it's widths are not percent based, so nothing is responding to different viewport sizes.  This could lead to a lot of white space if the vp is massive, or scrunched together and almost unusable if the vp is smaller.  
    
    Adaptive uses different layouts for different screen sizes.  disadvantagse is you can't cover all your bases, if a new screen size is used, you may not have a template for that new vp and thus your website becomes somewhat fixed.  The templates are optomized for specific screen sizes.

    Fluid is percent width based, white space can become excessive when used on a bigger vp, also you will run into a scrunched feel on smaller vps.

    Responsive uses media queries to change at break points.  The most popular in use, its only draw back is complexity.

5.
    
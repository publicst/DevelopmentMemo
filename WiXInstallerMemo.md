### Scaling Issue
When you are making your own WiX installer UI, if you just enter the pixel value of the image as the width and height, the scaling occurs. This issue occurs because of the use of **installer units**. Basically it is unit that gets scaled based on DPI.

The default 100% scaling of Windows uses 96 DPI, and in order to make the image appear 1:1, I have to enter the width and height of **75% of what it originally was in pixel.**

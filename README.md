Seam carving final project - Computer vision

As we are aware, with the advancement of technology, developers are deploying more and more applications and websites for the needs of people and making their lives easier. Images are the most
important part when it comes to these applications and since we use different kinds of phones, image
size is critical. There are different techniques for adapting an image for different devices such as cropping or standard scaling but at the end the image ends up losing information only in the periphery
when we perform cropping. These techniques don’t seem to be the best way when it comes to resizing since we lose important content from the image. Shai Avidan and Ariel Shamir introduced seam
carving that can change the size of an image by gracefully carving-out or inserting pixels in different
parts of the image. As they explained in their paper Seam carving uses an energy function defining the importance of pixels.
A seam is a connected path of low energy pixels crossing the image from topto bottom, or from left to right. For this final project I am going to implement seam carving for image
resizing using the same techniques as they did. So, the main steps of the implementation are:
• Computing the energy map of the image or in other word finding the edges of the image
• Calculating the energy map matrix which will store the least energy of the pixels and the path
of these values.
• Finding the seam with the lowest energy and then removing it from the image.
• Comparing the original image with the resized one.

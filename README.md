# Pixelizer_Depixelizer

## Group Members (Name/USP ID):
- Andre Seiti Caniza (9790923)
- Bruno Waldvogel (9847690)
- Marcel Otoboni de Lima (9791069)

## Main Idea of the Project

Transform a given image to a pixel-art representation, and vice-versa. 

## Pixelizer

The name Pixelizer refers to the process of transforming the image to a pixel art representation with a limited pallete of colors. To start with, we are going to work with images representing objects or characters, like books, video-game characters and so on. Our main goal for this first part is to accomplish something like the following:

![alt text](./expected_results/sample-1.png)
![alt text](./expected_results/sample-2.png)

## Depixelizer

If there is any remaining time left by the end of the semester, our second goal is to reverse the process mentioned above, i.e, transforming an original pixel-art image into a smooth countour-lined image using algorithms such as xBR or HQX (popular fast image upscaling algorithms), hoping to achieve the following results:

![alt text](./expected_results/sample-3.jpeg)

![alt text](./expected_results/sample-4.png)

## Partial Results Report

After applying image processing algorithms in our images, such as image segmentation (to construct the color palette to be used by the final pixel-art image) and edge/contour detection (to give the object/character that sweet black contour that is typical of the style of pixel-art), we have arrived at some pretty good results, but we are still figuring out the best way to accomplish that fine contour definition, which turned out to be pretty hard to get right. With that in mind we give a few example of the results:

![alt text](./partial_results/boo_p_res.png)

![alt text](./partial_results/samus_p_res.png)

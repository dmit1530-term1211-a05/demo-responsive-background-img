# [demo] Responsive Background Images

This demo explains the importance of optimizing background images.

There is a lot of different opinions and discussions about this topic on the web, but overall you want to stay between 50 - 150KB per picture and under 250KB for a large full screen image.

## Image Sizing

### Smallet Image:

Start with the smallest size first - serve a scaled-down version of the background imgage to be conscious of page load speed and bandwidth.

As an example, if the original image is 4460px by 2973px and 950KB - that waaaayyyyy to large to load on small screens (any screen really). So you should be:
1. Find find ratio: 4460/2973 = 1.5 (using the squoosh.app will do this automatically!)
2. Reduce the size of your photo in photoshop or the squoosh app.
3. then run it through a compression tool to reduce the size a bit more

For example, a good small image size might be around 600px by 400px. 

### Medium Image.

As the screen gets wider, the background image stretches to fit and the lower quality of the image no longer looks good So, follow the same steps as above, but your scale your image a bit larger to increase the quailty of the overall image. 

Images will be swapped out using media queries, so we are loading the image we need and not just one large size.

### Large Image

Continue to use PS or the Squoosh.app to resize and compress your images, as well as online compressor.

Save your desktop image (banner images) at a higher quality level, as it will stretch beyond the actual cropped width. Current reccommendation are to keep full screen and background images under 250KB






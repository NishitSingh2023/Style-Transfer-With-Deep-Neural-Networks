# Style-Transfer-With-Deep-Neural-Networks

This project shows the power of __Deep Convolutional Neural Networks__, By merging two pictures into one.
***
Style transfer relies on separating the content and style of an image. Given one content image and one ` style image `, we aim to create a new, ` target image ` which should contain our desired content and style components:
 - objects and their arrangement are similar to that of the ` content image `
 - style, colors, and textures are similar to that of the ` style image `

***
In this notebook, we'll use a pre-trained [VGG19](https://www.programcreek.com/python/example/108006/torchvision.models.vgg19) Net to extract content or style features from a passed in image. We'll then formalize the idea of content and style losses and use those to iteratively update our target image until we get a result that we want.

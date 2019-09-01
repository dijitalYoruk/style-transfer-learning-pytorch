# Style Transfer Learning with Pytorch

Style Transfer Learning refers to a class of software algorithms that manipulate digital images to adopt the appearance or 
visual style of another image. Content image and style image are taken and resized to equal shapes. Corresponding convolutional
layers of vgg19 is chosen for content extraction and style extraction and weighted with parameters. For style extraction, gram matrix 
of the style images are taken. Then, the loss functions for style and content images are arranged and combined. After combining, total 
variation loss is obtained and by backward and forward propagation, total variation loss is minimised. After the miniimisation process,
the visual obtained images are the followings:

![](images/you-picture.png)

![](images/you-picture.png)

![](images/you-picture.png)

![](images/you-picture.png)

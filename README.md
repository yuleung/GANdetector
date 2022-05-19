# No one can escape: A general approach to detect tampered and generated image

Fake or tampered images pose a real problem in today’s life. It is easy to unknowingly be drawn to an interesting image that is false. Recently, with the emergence of generative adversarial networks (GANs), it becomes much more easy to generate high-quality fake images in a very realistic way. However, the current digital image forensics algorithms mainly focus on the detection of traditional tampered images or need prior knowledge of the network structure of GANs. Hence, verifying the authenticity of an image is very challenging. In this paper, we propose a general method for simultaneously detecting tampered images, and GANs generated images. First, we use the Scharr operator to extract the edge information of the image. Then, we converted the edge image information matrix into the gray level co-occurrence matrix (GLCM) to scale the image without loss of image information. Finally, GLCM was fed into the deep neural network designed based on depthwise separable convolution for training. Compared with other methods, our model achieves a higher macro average of F1 score of 0.9865. Meanwhile, our method has better performance in detecting tampered images and has strong generalization ability for many GANs models.


MIT license

Programmer: Yu Liang

Email: zjy@besti.edu.cn

Accepted by IEEE ACCESS

北京电子科技学院CSP实验室

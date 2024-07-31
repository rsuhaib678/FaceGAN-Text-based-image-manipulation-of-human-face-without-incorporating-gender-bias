# FaceGAN-Text-based-image-manipulation-of-human-face-without-incorporating-gender-bias
Propose a new method called “ FaceGAN ” capable of manipulating human face images using user text prompts without incorporating gender bias.

# Video presentation

Link: https://youtu.be/SEWKMCcaeBs

# Abstract

Text-based image synthesis is a promising technique for advancing the field of image manipulation.
In this dissertation, we investigate the implementation of text-based manipulation
of human faces using StyleGAN and Contrastive Language-Image Pre-training (CLIP). Using the global direction technique, we
combined the generative power of StyleGAN and the image-text mapping ability of CLIP
. We identified 2 major challenges in the StyleCLIP method,
non-target feature manipulation and gender bias in the generated face image. We explore the
problem of gender bias in the generated image and combine the discriminator of StyleGAN with
a deep convolutional network capable of classifying gender to mitigate gender bias. We
propose this new combination as “FaceGAN”, a novel method that is capable of manipulating
human face images using text prompts from users without incorporating any gender bias.

# Dataset

1. <b> Flickr-Faces-HQ (FFHQ):</b> FFHQ is a collection of 70,000 high-quality PNG images at 1024 X 1024 resolution, with a
wide range of age, ethnicity, and image background. Link: https://paperswithcode.com/dataset/ffhq.
2. <b> UTKFace dataset:</b> This dataset consists of over 20,000 face images with annotations of age, gender, and ethnicity.
The images cover a large variation in pose, facial expression, illumination, occlusion, resolution,
etc. Link: https://paperswithcode.com/dataset/utkface.

# Libraries
1. <b>Numpy</b> is a fundamental scientific Python library helpful for quick
matrix and vector computations.
2. <b>Matplotlib</b> is a library for the Python programming language and its
NumPy numerical mathematics extension that allows for data visualization and graphical
plotting.
3. <b> Sklearn </b> is a free machine learning package for Python that
includes different clustering, regression, and classification techniques.
4. <b> Keras </b> is an open-source software library that provides a Python
interface for artificial neural networks like pre-trained CNNs.
5. <b> Pytorch </b>  is capable of accelerating tensor operations on cuda cores
and is particularly designed for deep learning jobs.
6. <b> Tensorflow </b> is a Google-developed open-source library intended
primarily for deep learning applications.

# Computing resources

The image inversion, data augmentation, and training of the CNN model will be done on a personal
computer. The University of Bath HEX GPU will be used for training the StyleGAN. Google
Colab will be used to compile all the models and test the integration of StyleGAN and CNN.


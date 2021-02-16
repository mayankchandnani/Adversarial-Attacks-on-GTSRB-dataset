# Adversarial-Attacks-on-GTSRB-dataset
Our project focuses on, creating algorithms which creates adversarial attacks on neural networks and tests the strength of these neural networks which are trained on GTSRB dataset.
Four techniques were created and tested on three different models in the
lifecycle of this project. In our first approach we created a random fuzzer that would modify the RGB values
of the pixels randomly till it misclassifies the image. For our second approach, we applied a Gaussian filter
on the images and checked for misclassification. In our third approach, we blended two images of the same
class and then applied Gaussian filter on them. For our fourth and final approach we, implemented the
FGSM method that adds noise based on gradient of the image.

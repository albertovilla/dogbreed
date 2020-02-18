# dogbreed
In the project a convolutional neural network is created to identify, based on an image, the breed of a dog. It also allows to associate a dog breed to human faces.

So basically, the project accepts a file path to an image and first determines whether the image contains a human, dog, or neither. Then,
- if a dog is detected in the image, return the predicted breed.
- if a human is detected in the image, return the resembling dog breed.
- if neither is detected in the image, provide output that indicates an error.

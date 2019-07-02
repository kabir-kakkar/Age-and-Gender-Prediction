# Age-and-Gender-Prediction

This is a Keras implementation for estimating the age and gender of a person through a real-time webcam. 

## Dependencies 
* Python 3.7
* Numpy 1.15.4
* TensorFlow 1.13.1
* Keras 2.2.4-tf
* OpenCV 3.4.1

## Demo

Here is a simple demonstration of the project.

![GIF](https://user-images.githubusercontent.com/48717801/60512919-868ec400-9cf3-11e9-9490-d2fe0de04bf0.gif)

This program runs a facial recognition system and predicits the age and gender of the person on a webcam video.

It works in the following manner: 
1. Identifies Face
2. Crops it
3. Predicts the age and gender of the person on the webcam using a placeholder for the cropped face.
4. Draws a Label around the face.
5. Displays the results.

## Models

Two models have been used here 
1. haarcascade_frontalface_alt.xml (The link is provided in the file)
2. weights.18-4.06.hdf5

The weight model can be imported from the here:
https://github.com/Tony607/Keras_age_gender/releases/download/V1.0/weights.18-4.06.hdf5

### References 

1.[DEX: Deep EXpectation of apparent age from a single image](https://www.vision.ee.ethz.ch/en/publications/papers/proceedings/eth_biwi_01229.pdf)

2.[Deep expectation of real and apparent age from a single image without facial landmarks](https://www.vision.ee.ethz.ch/en/publications/papers/articles/eth_biwi_01299.pdf)

3.[yu4u/age-gender-estimation](https://github.com/yu4u/age-gender-estimation)

4.[Tony607/Keras_age_gender](https://github.com/Tony607/Keras_age_gender)

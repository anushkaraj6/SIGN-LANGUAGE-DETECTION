# SIGN-LANGUAGE-RECOGNITION

Generally referred to as SLR, sign language recognition is a computing challenge that requires understanding sign languages. To close the communication gap experienced by those with hearing impairments, particularly in the digital world, this issue must be resolved.

## Mediapipe Framework

Two real-time deep neural network models that cooperate make up the MediaPipe ML pipeline: a face location detector that acts on the entire image, a 3D face landmark model that operates on those places and uses regression to estimate the approximate 3D surface. It enables the network to focus the majority of its resources on accurate coordinate prediction. The following are the elements of each landmark: Landmark coordinates normalised to [0.0, 1.0] by the width and height of the image, respectively, are x and y. z: The separation between the user's visibility and the camera a number between [0.0, 1.0] indicating how likely it is that the landmark will be present in the image and not be obscured.

## Methodology

- Detection of face and hand

- Detecting the landmarks of face and hand

- Generating the dataset by capturing the 3D coordinates

- Training and testing of dataset

## Task Being Done

This model is able to detect the following signs:-

- Hello
- Thanks
- Peace

## Future Scope

Currently this model can detect three signs but in future, more signs can be added. 

# Results

![Screenshot 2022-07-24 105536](https://user-images.githubusercontent.com/93306837/180633570-1948bc61-1830-43da-9222-a81153776f25.png)

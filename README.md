# TF

Main Characteristics of the model:

1. Face Detection
2. Face Recognition
3. Face Aging
4. Face Gender (Male, Female) this one is based on logitic regression, the highest probability shows if the image classifies the face 74% male and 26% female then label this image as female.
5. Ethencity
6. Multiple faces in the same photo


Backend == TF<br>
Frontend == Streamlit

Streamlit will do:

1. Accept videos
2. Predict Age, mask/no mask, gender
3. display the images from the video with red boxes gender and age prediction
4. Accuracy of the model and loss function

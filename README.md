# Covid-19-Detection

## 🧠 How We Predicted Data Using PDCOVIDNet

To predict whether a person has COVID-19 from chest X-ray images, we built and used a deep learning model called **PDCOVIDNet**. Here's how the process worked in simple terms:

1. **Collected and Prepared the Data**  
   We used a labeled dataset of chest X-ray images. The data was divided into training, validation, and test sets. Before feeding it into the model, we cleaned and resized the images and applied some transformations (like rotations and zoom) to make the model more robust.

2. **Trained the Model**  
   We designed a custom neural network and trained it using the prepared dataset. During training, the model learned to recognize patterns and features in the X-rays that are commonly associated with COVID-19, pneumonia, or healthy lungs.

3. **Tested the Model**  
   After training, we tested the model on new images it hadn't seen before to check how accurately it could classify them.

4. **Made Predictions**  
   To make a prediction, we passed an image through the trained model. The model would then analyze the image and tell us whether it thinks the person has COVID-19, pneumonia, or is healthy.

5. **Evaluated the Results**  
   Finally, we measured the model’s performance using metrics like accuracy, confusion matrix, and classification reports to see how well it was doing overall.

# NEOM-AlUla-Image-Classifier
This is a simple project to classify images between two regions from Saudi Vision 2030: NEOM and AlUla.

The model was trained using Google’s Teachable Machine on a small dataset of 12 images (6 images per region).

After training, we used Google Colab to test the model and run predictions on new images.

Files Used
Trained model file keras_model.h5

Class labels file labels.txt

Image file for testing

How to Use
Upload the model files and the test image to Google Colab.

Run the code that loads the model, processes the image, and predicts the class.

The program displays the test image along with the predicted region (NEOM or AlUla) and the confidence score.

Expected Outcome
The model identifies whether the image belongs to NEOM or AlUla and shows the prediction confidence.

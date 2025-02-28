# Movie-review-sentiment-analysis
## On IMDB dataset

### Steps:
1. Import the libraries (numpy, tensorflow)
2. Load the dataset from tensorflow.keras.datasets
3. Divide the dataset into training and testing
4. Inspect a sample review and its label
5. For own understanding, map the word index back to words
6. If mapped the word index, reverse map the index to words to decode the sample review in the next step
7. Decode the sample review to check how it looks
8. Pad the sequence to make the tensors of equal length
9. Train simple RNN model (first layer: Embedding, second layer: simple RNN, third layer: Dense layer with output)
10. Build the model and compile it with binary cross entropy (as dataset is a binary classification)
11. Check the summary of the model
12. Create an instance of earlystopping callback
13. Train the model with earlystopping callback
14. Write helper functions to preprocess the user input review
15. Create a prediction function to return sentiment (positive or negative) and the prediction score
16. Input an example review and check the prediction

##### End to end can be performed using streamlit web app and streamlit cloud.

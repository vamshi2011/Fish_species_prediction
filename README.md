# Fish_species_prediction
This projects predicts the selected species of fish(Perch ,Bream, Roach, Pike, Smelt, Parkki, Whitefish) based on its length , height , weight. We have used the K Nearest Neighbours classifier from the sklearn library.

# Required Libraries:
1. Numpy
2. Gradio
3. Pandas
4. Seaborn
5. Matplotlib
6. Knn classifier

# Features
- **Machine Learning Model**: Built using K Nearest Neighbours classifier from the scikit-learn library.
- **Prediction Interface**: A Interface that is built using the Gradio library in python allows for a easy to use userfriendly interface. We can input the different inputs(length, width, height) for the fish and get the name of the fish along with its image.

# Dataset
The dataset consists of 160 rows and 7 columns for 7 species of fish.
- Perch
- Bream
- Roach
- Pike
- Smelt
- Parkki
- Whitefish

Each sample has 7 features
- Weight
- Length1
- Length2
- Length3
- Height
- Width
- Species

# Preprocessing 
The data is scaled using the Standard Scalar Library 

# Model Training
- The K nearest neighbours model is trained using the 80% of the dataset.
- Remaining 20% is used for testing purpose
- The model is checked for different parameters such as accuracy score, precision, Recall, f1 score.

# Interface
The interface is built using the Gradio library.
Input: Enter the Weight, Length, Width
Output: The image along with the name of the fish.

# Instructions
1. **Clone the repo**
   ```bash
   git clone https://github.com/vamshi2011/Fish_species_prediction.git
   ```
2. **Launch the application**
    ```bash
   python Fish_species_prediction.py
   ```
3. The interface will open in your browser

# Open in google collab
To open the application directly in google collab , go to Fish_species_prediction file in github and click the "Open in Google collab". There you can edit the code as per your reqirements.

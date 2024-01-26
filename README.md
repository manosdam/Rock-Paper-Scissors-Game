# Rock-Paper-Scissors - Game
## Project Overview
This project develops an intelligent agent to play the Rock-Scissor-Paper game.
The agent recognizes images corresponding to Rock (0), Scissor (1), or Paper (2) and makes the winning move. It uses a dataset from Kaggle and a custom dataset of images for testing predictions.

## Implementation Details
### Libraries and Data Connection
- The project utilizes Python libraries like Pandas, NumPy, OpenCV, and Sklearn for data handling and machine learning, running on Google Colab and Google Drive.
### Data Preparation
- Images from the Kaggle dataset and a custom dataset of photos are used.
- Image processing techniques such as resizing, grayscale conversion, and normalization are applied to reduce image size and complexity.
### Machine Learning Models
- Various models like SVM, Random Forest, and KNN are tested with different hyperparameters to find the best combination.
- The models predict the corresponding move (Rock, Scissor, or Paper) based on the input image and the best combination of hyperpameters.
### Model Evaluation
- Performance is evaluated using accuracy scores, confusion matrices, classification reports, and line plots to visualize results.
- The agent's performance is tested with both the Kaggle dataset and the custom dataset, ensuring robustness and accuracy.
### Game Simulation
- The agent competes against a "Random Agent" in a series of rounds, with betting mechanics to assess financial performance.
- The Random Agent introduces complexity by applying transformations like flips and noise to the images.
### Analysis and Results
- Detailed analysis using confusion matrices, line plots, and classification reports to understand the model's performance.
- Insights into the model's strengths and weaknesses across different types of images.
### Description
- The code is created in a Google Colab Notebook, uploaded to GitHub.
- There is also a report file in the repository.
- The project explores various models, image processing techniques, and hyperparameter tuning.

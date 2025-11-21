## Title - Cat vs Dog Image Classification Using Support Vector Machine

##  Introduction

<div align="justify">
Image classification is a key task in the field of computer vision, and distinguishing between images of cats and dogs serves as a common benchmark for evaluating model performance. This project focuses on building a binary image classification system using the Support Vector Machine (SVM) algorithm to accurately classify pet images as either a cat or a dog. The dataset consists of labeled images which are first preprocessed through steps such as resizing, grayscale conversion, and feature extraction using methods like flattening or Histogram of Oriented Gradients (HOG). These processed features are then fed into an SVM model, which excels in binary classification by finding the optimal hyperplane that maximally separates the two classes. By leveraging traditional machine learning techniques, this project demonstrates how accurate image classification can be achieved without relying on complex deep learning architectures, making it both computationally efficient and interpretable. The resulting model provides reliable predictions and serves as a practical application of classical supervised learning in visual recognition tasks.
</div>

##  Structure 

├── Dataset/  # Folder containing cat and dog images

├── Models/  # Saved model files (e.g., trained SVM model)

├── Pet_Image_Classification_Code.ipynb # Main Jupyter notebook

├── Requirement.txt # List of required Python packages

## Setup Instructions

1. Clone the Repository

    Terminal - Command - Git Clone 

    https://github.com/Praisingh-Codes/Pet-Image-Recognition.git

    cd Pet-Image-Recognition


2. Create Virtual Environment

   Terminal - Command
   
   python -m venv venv
   
   (On Linux/Mac: source venv/bin/activate)

   (On Windows: venv\Scripts\activate)


3. Install Dependencies
   
   Terminal - Command
    
   pip install -r Requirements.txt


4. Download or Prepare Dataset

   Ensure the Pet_Images dataset is placed correctly in:

   Dataset/Pet_Images/  

   ├── cat/

         ├── cat001.jpg

         ├── ...

   ├── dog/
   
         ├── dog001.jpg

         └── ...
   
   Each folder (cat and dog) should contain image samples of that class. Make sure all image files are properly named and readable for training and testing the classification model.


5. Run the Jupyter Notebook
   
   Launch the notebook environment:
   
   jupyter notebook

   Open Pet_Image_Classification_Code.ipynb and run all cells to train and evaluate the model.


6. Use the Gradio Interface
   
   Run the final cell in the notebook to open the Gradio web app.

   Upload a Pet image and get predictions 

## Screenshots

#### Gradio Image Upload Page
![Upload Page](./Outcome%20Screenshots/Gradio_Upload_Interface.png)

#### Cat vs Dog Image Classifier Outcome
![Image Prediction Page](./Outcome%20Screenshots/Cat%20vs%20Dog%20Image%20Classifier%20Outcome.png)


## Conclusion

<div align="justify">
This project successfully demonstrates the application of classical machine learning techniques, specifically Support Vector Machine (SVM), for solving a binary image classification problem. By leveraging image preprocessing, feature extraction, and effective model training, the system is capable of accurately distinguishing between images of cats and dogs. The use of SVM provides a lightweight yet powerful solution, making it suitable for applications where deep learning models may be computationally intensive. Overall, the project highlights the importance of proper data preparation and feature engineering in achieving reliable performance in image classification tasks, and it serves as a strong foundation for more advanced computer vision applications.
</div>

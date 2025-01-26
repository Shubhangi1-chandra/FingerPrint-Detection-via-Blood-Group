Folder Details
code/: Contains subfolders for each model (ResNet, VGG16, AlexNet, LeNet), with Jupyter notebooks files for training and evaluation.
dataset/: Contains the main dataset with images of fingerprints categorized by blood group types (A+, A-, B+, B-, AB+, AB-, O+, O-).
graphs/: Stores accuracy, validation accuracy, loss, and validation loss graphs for each model.
performance_metrix/: Contains bar graphs comparing the performance metrics across different models.
sample dataset/: Includes a sample fingerprint image to preview the dataset.
test/: Placeholder for any testing or additional data as needed.
Getting Started
Prerequisites
Python 3.8 or later
Jupyter Notebook
PyTorch
Additional libraries listed in requirements.txt
To install required libraries, run:

pip install -r requirements.txt
Cloning the Repository
git clone https://github.com/yourusername/Fingerprint-Based-Blood-Group-Detection.git
cd Fingerprint-Based-Blood-Group-Detection
Dataset
The dataset contains fingerprint images organized into folders by blood group type. There are approximately 6,000–7,000 images spread across the eight blood group categories.

Each subfolder within dataset/datasetbloodgroup/ represents a blood group and contains fingerprint images labeled accordingly.
Ensure that you have sufficient storage space before downloading or expanding the dataset.

Models
This project explores the following CNN architectures:

ResNet
VGG16
AlexNet
LeNet
Each model has a dedicated folder under code/, with:

A Jupyter notebook (.ipynb) that contains code for training and testing.
Results
Performance metrics and training graphs are stored in separate folders for easy access and visualization.

graphs/: Includes accuracy, validation accuracy, loss, and validation loss plots for each model, which help visualize the model's performance over time.
performance_metrix/: Contains bar graphs comparing the performance of different models.
Sample Dataset
The sample dataset/ folder includes a sample fingerprint image to give users an idea of the dataset's format.

Usage
Dataset Preparation: Ensure that the dataset/ folder is populated with the required fingerprint images.

Running the Models: Navigate to the respective model folder in code/, open the Jupyter notebook, and run it step-by-step. Each notebook is designed to:

Load the dataset
Train the model on the training dataset
Evaluate the model on the test dataset
Viewing Results: After training, check the graphs/ and performance_metrix/ folders for visualizations of the training process and model comparisons.

Testing on Sample Data: You can test the model using images from the sample dataset/ or by adding additional test images to the test/ folder.

Contributing
Feel free to fork this repository, make improvements, and submit a pull request. Contributions to improve model performance, add additional blood group types, or optimize the codebase are welcome.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgments
Special thanks to the authors of the research paper that served as the foundation for this work. For details on the methodology and findings, refer to the paper included in this repository.

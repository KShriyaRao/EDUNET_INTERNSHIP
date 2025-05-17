

#  Crop and Fertilizer Recommendation System Using Machine Learning

This project, developed during the Edunet Internship, leverages machine learning to provide data-driven recommendations for optimal crop selection and fertilizer application based on soil and environmental parameters.


## Repository Structure

* **`Week_2.ipynb`**: Notebook encompassing data preprocessing, exploratory data analysis, model training, and evaluation for crop recommendation.

* **`Fertilizer_recommendation.ipynb`**: Notebook dedicated to fertilizer recommendation logic, including data handling and model implementation.

* **`crop_model.sav`**: Serialized machine learning model for crop prediction.

* **`fertilizer_model.sav`**: Serialized machine learning model for fertilizer recommendation.

* **`crop_scaler.sav`**: Scaler object used for normalizing crop-related input features.

* **`fertilizer_scaler.sav`**: Scaler object used for normalizing fertilizer-related input features.

* **`Crop_recommendation.csv`**: Dataset containing soil and environmental parameters for various crops.

* **`Fertilizer Prediction.csv`**: Dataset detailing fertilizer requirements based on soil nutrients and crop types.

* **`WEEK-1.docx`**: Document outlining theoretical concepts and foundational knowledge pertinent to the project.


## Project Overview

The system is designed to assist farmers and agricultural stakeholders in making informed decisions by:

* **Analyzing Soil and Environmental Data**: Utilizing parameters such as nitrogen (N), phosphorus (P), potassium (K), temperature, humidity, pH, and rainfall.

* **Predicting Suitable Crops**: Employing machine learning models to recommend crops best suited to the given conditions.

* **Recommending Fertilizers**: Suggesting appropriate fertilizers based on soil nutrient deficiencies and crop requirements.



## Technologies Used

* **Programming Language**: Python([Medium][1])

* **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

* **Development Environment**: Jupyter Notebook, Google Colab

* **Machine Learning Algorithms**: Decision Tree, Random Forest, K-Nearest Neighbors (KNN)

 Getting Started

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/KShriyaRao/EDUNET_INTERNSHIP.git
   ```
2. **Navigate to the Project Directory**:

   ```bash
   cd EDUNET_INTERNSHIP
   ```
3. **Install Required Libraries**:

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
4. **Open Notebooks**:

   * `Week_2.ipynb` for crop recommendation.
   * `Fertilizer_recommendation.ipynb` for fertilizer recommendation.


## Results

The implemented models demonstrate effective predictions for both crop selection and fertilizer recommendations, enhancing decision-making in agricultural practices.


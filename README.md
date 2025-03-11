# 🏠 Pune House Price Predictor

A machine learning web application that predicts house prices in Pune, India based on various features like location, size, and amenities.

![Pune House Price Predictor](https://github.com/yourusername/pune-house-price-predictor/assets/yourassetsfolder/app-screenshot.png)

## 📝 Description

This application uses a trained Linear Regression model to predict house prices in Pune. Users can input details such as location, BHK (bedroom, hall, kitchen), total area in square feet, number of bathrooms, and number of balconies to get an estimated price for the property.

## ✨ Features

- **📍 Location-based pricing**: Considers various localities across Pune
- **📊 Multiple factors**: Takes into account BHK, square footage, bathrooms, and balconies
- **🖥️ User-friendly interface**: Built with Streamlit for easy interaction
- **🎯 Accurate predictions**: Uses a trained linear regression model

## 🛠️ Tech Stack

- **🐍 Python**: Core programming language
- **🐼 Pandas**: For data manipulation and analysis
- **🔢 NumPy**: For numerical operations
- **🌊 Streamlit**: For building the web application interface
- **🧠 Scikit-learn**: For the machine learning model (contained in the pickle file)

## 🚀 Installation

1. Clone the repository
   ```
   https://github.com/keshavthakur30/house-price-predictor.git
   cd pune-house-price-predictor
   ```

2. Create a virtual environment (optional but recommended)
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use venv\Scripts\activate
   ```

3. Install the required packages
   ```
   pip install -r requirements.txt
   ```

4. Run the application
   ```
   streamlit run app.py
   ```

## 📋 Usage

1. Select a location from the dropdown menu
2. Enter the number of BHK
3. Enter the total area in square feet
4. Enter the number of bathrooms
5. Enter the number of balconies
6. Click "Predict Price" to get the estimated price in rupees

## 📊 Dataset

The model is trained on a cleaned dataset of Pune house prices (`cleaned_data.csv`). The dataset includes features such as:
- Location
- Total square footage
- Number of BHK
- Number of bathrooms
- Number of balconies

## 💡 Model

The application uses a Linear Regression model that has been trained on the Pune house price dataset. The model is saved as a pickle file (`LinearModel.pkl`).

## 📁 Files

- `app.py`: The main application file
- `cleaned_data.csv`: The cleaned dataset used for predictions
- `LinearModel.pkl`: The trained machine learning model
- `requirements.txt`: List of required packages

## 🔮 Future Improvements

- Add more features such as property age, furnishing status, etc.
- Implement more advanced algorithms for better prediction accuracy
- Add data visualization to show price trends across different locations
- Include a comparison feature to compare prices across different areas

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgements

- Pune real estate data sources
- Streamlit community for the amazing tool
- Contributors and reviewers

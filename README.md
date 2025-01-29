# Crop Yield Prediction using Random Forest Algorithm

## Project Overview
Crop Yield Prediction is a machine learning-based project aimed at helping farmers predict crop yield before cultivation. The system uses historical agricultural data, weather parameters, and soil conditions to forecast crop productivity. The prediction is performed using the Random Forest Algorithm, which is known for its high accuracy in regression tasks.

## Features
- User-friendly web-based GUI for input and output visualization.
- Machine learning model trained on historical agricultural data.
- Integration with OpenWeatherMap API to fetch live weather data.
- Support for multiple crops and soil types.
- Efficient yield forecasting using Random Forest Regression.

## Technologies Used
### Programming Languages & Frameworks
- Python (Machine Learning & Data Processing)
- HTML, CSS, JavaScript (Front-end Development)
- PHP (Backend Processing)
- XAMPP Server (Localhost Environment)

### Libraries & Packages
- NumPy (Numerical Computations)
- Pandas (Data Manipulation)
- Scikit-Learn (Machine Learning Algorithms)
- BeautifulSoup (BS4) (Web Scraping for Data Collection)
- JSON (Data Handling)

### External Services
- OpenWeatherMap API (Live Weather Data)
- Apache Server (Hosting the Web Application)

## Installation & Setup
### Prerequisites
1. Install Python (3.x recommended)
2. Install XAMPP Server
3. Install required Python packages using:
   
   ```sh
   pip install numpy pandas scikit-learn beautifulsoup4 requests flask
   ```

### Steps to Run the Project
1. Clone the repository:
   
   ```sh
   git clone https://github.com/your-username/CropYieldPrediction.git
   ```
3. Navigate to the project directory:
   
   ```sh
   cd CropYieldPrediction
   ```
5. Start XAMPP and enable Apache & MySQL services.
6. Place the backend files in the `htdocs` folder of XAMPP.
7. Run the Python script to train the model:
   
   ```sh
   python train_model.py
   ```
9. Open your web browser and visit:
    
   ```
   http://localhost/CropYieldPrediction
   ```

## How It Works
1. User Inputs: The user provides crop type, soil type, district, and area size.
2. Weather Data Retrieval: The system fetches real-time weather data from OpenWeatherMap.
3. Prediction Process: The Random Forest model processes the input and predicts yield.
4. Output Display: The predicted crop yield is displayed in the web interface.

## Dataset
The dataset consists of historical crop yield data collected from government websites. It includes:
- District-level crop production data
- Weather parameters (temperature, humidity, rainfall)
- Soil type and PH values
- Area cultivated and past yield records

## Results & Accuracy
- The Random Forest algorithm was selected due to its superior performance compared to Logistic Regression and Naïve Bayes.
- Achieved an accuracy of 73% on test data.

## Future Enhancements
- Expanding the dataset to include more geographical regions.
- Implementing multilingual support for better accessibility.
- Enhancing the web interface for improved user experience.
- Integrating soil health monitoring sensors for real-time data collection.

## Contributors
- Akshar Patel
- S Vishnu Vardhan

## Contact
For any inquiries or contributions, feel free to reach out at apcodes7@gmail.com.

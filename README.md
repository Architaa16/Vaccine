# Vaccine Adverse Reaction Prediction Platform

This repository contains a web-based application designed to provide insights into potential adverse reactions to COVID-19 vaccines based on user-specific inputs. Built with HTML, CSS, JavaScript, and Flask, the platform allows users to enter details such as age, gender, and vaccine type to receive personalized predictions on possible adverse reactions. Additionally, it includes AI-powered predictive models to assist in forecasting vaccine demand, identifying areas of low vaccination coverage, and providing personalized insights.

## Features
- **User Input for Predictions**: Users can enter their age, gender, and selected vaccine type to receive insights on potential adverse reactions.
- **AI-Powered Forecasting**: Incorporates predictive models using Scikit-learn to forecast vaccine demand and detect areas with low vaccination coverage.
- **Real-Time Data Sync**: API integrations allow for real-time data synchronization with healthcare systems, ensuring accurate, up-to-date information.
- **Seamless User Interface**: Built with HTML, CSS, and JavaScript for an intuitive user experience.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask
- **Machine Learning**: Scikit-learn for predictive modeling
- **APIs**: Integrated for real-time data syncing
- **Deployment**: Google Cloud (Free Tier) for scalable deployment

## Project Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Architaa16/Vaccine.git
   cd Vaccine
   
2. Install Required Packages Make sure you have Python installed, then run:
   ```bash
   pip install -r requirements.txt

3. Run the Application To start the application, use:
   ```bash
   python app.py

4. Access the Application Open a web browser and navigate to http://127.0.0.1:5000 to start using the platform.

## How It Works
1. **User Input**: Users fill out a form with age, gender, and vaccine type.
2. **Adverse Reaction Prediction**: The application uses the provided inputs to predict potential adverse reactions.
3. **Data Analysis and Insights**: Predictive models forecast vaccine demand and identify areas of low coverage, supporting public health efforts.
4. **Real-Time Updates**: API integration ensures data is synced with the latest healthcare information.

## Model and Predictive Insights
The predictive model is powered by Scikit-learn and leverages:

- **Demand Forecasting**: Estimating future vaccine demand to assist in inventory management.
- **Coverage Detection**: Identifying regions with lower vaccination rates to improve outreach.
- **Personalized Insights**: Offering users tailored recommendations and information on vaccine reactions.

## Future Improvements
- **Enhanced Machine Learning Models**: Integrate additional features and improve model accuracy.
- **User Authentication**: Enable secure, personalized user accounts.
- **Expanded API Integrations**: Connect with additional healthcare databases for comprehensive data coverage.

## Contact
For questions or suggestions, please reach out to:

- **Architaa Swain**: architaaswain16@gmail.com
- **Swapnil Das**: swapnildas742@gmail.com
- **Medha**: medha30ki@gmail.com



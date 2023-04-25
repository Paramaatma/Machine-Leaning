# Bike-Sharing-Linear-Regression-Model
Bike Sharing Linear Regression Model
This project aims to predict bike rental demand using linear regression. The dataset used in this project includes hourly rental data spanning two years and includes information on weather, holidays, and working days.

Requirements
Python 3.6+
Jupyter Notebook
pandas
NumPy
scikit-learn
matplotlib
Installation
Clone the repository to your local machine
Install the required packages using pip install -r requirements.txt
Open the Jupyter notebook Linear Regression Assignment.ipynb to view the code and run the project
Usage
To use this project, simply open the Jupyter notebook and run the code cells sequentially. The notebook includes explanations of each step and provides visualizations of the results.

Contributing
If you wish to contribute to this project, please create a new branch and submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
This project was completed as part of an assignment in a data science course. The original dataset was provided by a bike-sharing company.

📝 Table of Contents
General Information
Conclusions
Recommendations to improve the business
Technologies Used
📊 General Information
Multiple linear regression is performed on the dataset.
The project is done as part of coursework from IIIT-Bangalore.
We are trying to find the number of rentals issued from the company based on numerous independent values such as temperature, weather, humidity, holiday, etc.
The Boombikes bike rental dataset is being used.
📈 Conclusions
The R-squared value of the train set is 83.6% whereas the test set has a value of 80.4% which suggests that our model broadly explains the variance quite accurately on the test set and thus we can conclude that it is a good model.

The training and testing datasets suggest that the variance is accurately predicted on the test set. The p-values and VIF were used to select the significant variables. RFE was also conducted for automated selection of variables.

Equation of the best fit line is:

cnt= 0.199648 + (0.233482 * yr)-(0.098013 * holiday)+(0.491508 * temp)-(0.147977 * windspeed)-(0.066942 * spring)+(0.045280 * summer)+ (0.083084 * winter) -(0.285155 * light Rain)-(0.081558 * mist)-(0.052418 * jul)+(0.076686 * sep)

As per the final model, the top 3 predictor variables that influence bike booking are:

Temperature (Temp): A coefficient value of ‘0.491508’ indicated that temperature has a significant impact on bike rentals.
Light Rain: A coefficient value of ‘-0.2852’ indicated that light snow and rain deter people from renting out bikes.
Year (yr): A coefficient value of ‘0.2335’ indicated that year wise the rental numbers are increasing.
💡 Recommendations to improve the business
It is recommended to give utmost importance to these three variables while planning to achieve maximum bike rental booking.
As high temperature and good weather positively impacts bike rentals, it is recommended that bike availability and promotions to be increased during summer months to further increase bike rentals.

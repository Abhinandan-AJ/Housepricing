## House Pricing Prediction

**This project is created to predict the vaalue of a real-estate unit based on the below parameters.**
- CRIM     per capita crime rate by town
- ZN       proportion of residential land zoned for lots over 25,000 sq.ft.
- INDUS    proportion of non-retail business acres per town
- CHAS     Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
- NOX      nitric oxides concentration (parts per 10 million)
- RM       average number of rooms per dwelling
- AGE      proportion of owner-occupied units built prior to 1940
- DIS      weighted distances to five Boston employment centres
- RAD      index of accessibility to radial highways
- TAX      full-value property-tax rate per $10,000
- PTRATIO  pupil-teacher ratio by town
- B        1000(Bk - 0.63)^2 where Bk is the proportion of black people by town
- LSTAT    % lower status of the population

**Dataset used:** [Boston House Pricing Dataset](http://lib.stat.cmu.edu/datasets/boston)

**Model Applied:** Linear Regression

**Softwares and Tools required:**
 1. [GithubAccount](https://github.com)
 2. [HerokuAccount](https://heroku.com)
 3. [VSCodeIDE](https://code.visualstudio.com/)
 4. [POSTMAN](https://www.postman.com/)

**File Structure:**
 1. *requirements.txt:* Contains the required packages to be installed.
 2. *Boston Housing Project - Linear Regression.ipynb:* Python notebpook file.
 3. *regmodel.pkl:* Pickle file of the regression model for python app.
 4. *scaling.pkl:* Pickle file of the standardization scalar for python app.
 5. *app.py:* Python app.
 6. *Templates>>home.html:* Web page.
 7. *Procfile:* Procfile to contain gunicorn.

**R2 Score of the model:** 0.711
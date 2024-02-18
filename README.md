# CE888
RUN THE CODE IN GOOGLE COLAB: Click "File" -> "New notebook" to start a new notebook, or click "Open notebook" to access an already-existing one that is upload from computer
Upload the code: Code can be upload in colab an I have used Python language here.
Run code cells: You may use Shift + Enter or the play button located next to the code cell to run it. Colab will run the code and display the result beneath the cell.
Run code cells: You may hit Shift + Enter or click the play button  next to a code cell to put it into action. The code will run in Colab, and the result will be shown beneath the cell.
Engage the code in interaction: Code cells are editable and rerunnable as needed. Colab supports many data visualization libraries, and need to install library if it is not install previously!pip install, and gives access to GPU and TPU accelerators.
Save the work: Colab stores a copy of your notebook locally or on GitHub, but it also automatically saves it to your Google Drive.

### PROJECT DESCRIPTION:
This project is of time series analysis one where I have used the Brighton weather dataset from 2010 to 2024.
At first T have read the excel file that is provided and checked the descritive statistical and whether any missing value is present or not.
The dataset conrains lots of missing values and I have dropped the columns which contains more than 90% missing assuming that it is not important. I have filled rest of the numerical columns with mean value and finally checked whether is there any missing values or not.
Then I have done some exploratory data analysis on the columns which some plots like histograms, scatter plots, line plot, box plot and kde plots.
Then I have splitted the dataset into train, test and validation which is very important for time series data and find out the most important features.
My aim target later is to build some deep learning and time series analysis model and compare which one is performing better by using metrics like RMSE,MSE and MAPE. Finally forecast the future temperature for next 1 month or so using the data.

## Professor please suggest me whether I will use and other columns other than temperature for building the model and doing forecasting.

#### ASSUMPTIONS
1)Temporal Dependency: Given that observations are recorded at different time periods (hourly, daily, etc.), the dataset most likely displays temporal dependency. According to this hypothesis, data points that are closer in time can be more connected than those that are farther away.
2)Stationarity: When statistical attributes like mean and variance are consistent throughout time, the data may show signs of stationarity. This presumption might not apply to all variables, particularly those that are impacted by trends or seasonal patterns.
3)Missing Values: Analysis and modeling techniques may be impacted by missing values in the dataset. Appropriate handling of missing data is essential to prevent bias and guarantee the correctness of the findings.
4)The column where more than 90 percent missing values is there is not important and does not have effect on the performance of the model and so it is dropped

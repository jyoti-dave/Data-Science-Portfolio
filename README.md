# Data-Science-Portfolio
This is my data science portfolio page I have created on whatever I have learned during my masters in datascience 

## Content
### Data Exploration and Analysis:
Data Exploration and Analysis (EDA) is literally the first step in understanding raw data by employing statistical analysis to uncover hidden patterns, identify anomalies in data, validate assumptions, and understand the relationships within the data. It also helps to understand the true nature of the data by identifying areas of potential problems, which can be due to missing values or outliers. EDA essentially helps to ask questions of the data
1.	Impact of COVID-19 on Work Habit, Stress Level Productivity Change, and Health Issues
The central question for this analysis was to understand the impact of various factors, such as Stress Level, Productivity Change, and Health Issues, on Hours Worked Per Day. This inquiry aimed to explore whether higher stress levels or productivity changes were associated with longer work hours, and whether health issues play a significant role in determining how much time an individual spends working per day.	
Libraries used: numpy, pandas, matplotlib, seaborn
              Tools: Jupyter, Python
### Data Wrangling:
Data Wrangling is referred to as the process through which data is transformed and mapped from one form of raw data to another with the aim of making it more suitable for a range of uses such as analyzing it.

2.	Boston Housing Dataset
Create Histogram, ScatterPlot, Calculate mean, medium values, Add new column, Find missing values, Create data series.
Libraries used: numpy, pandas, matplotlib
Tools: Jupyter, Python

3.	Reading tabular data from a web page and creating dataframes
Preparing the data from Wikipedia
Libraries used: BeautifulSoup for web scraping and parsing HTML or XML content, pandas
  Insert data into a SQL Lite database
  Handling outliers and missing data
  Extracting the top 100 E-books from Gutenberg
  Building your own movie database by reading an API


### Data Mining/Machine Learning:
Data mining is the art of turning raw data into actionable knowledge by extracting hidden patterns, correlations, and valuable insights from massive datasets by applying techniques from machine learning, statistics, and database systems. It represents a key aspect of data analytics, enabling organizations to enhance marketing techniques, reduce costs, control risks, and understand customer behavior.

4.	Graph Analysis with Matplotlib
It provides information on electric and plug-in hybrid cars registered in Washington state.
state. It comprises information like the vehicle identification number (VIN), year, make, and model of the motor vehicle. Additionally, it entails
vehicle type, qualified clean alternative fuel vehicle (CAFV) incentives, electric range,
along with geographical information (county, city, and zip-code details). This Data Source may help understand electric vehicle usage trends in various regions
Libraries used: numpy, pandas, matplotlib, seaborn
Tools: Jupyter, Python

5.	Sentiment Analysis and Preprocessing Text and build your model
In the task of movie analysis, the application of sentiment analysis includes text preprocessing techniques such as tokenizing, removal of stop words, vectorizing, and then implementing machine learning or deep learning algorithms such as Logistic Regression, Random Forest, SVC resulting in the identification of opinions as positive, negative, or neutral, providing insight into the emotions felt, as well as script quality

Libraries used: TextBlob and SentimentIntensityAnalyzer

Tools: Jupyter, Python

In sentiment analysis, a TF-IDF (Term Frequency-Inverse Document Frequency) matrix represents
the importance of words in documents, aiding in classifying text sentiment by highlighting words
specific to a document or corpus. TF-IDF transforms text data into numerical vectors, where each row represents a document and each column represents a word (or term). The values in the matrix represent the TF-IDF scores



6.	Dimensionality Reduction and Feature Selection
Dimensionality Reduction and Feature Selection are methods in Machine Learning that deal with the reduction of the input variables in a dataset, thereby preventing the problem of Overfitting. One of the examples of usage of the above-mentioned concepts would involve the classification of mushrooms as to whether they are edible or poisonous.
7.	Loan Approval Prediction using Machine Learning
For the loan approval dataset, a strong solution would entail an iterative routine that involves data preprocessing, application of various baseline models, and then applying cross-validation techniques such as GridSearchCV or RandomizedSearchCV to determine the best baseline model out of the ones that have been tested for hyperparameter tuning. Random Forest or XGBoost models are strong candidates.
8.	Building a CNN Image Classifier
For this experiment, the Convolutional Neural Network (CNN) classifier was created and trained using the MNIST handwritten digits database. The database features 28x28 grayscale images of the digits 0 through 9. The initial five training images were viewed to ensure that they corresponded to their respective labeled values.

Prior to its use for training, preprocessed operations included scaling pixel intensity, adjusting image sizes according to the requirements of the input of a convolutional network, and encoding class targets as hot vectors. A convolutional network architecture was built employing the use of Keras. This included convolutional layers, pooling layers for dimensionality reduction, and fully connected layers for classification. Dropout was included to prevent overfitting.

### Predictive Analysis
Predictive analytics utilizes past data and patterns from machine learning and statistics that enable it to make predictions about what would happen in addition to what happened in order to assist and guarantee that decisions made in business are data oriented. It hinges upon algorithms that range from regression and decision trees and data mining that build models that find relationships between variables in order to predict unpredictable phenomena, such as credit risk or equipment failure.

9.	US Retail Sales Forecasting Analysis – Time series modeling
This analysis follows the total of monthly retail sales in the United States between January 1992 and June 2021 by applying the time series linear regression methodology. It will look at the trends of retail sales over the long term and how well the simple linear model describes these changes.
10.	Movie Recommender System
Using the MovieLens small data set, recommender system is designed that accepts a user input of movie they like (in the dataset) and recommends ten other movies for them to see.

### Data Presentation
Data presentation is the process of converting complex data into comprehensible, visual formats, such as charts, graphs, tables, or dashboards, in such a way that insights, trends, and patterns are well understood by the audience for easier comprehension, analysis, and utilization in informed decision-making. It's a pretty important stage following the analysis of data, really-one that bridges raw numbers with actionable insight-and can take textual, tabular, or diagrammatic methods.
11.	TSA Complaints
The primary target audience of this data story involves executives of airport operations, airline regulatory stakeholders, and customer service managers. They are aware of metrics on airports and customers but may not be directly involved in the day-to-day processing of complaints. Given their leadership and oversight role, visualizations are created with clear trends, comparative insights, and strategic implications. Jargon is used selectively-for example, "escalation rate," "service category"-and defined as necessary to accommodate less technical board-level viewers.
Generative AI
Generative AI (GenAI): Creates new, original material such as text, images, software code, and audio, as opposed to traditional AI tasks, such as classifying and predicting, and is the application of AI to generation, utilizing deep AI models such as the Transformer and GAN, to produce creative, natural-sounding language, as seen in ChatGPT and Dall-e.
12.	 Support Car Dealership using AI – Fine-Tuned OpenAI Model & Streamlit Application
Build your first model using OpenAI, Fine Tuning Model, The app allows users to generate car-sales content instantly using the fine-tuned model

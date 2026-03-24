# 📰 Problem Statement 
Companies want to categorize their customers into different types customer behaviors .so that , they can personalized recommendataions , offers , retention campains.

#🎯 Objective 
Build a segmentation model using k-means clustering algorithm.

It should segment customers into 3 categories (Premium, Aerage, low budget)

#⚙️ Tech Stack 
Python 
Pandas 
Matplotlib
Seabron
Scikit-learn

# 🪜Approach 

I followed following approach to build this model 

# Step-1 : Importing required libraries
Pandas , scikit-learn , matplotlib , seaborn 

# Step-2 : Data collection and inspection 
Collect data using pd.read_csv()

printing df.info() about data set , statistical analysis of data set (df.describe())

# Step-3 : Data preprocessing 
Checking null values 

# Step-4 : feature Engineering 
Performing label encoding , feature scaling

# Step-5 : modeling 
Accessing model (Kmeans())

# Step-6 : Predicting 
kmeans_model.fit_predict()

# Step-7 : Visualization 
Perfromed visual analysis using scatter() to see the number of the categories i generated 

### DEMO 
<img src="Screenshot 2026-03-21 191643.png"  alt="Description of image" width="400" height="auto">
<img src="Screenshot 2026-03-21 191728.png"  alt="Description of image" width="400" height="auto">
<img src="Screenshot 2026-03-21 191916.png"  alt="Description of image" width="400" height="auto">
<img src="Screenshot 2026-03-21 192003.png"  alt="Description of image" width="400" height="auto">

# Impact of this model on business
  ➡️Personal recommendations
  ➡️Personalized offers 
  ➡️Retention campains 
  ➡️Finding premium customers

  


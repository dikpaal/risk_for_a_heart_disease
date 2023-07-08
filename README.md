#An Investigation into the Relationship between Cholesterol Levels, Age, and Resulting Heart Disease or Lack thereof

Dataset: Heart Disease Dataset | Kaggle - https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset?resource=download

Using classification to predict whether a person who has high cholesterol levels and is older has a higher risk for a heart disease than a person with lower cholesterol levels and is younger.

Heart disease refers to a broad variety of medical problems that can impair the healthy heart's ability to pump blood, which can lead to a heart attack, stroke, or, in the worst circumstances, death. Coronary artery disease, commonly known as atherosclerosis, is the most prevalent kind of heart disease. With this illness, fatty material accumulates over time, blocking the body's arteries and preventing blood flow. If it becomes bad enough, this raises blood pressure, or hypertension, and can lead to heart attacks. A person's chance of getting atherosclerosis or heart disease can be increased by a number of variables, including age, food, and cholesterol levels. Throughout our project, we will be investigating and predicting whether or not a person is likely to develop heart disease based on their cholesterol levels and age by using the classification predictive method. We will use a heart disease dataset that contains several factors including, age, sex, and more, in order to help us answer this question.

Our predictors are going to be patient age (Age) and their cholesterol levels (in mg/dl) (Cholesterol). We are aiming to predict whether or not a person has heart disease–which is determined by the angiographic disease status–which is labeled as “HeartDisease” in the dataset. We will visualize the results through a scatterplot with our predictors Age against Cholesterol and the points will be color-coded based on the diagnosis of heart disease (HeartDisease). We will start off the cleaning of the dataset by first selecting the variables Age, Cholesterol, and HeartDisease. Then, we will convert HeartDisease to factor. We will then group the data according to the Age and HeartDisease diagnosis and summarize it by finding the mean of Cholesterol levels. At the end, we will arrange our dataset in increasing order of Age. Then we will split the cleaned dataset into training and testing sets. From here, we will conduct a K-nearest neighbor classification to predict whether a person has heart disease or not.

We hope to learn how age and high cholesterol increase a person's likelihood of developing heart disease. Individuals over 65 are more likely than younger people to have cardiovascular disease. As a person ages, changes to their heart and arteries may increase their chance of developing cardiovascular disease. Scientists now have a greater understanding of the elements that influence cardiovascular disease and the aging of our cardiovascular system. Individuals in our community, particularly those of our generation, hardly ever consume fried food on a daily basis. Instead, individuals are adopting healthy routines and including exercising. Members of this age are well conscious of the need to limit these practices and minimize health hazards. Future issues raised by these findings include: Do individuals consider their health enough before engaging in these activities? Might heart issues caused by aging be prevented with existing technology?

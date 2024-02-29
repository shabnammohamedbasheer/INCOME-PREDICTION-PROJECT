INTRODUCTION

Income classification plays a crucial role in various real-world applications, such as credit risk assessment, targeted marketing, and economic analysis. Machine learning (ML) has emerged as a powerful tool for automating and improving the accuracy of income classification. By leveraging complex algorithms and large datasets, ML models can learn the underlying patterns in income data and make intelligent predictions about individuals' income levels.

FEATURES:

age: continuous. It denotes the age of the person.

workclass: It denotes the working class of the person. Sample values: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.

fnlwgt: continuous.

education: It denotes the educational qualification of the person. Sample values: Bachelors, Somecollege, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.

education-num: continuous. It denotes the quantitative values with reference to education.

marital-status: It denotes the marital status of the person. Sample values: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.

occupation: It denotes the occupation of a person. Sample values: Tech-support, Craft-repair, Otherservice, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.

relationship: It denotes the people present in the family. Sample values: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.

race: It denotes the person’s origins. Sample values: White, Asian-Pac-Islander, Amer-IndianEskimo, Other, Black.

sex: It denotes the person's gender. Sample values: Female, Male.

capital-gain: continuous. It denotes the monitory gains by the person.

capital-loss: continuous. It denotes the monitory loss by the person.

hours-per-week: continuous. It denotes the number of working hours per week by the person.

native-country: It denotes the country to which the person belongs. Sample values: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, ElSalvador, Trinadad&Tobago, Peru, Hong, HolandNetherlands

CONCLUSION:

here for model creation i used logistic regression as the problem was based on classification

accuracy score was 76.5% and recall score 78.6% which shows the model built was a good one for classification , so that if a new data was entered it will be classified to the correct one

auc is 85% which tells A model with an AUC above 0.8 is generally considered good and can effectively distinguish between the classes. This indicates the model makes few mistakes in both classifying positive and negative cases.so the model created is a good one

As many of the features like gender , race , country , have more than 80% of data skewed to a certain point we cant clearly say how the classification goes and predict it well because mainly the data falls in US , males white people and all

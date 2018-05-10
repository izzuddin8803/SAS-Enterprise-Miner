# SAS-Enterprise-Miner
Enterprise Miner data analysis and modelling for income consensus dataset

The Census Income dataset is derived from UCI dataset archieve. The challenge from this data set is to determine the binary outcome of if a person is having an annual income more 50,000 USD or less than 50,000 USD based on the 14 variables and 32562 row of dataset.

URL link of the Census Income Data Set: https://archive.ics.uci.edu/ml/datasets/census+income

The variables consist of:

• Age = the age of the subject, interval
• Workclass = Occupation of the subject, nominal (Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked)
• Fnlwgt = ID of the subjects, ID
• Education = Level of education of the subject, ordinal (Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool)
• Education-num: Years of education that the subject has, continuous value
• Marital status: Married status of the subject, nominal (Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse)
• Occupation: The job of the subject (Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces)
• Relationship: The relationship status of the subject of the subject (Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried)
• Race: the ethnicity of the subject, nominal (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)
• Sex: The Gender of the subject, binary (Female or Male)
• Target: above 50,000 USD annual income or below 50,000 USD annual income, binary

Objective

To find best predicting model between Decision Tree and Logistic that predict if a person has annual income above $50,000 USD or below $50,000 based on the given variable

# Potential Projects/Topics for Project 2
## DATA 6545, Spring 2022

For the purpose of familiarizing you with machine learning techniques, especially modeling/evaluation, as well as preparing you for topic selection of your capstone project, I have carefully selected the following topics for competition 2. These topics cover fields including _healthcare_, _social media_, and _marketing_ analytics. Also, these topics range from __classification__ to __regression__ as for the modeling objectives.

Each group is asked to provide their ranking of the following topics. For instance, one group can rank the topics - e.g., __Topic 1__, __Topic 3__, __Topic 2__. The topic with the highest ranking will be selected as the topic for competition 2.  

Please use [this form](https://forms.gle/cknDw6qdwk2vRn4t8) to rank these topics.

## Topics:
+ __Topic 1__: [US Hospital Readmissions of Diabetes Patients](https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008)

In this project, you are going to predict if a diabetic patient is going to be readmitted from a US hospital using various features such as __demographic information__ (e.g., race, gender, age), __healthcare information__ (e.g., time in hospital, number of visits, diagnosis) and __medical information__ (e.g., lab test results). The __target feature__ is `readmitted`, and contains three classes: `<30` means the patient is readmitted within `30` days, `>30` means the patient is readmitted more than `30` days, and `No` for no record of readmission.
<!--a web user is going to make a purchase using a set of web browsing and demographic information of the user. This is a classification project - in the data the feature `Revenue` as the __target__ feature - if `Revenue` is greater than 0, then the user made a purchase (class `1`); otherwise, the user did not make a purchase (class `0`).-->

This dataset contains `70,000` instances, however it also contains some _serious_ missingness problems. [This article](https://www.hindawi.com/journals/bmri/2014/781670/) might be useful to you. 

This dataset contains `9` continuous and `20` categorical features, and `1` multi-class target. You can find the __data dictionary__ [here](https://www.hindawi.com/journals/bmri/2014/781670/tab1/). The dataset can be downloaded using this [link](https://archive.ics.uci.edu/ml/machine-learning-databases/00296/dataset_diabetes.zip). If needed I can provided the uncompressed version of the data files.

+ __Topic 2__: [Bank Tele-marketing](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)

In this project, you are going to predict if the client will subscribe a term deposit, using the information from a direct marketing campaigns (phone calls) of a Portuguese banking institution. This is a classification project (although __regression models__ can be used in it).

The dataset can be downloaded using this [link](https://archive.ics.uci.edu/ml/machine-learning-databases/00222/bank-additional.zip). This data set contains a full file (which you will use to train and evaluate your model(s)) and a much smaller sample (10% random sample, which you can use to train complicated models such as SVM or random forest). If this project is selected, I will provide the decompressed data files.
This dataset contains `10` continuous and `10` categorical features, and `1` __binary__ target. You can find the __data dictionary__ [here](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing#).

+ __Topic 3__: [In-vehicle Coupon Recommendation](https://archive.ics.uci.edu/ml/datasets/in-vehicle+coupon+recommendation)

In this project, you are going to predict if a coupon is accepted by a driver in different driving scenarios. Please refer to [this paper](https://jmlr.org/papers/volume18/16-003/16-003.pdf) for more details of this dataset, but note the paper is working on a __different__ angle. The dataset contains `34` categorical features, and one __binary__ target: `1` means the coupon is accepted, `0` means not.
<!--client will subscribe a term deposit, using the information from a direct marketing campaigns (phone calls) of a Portuguese banking institution. This is a classification project (although __regression models__ can be used in it).-->

This dataset contains `5` continuous (although that all of them are __pre-binned__) and `29` categorical features, and 1 __binary__ target (accept or not). The dataset can be downloaded using this [link](https://archive.ics.uci.edu/ml/machine-learning-databases/00603/in-vehicle-coupon-recommendation.csv). 
<!--This data set contains a full file (which you will use to train and evaluate your model(s)) and a much smaller sample (10% random sample, which you can use to train complicated models such as SVM or random forest). If this project is selected, I will provide the decompressed data files.-->


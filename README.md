# House-price-prediction-


1. DATASETS involved
    . Ms zoning - It has several features that help with the availability and reliability of applications and data
    . Ms subclass -legal document that transfers ownership of a property from the seller to the buyer and includes details about the property and rate exchanged 
    . Lot Area - The place where the Complete area is classified by Area = L × W square units
   . LotConfig-Based configuration system. No more meaningless key-checking or file creation. LOTConfig makes it easy to create, manage, and write configuration
    .BidgType - The total occupation of the family members in the accomplished area of square units
   .OverallCond- Overall condition rating depends upon the  Lotconfig and BidgType
   .Year built - Depending upon the Year of occupation the price and dependence of the area requirement gradually increases 
   .Exterior f1- The conceptional way of classifying overallcond for exterior techniques 
  . BSMT f2 -crossing individuals from the F1 generation.
  . Total BSMT Sf - sum of the exterior f1 and BSMT f2 for accurate techniques 
 . sale price -The sales price of an item is the price a buyer pays for it after any discounts have been applied. To calculate the sales price, subtract the discount amount from the original price
2.The Preprocessing involved 
   . Handling outliers - 
   Multiprocessing-A built-in module in Python that allows users to designate certain sections of code to bypass the GIL and send the code to multiple processors for simultaneous execution. 
   . Sklearn - Scikit-learn is an open source data analysis library, and the gold standard for Machine Learning (ML) in the Python ecosystem
   . Matplotlip-Matplotlib is a popular data visualization library in Python. It's often used for creating static, interactive, and animated visualizations in Python and it also involve in generating plots, histograms, bar charts, scatter plots
   .seaborn - The Seaborn library in Python is a data visualization tool that helps you create statistical graphics
 
3.MODULES and PACKAGES 
   . numpy
    .OS 
   . Glob
   . Lasso
   .Panda


4. Step by step process(description)
Step :1
The Datas involved for the house price prediction is collected from kaggle website for division of consistent event involve 
Step:2
Divide the variances as Tables for gathering more analytics conceptionals as Ms zoning,Ms subclass,Lot Area,LotConfig, BidgType, OverallCond, Year built ,Exterior f1, BSMT f2 ,Total BSMT Sf, sale price

Step:3
From python libraries using pandas for reading house price prediction, shape , sq.feet ,unit values 
Step 4
Next steps involve drop duplication inplace are true and we move to next stop to drop columId
Step5
The process of drop columnId allows for check null value . Prediction depends upon the year time intervals one of the next year is null it is hard for the conclusion of rupees of the next year ahead
Step :6
Scale on model is used for the function depending up on the package in Python which import simple input main occurrency with a strategy mean.The imputor which fit in the house is defined as sales price
Step : 7
From the library in Python The impure the works on date of frame which are not in series for a presenting single column which describe count ,mean ,standard ,minimum ,percentage maximum, 
*Rise of outliers 
When the percentage of sales value is far maximum in salary which define the difference is more so there is a need of outliers so the data point that is far from the average value of a group is used in handling the outliers 
Step : 8
Importing of matlab in Plot package as plotting in graph using pandas input of seaborn for colour and additional visualising features and we also use numphy for analysing scientific problems depending upon numerical values
Step:9
*We are using numb p for present time how is definition of lot area interpretation and mid points IQR=Q3-Q1
Lower bound = Q1-1.5*IQR
Upper bound= Q1+1.5+IQR
*The house definition and lot area if lesser than upper bond or house definition of lot area greater than lower bound 
*We are using MS Dhoni in unique ways for arranging the array such as ['RL' , 'RM', 'C(all)', 'Fv','RH'] what's depending upon the object category 
Step:10
The object category classification depend upon nominal, odinal which should not include spam
The category values classified in representation which flows of column 
Step:11
The normalisation technique in minimum maximum scalar which involved in preprocessing the range from (0 to 1) 
The random state shuffles analum back to form with independent variable as input and depended variable as output 
Step :12
The next ahead process is linear relation such as lot area and sales . In each row of classification is independent which has a quite different in sale which is depending upon the previous input of values 
So sales values is considered as linear regression 
Which have x_train,y_train independent 
Step :13 
So as a conclusion we can accomplish the required house price prediction for next ahead steps to proceed in the implementation 






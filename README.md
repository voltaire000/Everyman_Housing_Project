# Middle to Lower Class Housing Model 

### Project Statement
##### My goal is to create a reasonable reliably cost prediction model that can be used by middle to lower class home sellers in order to get a good base prediction for cost of the house without being forced to interact with a realtor

Data for this set : http://jse.amstat.org/v19n3/decock/DataDocumentation.txt<br><br>

The model will only be using Data that can be easily accessed by a normal person so no sliding scales or vague data pieces.<br><br>

The model selection deals with quite a bit of colinearity when the datapoints are chosen to be usable by the general person <br>
but there were some selections made based on pieces of data that were within .1% correlation with saleprice and had some <br>
potential relationship with the similiar datapiece. e.g. "garage_cars", "garage_sqft"<br><br>

```
project-2
|__ code
|   |__ 01 EDA.ipynb   
|   |__ 02 Data_Cleaning.ipynb   
|   |__ 03 Model.ipynb
|   |__ 04 Kaggle_Submission.ipynb
|__ data
|   |__ train.csv
|   |__ test.csv
|   |__ cleanedtrain.csv
|   |__ sample_sub_reg.csv
|   |__ submission_1-5.csv
|__ images
|__ House_pricing_Model.pdf
|__ README.md
```S
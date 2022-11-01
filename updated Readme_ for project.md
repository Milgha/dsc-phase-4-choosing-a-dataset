# Phase 4 Project
## Using Time Series in Real Estate 
Milad Ghesemi, Henry Shin, Dan Moreira

### Business Problem
We are here today because were hired by a writer for AARP to conduct a study to find the best zip codes for investing in a retirement home. Many retirees are faced with financial pressures on a fixed income, and worry about what they will leave behind for their children and grand children. Our objective was to use housing data from Zillow in order to forecast zip codes that prove to have high ROI's and publish as a feature story to share with Americans across the country.  



For applicability reasons, becasuse  not everyone wants to relocate across the country, we decided to split research into 3 regions: East Coast, South/Mid west and West coast. 

![image](https://user-images.githubusercontent.com/103558721/199138559-0bfa9543-df0f-4272-b372-6e592a63518a.png)

In our analyses of these regions, 3 states proved to be the most profitable. we found On the east coast -Homestead in Florida had a high ROI of 66%, in the South/midwest- Texas we found Austin to be the most profitable at 98% and on the West coast we have  Richmond California at 101% 

### Florida

![image](https://user-images.githubusercontent.com/103558721/199138737-c6749b9e-753e-4f34-9420-fe4e59f9595b.png)

![image](https://user-images.githubusercontent.com/103558721/199138789-0ccbd3d1-3c69-436e-bac2-70edaaf9b162.png)

![image](https://user-images.githubusercontent.com/103558721/199138848-b400619a-b062-4a6e-93dd-661aa4f70b63.png)

![image](https://user-images.githubusercontent.com/103558721/199138884-dcebf770-1a9a-4290-80a3-db7e4751308a.png)

![image](https://user-images.githubusercontent.com/103558721/199138918-4e442156-308d-4c6b-892d-80790c80e44d.png)


### Texas

![image](https://user-images.githubusercontent.com/103558721/199138945-de2d8db0-6773-40d5-8f5f-183f242680b4.png)


![image](https://user-images.githubusercontent.com/103558721/199138984-4d9371d0-5c39-418c-9e69-be52dae016ee.png)

The top 3 Texas Zip codes based on the 5 Year ROI were 2 Houston, TX zipcodes and the top one was an Austin, TX zipcode.

![image](https://user-images.githubusercontent.com/103558721/199139026-54665188-4b70-4c60-89af-209206cc750b.png)

Taking a look at the top 3 TX zipcodes from 1996-2018, their is a relatively small, steady, upwards trend until 2012, then all 3 zipcodes average prices dramatically escalates. Some reasons for this can be that Texas is a tax-free income state, which is a significant advantage, as well as lower cost of living.

![image](https://user-images.githubusercontent.com/103558721/199139097-c1e4087e-be4d-4e47-92c7-15a1b09a6c75.png)

The model for 78758 (Austin, TX) performed well as the predicted values were both in the Confidence Interval and mimicked the actual value trends. Close to 10% error difference.

![image](https://user-images.githubusercontent.com/103558721/199139121-07f597d9-5c0c-49a3-8baa-a5add60355a5.png)

The 5 year Forecasting Model projections are noteworthy as the predicted future values continue to trend positively. Ultimately, our findings are that 78758 zip code will average 98% ROI.

### California 
![image](https://user-images.githubusercontent.com/103558721/199139221-37e4a706-2c5c-48d5-b59c-66fba4c33371.png)

![image](https://user-images.githubusercontent.com/103558721/199139237-60076782-b51b-443f-9774-5e8dd498326c.png)

The top 3 CA 5 year ROI zipcodes included 2 in the bay area (Richmond, CA top performing) and one in Los Angeles, all with incredible +150% ROI's.

![image](https://user-images.githubusercontent.com/103558721/199139260-de5ba97c-cb74-4b3d-9e1a-6544c2f947e7.png)

In general, California's average zipcode price trends are alike Florida's with a strong upward trajectory from 2012-2018. This paired with Richmond's high standard of living, mild weather year round, and first class health care makes it an attractive retirement destination as well as investment opportunity.

![image](https://user-images.githubusercontent.com/103558721/199139282-92fc133f-824a-4dc4-8f92-5fe82a24d12b.png)

Here we have a case of slight overfitting from our model for 94804 (Richmond, CA). It is a positive that the prediction still follows the overall positive trend dating back to 2012 and still fits the trend on the actual 2017-2018. Ways to address this overfitting include training with more past data, ensembling(boosting and bagging methods work by combining predictions from two or more separate models),  and data augmentation, which makes a sample data look slightly different every time it is processed by the model. Ultimately this process makes each data set appear unique to the model and prevents the model from learning the characteristics of the data sets.

![image](https://user-images.githubusercontent.com/103558721/199139311-2165d497-d6d9-4aa5-84ea-e3b171cdd728.png)

Even though there was slight overfitting, the 5 Year future forecast follows the positive trend and projects bullishly. So much so, the average zipcode house price almost doubles it's ROI in 5 years and our findings forecasts a 101% ROI for Richmond."

![image](https://user-images.githubusercontent.com/103558721/199139341-72dd9a38-5c64-4930-ad61-6f256371b666.png)


To conclude our recommendations, we found Homestread, Florida with ROI 66%, Austin Texas at 98% and Richmond CA at 101% are recommendable investments


#### For the future we’d like to take into consideration how the Pandemic has affected the volatility of the market including interest rates and inflation. Also the Quality City amenities as well as Costs of living and state tax rates 



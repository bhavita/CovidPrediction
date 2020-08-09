# CovidPrediction
Proof of concept for COVID-19 prediction using Patient's X-ray for analysis.

**Disclaimer**: I am not a medical researcher or a doctor. This work is only intended as a source of inspiration for further studies and to showcase the role of ML in medical assistance.

**Inspiration** : 
I recently faced a major problem, where my family member was given a wrong diagnosis and declared COVID +ve based on d-dimer test and due to the long wait of COVID-19 testing, (there was a wait of 2 days for test results and 1 day for test to be conducted). Crazy right? During this time, while we wait for results, we got X-Ray undertaken which helped us prove the wrong diagnosis early. This is when I started to research more on this parameterial aspect of COVID predicton.

**DataSets utilized for predictions**
 - For COVID-19 Positive cases  
 [IEEE8023 COVID Chest X-RAY database](https://github.com/ieee8023/covid-chestxray-dataset)  
 
	 [Dr. Joseph Paul Cohen, Postdoctoral Fellow at University of Montreal](https://josephpcohen.com/w/), recently open sourced this [database](https://github.com/ieee8023/covid-chestxray-dataset) containing chest x-ray pictures of patients suffering from the COVID-19 disease. 
	
	
 - For COVID-19 Negative cases (Healthy cases) 
    KAGGLE - Chest-xrays-pneumonia
	[https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

	So positive cases were determined by Dr Joseph's database. For negative cases, kaggle had previously open sourced the database of patients having pneumonia. This database came to rescue in preparation of our healthy dataset for the classification.

    Implementation -> [CovidXrayDataSet.ipynb](https://github.com/bhavita/CovidPrediction/blob/master/CovidXrayDataSet.ipynb)



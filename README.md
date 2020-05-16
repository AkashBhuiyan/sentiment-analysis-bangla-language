# Sentiment Analysis of Bangla Language

Here, I describe a system that can classify opinion of different sentiment from Bangla text. The data has manually built on Bangla text corpus by Facebook graph api from Facebook page Bangla newspaper Prothom Alo. Then the 80% of total sentences is used for training and the remaining 20% for testing the classifiers. There are 3 categories are used as labels. They are positive(pos), negative(neg) and neutral. N-Gram approach is used for vectorization. The total dataset length is 2419 rows.

### Create environment by conda
> conda create -n sa python=3.6<br/>
> conda activate sa<br/>

### Installation:
> pip install sklearn==0.22.2<br/>
> pip install numpy==1.18.2<br/>
> pip install scipy==1.4.1<br/>
> pip install pandas==0.24.2<br/>
> pip install matplotlib==2.2.2<br/>
> pip install seaborn==0.9.0<br/>
> pip install yellowbrick==1.1<br/>
> pip install pydot==1.4.1<br/>


#### Note:
Here I have been described about how doing sentiment analysis of Bangla language. I did not do any optimization here.

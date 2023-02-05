# medical-callback-data-analytics
This is an ongoing project using real medical administrative data about scheduling patients for clinical studies.  
The company is looking for insights into how to mitigate scheduling churn


#update
well, turns out factorize and encoder library method don't do the same thing and return different mappings of columns and data.
this set me back for a bit till I recognized this as a possible issue.
Encoder is specifically used for preparing data for ML.  Factorize, which is what I was wanting to use, maps categories to numeric values. 
I wanted to do this mapping to see possible correlations using the 'heatmap' plasma in Seaborn

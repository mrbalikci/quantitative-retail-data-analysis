# Quantitative Analysis of A Large Retail Data Set 

A large retail data set is analyzed, correlations between columns discovered, time series charts generated, hypothesis testing tested, and insights for cases were determined.  

### DATA INSIGHTS
1.	Proper libraries were imported 
a.	Plotly library used for some since for too many data points and a better looking plots 
2.	Data was converted to a data frame
3.	Data types observed along with non-null value counts 
4.	Some NaNs and duplicate values were replaced with appropriate values 
5.	Time related columns converted to DateTime format
6.	Data Insights: Each cases were analyzed along with case expectations and findings 

### Possible Cases 

* CASE 1: Exploring Total number of cases over time (Mnfcture_wk) to see if there is a particular spike at any point in time. This could point to some issues in the manufacturing process/batch related to the weeks and help identify the root causes.
-	The analysis above could be done in more granular levels, say per product type, issue type etc, topic category etc.
* CASE 2:  We can come up with a time-series model to predict the number of parts required by using parts_ct. This can be done per region/country/parts_sent.
* CASE 3: We can look into the correlations between agent_tenure_indays and parts_ct, contact_manager_flg, repeat_ct etc. to understand where the new agents are struggling. We can add another dimension for topic category to see if some topics are harder to identify for the new agents than others.
* CASE 4:  We can look into the correlation between the repeat_ct and contact_type to see if some communication channels are more effective than others.
* CASE 5:  We can look into the correlation between diagnostics and repeat_ct to see if diagnostics are helpful to the agents. We can run a hypothesis testing to see if the effect is significant.
* CASE 6:  We can look into the relation between the time after manufacturing till contact week and topic parts_sent to see what parts are failing when.
* CASE 7:  We can look into if people are contacting the support right before their warranty expires.
* CASE 8:  We can look into the correlation between topic_category and repeat_ct to see if some problem types especially lead t

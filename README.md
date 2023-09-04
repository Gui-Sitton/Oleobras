# Oleobras

You work for the mining company Oleobrás. Your task is to find the best place for a new well.

Steps to choose the location:

Collect the parameters of oil wells in the selected region: the quality of the oil and the volume of reserves;
Build a model to predict the volume of reserves in the new wells;
Choose the oil wells with the highest estimated values;
Choose the region with the highest total profit for the selected oil wells.
You have data on oil samples from three regions. The parameters of each oil well in the region are already known. Build a model that will help you choose the region with the highest profit margin. Use the Bootstrapping technique to analyze potential profit and risks

Conditions

Only linear regression can be used to train the model (the rest are not predictive enough).
When exploring the region, a study of 500 points is carried out and the best 200 points are selected to calculate the profit.
The budget for developing 200 oil wells is 100 million dollars.
A barrel of crude oil brings in 4.5 dollars in revenue. The revenue from one unit of product is 4,500 dollars (the volume of reserves is in thousands of barrels).
Once you have assessed the risks, keep only those regions with a risk of loss of less than 2.5%. Among those that fit the criteria, you need to select the region with the highest average profit.
The data is synthetic and does not include any details of contracts or well characteristics.

**Conclusion**
* The second region obtained the best results in terms of average profit, confidence interval and risk of loss.
* The Third Region behaved very similarly to the First. Compared to the Second Region, the Second Region obtained better results in the most important tests, such as the bootstrapping technique, because I believe that when choosing a region, you should consider the whole region and not just the best results. The Second Region's behavior is different from the others because its 'population' is arranged differently in the graphs. I believe that this made the Second Region do better in the bootstrap and consequently be the region chosen because it has more average profit, a better confinement interval and, above all, the lowest percentage of loss.

**The region chosen was the Second**

**In the reading today (Stevens et al.) the authors use a technique to produce a high resolution description of the distribution of human populations across the globe. What is the name of the technique and describe in general and basic terms how it works?**

Steven's et. al use a "Random Forest" estimation technique in order to predict the population density of an area at ~100m resolution. This can be used to reinforce census data in a region as it gives a good idea of the population density of an area. Their method uses publicly available geospatial data in order to make a base dasymetric analysis of an area, then they apply their technique to create a gridded map of said area. This gridded map is used as a basis for another dasymetric redistribution, however, this time for countrywide census data. 



**In general terms, what is a machine learning algorithm? Within the context of this study what distinguishes a data science, machine learning method (such as random forest) from previous classical statistical approaches to describing and analyzing phenomenon and events?**

Machine learning algorithms are programs that take preexisting data for a region and analyze it for patterns. This pattern analysis is the real "learning" in the algorithm. As the algorithm gains more data, it can make more accurate predictions of an area or future sets of data. Machine learning algorithms are different from previous classical statistical approaches as they use vast amounts of data, and do so rapidly allowing for these predictions to be made. 

**What were these geospatial covariates and approximately how big of a data set did they represent (in general terms)? What is the significance of big data in the estimation of machine learning methods for inferring the correlates and drivers of human population distributions?**

In this study they use preexisting census data as a covariate, as it allows the machine learning algorithm (MLA) to have data to begin with. Big data is crucial for the inference of correlates and drivers of population distributions as it allows the program to compare data from a wide variety of sources. This comparison between sources allows the algorithm to account for many covariates, as well as confounding variables simply by increasing sample size of data. This increase of sample size also allows the algorithm to reduce its uncertainty in predictions since it has greater than N=10 data points or subjects. 

**The authors’ results present a remarkable improvement over previous geospatial descriptions at very high resolution, of the distribution of the human population. Within the context of human development in LMICs, what is the significance of having a highly accurate description of where each person is located across planet earth?**

The highly accurate description is deeply useful when deciding the allocation of resources among impoverished or otherwise in need areas. Additionally, it can help to track the spread and impact of potential and present problems. By having this distribution, for example, epidemiologists can make predictions about which areas will be hit hardest by a virus, or meteorologists could make predictions about which zones will be hardest hit by natural disasters. 

**Within the context of human development in LMICs, what is the relevance to your area of investigation in having a highly accurate description of where each household and person is located across planet earth?**

In the context of the water crisis in the Middle East, knowing the population density and number of people in a given area can be hugely beneficial when examining the affects of water shortages and surpluses. Additionally, this mapping can help us to see how access to water influences population distributions. 
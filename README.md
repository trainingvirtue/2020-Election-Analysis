# 2020-Election-Analysis

An analysis of 20 years worth of election/census data were created for all 3000 US counties. They show that counties that used Dominion systems had an inexplicable shift away from Trump of .6% of all votes. Swing state counties using Dominion switches 1.8%. This adds up to roughly 290k votes across swing states. 

We've done an analysis of the 20 years worth of election and census data, constructing longitudinal predictive models of election results for all 3000 US counties. These models include election data, turnout data, ratio of independent voters, rurality, suburbanicity, and more. We also tested traditional census demographic data. All of these models have R-Squared predictive indices over 95%. Unique among all models, the 2020 model has a highly statistically significant effect (p less than .001) against Trump among the states that used the Dominion systems. Digging further into the swing states there is a larger and more statistically significant effect.  It is important to note that this effect was not observed for prior elections, only the 2020 election.  As you can see from the final model among swing states, there is an inexplicable 1.8% switch away from Trump.  Across 348 counties, with an average population of 47,000, this adds up to 295,000 votes.  That is more than the entire margin between Trump and Biden across the swing states right now!  We have uploaded a .CSV file with the county-level election and census data. We have also uploaded a number of screenshots of the analysis which are listed below:

Figure 1A shows the result of the 2016 election model. 

Figure 1B shows the result of the above model with the Dominion/Diebold Systems (dss). Note that this variable was not at all close to being statistically significant.

Figure 2A shows the result of the 2020 model.

Figure 2B shows the result of the 2020 model with the Dominion variable included. As you can see it is statistically significant.

Figure 2C shows the results narrowing down to the effect of Dominion, only on the swing states, which you can see is much larger. 

Figure 3 shows summary characteristics of residuals from the model in Figure 2A by swing vs non-swing state and Dominion vs non-Dominon county. Essentially, the swing state counties went consistently to Trump above what the model predicted. This is the landslide that we all saw in the early evening of November 3rd. The errors completely reverse, however, among the Dominion counties. 

Figure 4 shows the total vote by swing vs non-swing state and Dominion vs non-Dominion. This shows that the average swing state Dominion county had a voter population of 46,756.

Given the model results and the size of the counties, we can calculate that 1.81% x 46,756 = 846 lost Trump votes per county. If we multiply this by the 348 counties, we calculate 294,507 lost votes for Donald Trump. This is more than the total lead for Joe Biden across the swing states. Please post and disseminate the attached summary figure anywhere you'd like!

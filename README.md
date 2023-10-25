# houselessstrategies

PowerBI DashBoard Link

provide link

Table of Contents

-PowerBI Dashboard
-Summary
-Terminology 
-Question
-Data Sources
-Problems and Hurdles
-Technologies Used

Summary

Residing in a prosperous developed nation, the existence of a homeless population has always left me perplexed. This project aims to investigate the strategies employed by our country to combat this crisis and determine which programs have shown higher rates of success over time. Specifically, the project will probe into documented strategies for assisting individuals without homes between 2014 and 2022. The primary objective is to analyze which programs are more effective and to make recommendations of the number of programs necessary to meet the total need of the population, based on the current number of available programs. This information will serve as valuable guidance for those dedicated to serving their communities, offering insights into what it takes to address the crisis effectively within their respective states.

During my childhood, my mother used to bring me to food banks and soup kitchens. As a child, I didn't fully comprehend the potential impact of our actions on others, which sometimes made my participation reluctant. Now, as an adult, I've witnessed the turmoil in our country's communities, prompting me to contemplate how I can make incremental contributions to address this issue. While I understand that tackling this problem single-handedly won't bring about sweeping change, I believe that by directing my newly acquired skills towards projects like this one, I can eventually create a positive influence on the lives of others throughout my career.

Terminology

HMIS- Homeless management information systems
HUD-Housing of Urban Development
COC-Continuum of Care Program
ES-Emergency Shelters
TH-Transitional Housing
SH-Safe Havens
RRH-Rapid Response housing
PSH-Permanent supportive housing

Question

This project aims to address the strategies employed in tackling homelessness and to discern which programs have exhibited greater effectiveness. The programs are categorized into two distinct groups: short-term initiatives, encompassing Emergency Shelters (ES), Transitional Housing (TH), and Safe Havens (SH), and long-term initiatives, including Rapid Response Housing (RRH) and Permanent Supportive Housing (PSH). The principal objective is to address fundamental questions: which programs have demonstrated the highest efficacy, what trends have surfaced over time, and, considering the total homeless population in the state, how many programs would be required to comprehensively address the homelessness crisis within the state.

Data Sources
1) U.S. Department of Housing and Urban Development (HUD) 
      https://www.hudexchange.info/resource/3031/pit-and-hic-data-since-2007/
	*For finding information on the Homelessness programs by year and state. * 
2) U.S. Department of Housing and Urban Development (HUD) 
      https://www.hudexchange.info/programs/coc/coc-homeless-populations-and-subpopulations-reports/
	*For finding information on total homeless populations in the U.S. by state and year. *
3) U.S. HUD Exchange
      https://www.hudexchange.info/programs/coc/
	*For finding information on common terms used. *

Problems and Hurdles

To examine the data, I had to procure and structure the statistics pertaining to the total homeless population in the U.S. by state and year, and subsequently import this data into Excel. This dataset will play a pivotal role in facilitating my evaluation, ultimately aiding me in formulating recommendations in the future.

The reporting process for homeless programs has undergone significant transformations over the years. The data collection period spans from 2007 to 2022. During the 2007-2012 period, data was collected using methodologies that were not consistent with those utilized in subsequent years. By 2013, substantial alterations were made in how the U.S. HUD reported this data, incorporating categories that were absent in both previous and future years. The period from 2014 to 2022 presents a more coherent dataset that allows for easier comparisons among the various program types and their respective categories. Due to this consistency, I have chosen to focus my analysis on the years from 2014 to 2022 for greater clarity.

Given that the data did not inherently provide an equation for making recommendations, I had to devise a formula for determining the number of programs necessary to address the entire population served. My approach involved retrieving the short-term & long-term initiative HMIS participation rates for populations currently served, dividing these rates by the number of programs, and subsequently dividing 1 (to represent 100 percent participation) by the prior result. This calculation yielded the number of programs required for the state to comprehensively address the homelessness crisis, encompassing both short-term and long-term initiatives. 

Technologies Used

1) Python: Primary use of python (Jupyter Notebook) was for the process of cleaning raw data and configuring the data into a single notebook for later visualization. 

2) Excel: Primary use of excel was for adding information regarding total homeless populations, and for the purposes of cleaning.

3) PowerBI: Primary use was for the creation of visuals and an interactive dashboard after the data had been cleaned and configured.
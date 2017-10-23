# Proposing A Survey Study









### Overall Design and Rationalization

To operationalize the wedge, it is necessary to compare the survey-reported perception of diabetic health and actual ones documented during physician visits, which require linkage between survey data and observational data via Patient ID. The traditional survey will allow me to do this. Phone and in-person interviews are common practice for survey studies in the field of medicine for privacy considerations, and mine will be no exception to IRB protocols. Another benefit of traditional survey in addition to sample-matching is that it can be always-on and longitudinal. As mentioned in my observational study proposal, the study can continue for as long as Joslin Diabetes Center is open for business, and as long as the funding allows for research assistants to conduct those interviews. 

The rationale behind using EMA to study tech-savviness is threefold. First, by definition it targets my target population perfectly -- Type II diabetes patients who are tech-savvy. Second, it measures the current state of my respondents (current perception of health and intention to be compliant) at the appropriate time (e.g, time to take the medicine or measure a1c level) and place (diabetes-related platforms). Third, the necessity in conducting this survey instead of asking respondents in the traditional survey to self-report their tech-savviness is to 1) avoid self-reported bias 2) obtain a larger sample size for more generalizable results. 


### Survey Design
The surveys will be created on Qualtrics.

For the EMA study, the respondents will be prompted to answer the following questions, supplemented by demographic information (the most explanatory features identified in the observational model) filling at the end. All respondents will be filtered by a gate-keeping question: *Are you a Type II diabetic patient?* Only answering yes to this question will allow the respondent to answer the ensuing ones.

1. When was your last visit to your physician?
1. What was your a1c and BMI level measured during that visit?
1. Were you diagnosed of any complications during that visit?
1. What a1c and BMI level do you think you have right now?
1. Do you think you have any complication now?
1. Have you ever missed your physician visit? 
1. If yes how many?
1. Will you comply by your future scheduled doctors' appointments? 
1. If no, why not?
1. Do you use any other diabetes-related channels?

***This survey will be designed so that no respondent will have to spend more than 3-5 minutes on it.***

##### Traditional Survey
Similarly, the respondents of the traditional survey will be prompted to answer the following questions:

1. What is your perceived a1c and BMI level?
2. Do you think you have any complications? Or do you predict there to be any complications during your next physician visit?
1. Will you comply by your future scheduled doctors' appointments? 
1. If no, why not?
2. Do you use technological diabetes management tools? 


#### Distribution Channels

##### EMA
Sponsored advertisements will appear on technological diabetes management tools like Glooko, Health2Sync, major US diabetes forums like *diabetes daily*, and major newspapers on diabetes, and etc. 




| Population Type   |      EMA Survey Study      |  Traditional Survey Study  |
|:----------:|:--------:|:------:|
| Target Population   |  Type II diabetes patients in the US | Type II diabetes patients in the US  |
| Frame Population   |    Type II diabetes patients that are tech-savvy and use the platforms described in **Distribution Channels**.    |   Patients on record at Joslin Diabetes Centers from the *Observational Study* for any number of years.   |
| Sample Population   | Users of the aforementioned channels who read our sponsored messages for the survey. |   Portion of the sample population that research assistants are able to contact.

### Analyses

#### Data Integration and Cleaning
For the traditional survey, I will create a new dataset linking the patient response form the traditional survey to their clinical measures and complication outcomes from the big dataset described in my first assignment, via Patient ID. For both surveys, I will also code the response into dummy variables (save the open-ended questions). 

#### Quantitative Data analyses

***Are tech-savvy patients more likely to be compliant? Do they have less of a wedge?***

The two populations that I will compare the measures between are 1) the respondents to the EMA study 2) the respondents to the traditional survey who report not to use the technological tools for diabetes management. Descriptive statistics and statistical tests will be performed to see if there are significant differences between the two populations in their self-reported decisions to be compliant (Q8 for EMA and Q3 for Traditional Survey), and the wedge (Q2-5 for EMA, and Q1-2 + observational data for Traditional Survey). 

***How do the above-mentioned results differ amongst different demographic groups?***

With the reported demographic data, I can repeat the statistical analyses mentioned above across different demographic groups identified from my previous big-data study.

***How does the wedge influence their decision to be compliant and their clinical outcomes?***

Within the population of traditional survey respondents, I will integrate the *wedge* as a feature into the regressions and predictive models described in my previous assignment, and see if it is a significant causal factor.


#### Open-ended Questions

As addressed in my previous assignment, the target population is Type II diabetes patients in US while the participants in my traditional survey study will be patients in Massachusetts. Given the demographic information of US and Massachusetts provided by US census, I can do non-probability sampling by putting different weights in different demographic groups, if such geographical difference turn out to yield bias.

For the EMA study, the most salient coverage error is that the participants in the study are more tech-savvy. However, that is exactly the design of this research.



Monetary rewards will be offered upon completion of the survey. I am also making the survey short enough so that no self-selected free people are much more likely to answer the survey. The number of research assistants will decide the scope of respondents the study will be able to reach, and how much effort will be put into recruiting each respondent. Thus, reducing non-response error will be dependent on fundings. 

#### 4. Measurement Error
Patients might interpret the questions in assessing their current perception of diabetic health differently. I will adjust the wording if measurement error proves itself to be salient. 

Another source of measurement error is that for the EMA study, patients' compliance is operationalized as their self-reported intent to be compliant, while the traditional survey study operationalizes it to be the no_show rate of real clinical data. For fair comparison I will compare Q8 and Q3 results respectively from the two surveys, and leave no_show rate only for model building.





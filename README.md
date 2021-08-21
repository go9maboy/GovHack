# GovHack by Team LockDown
<img src="logo1.png" alt="My cool logo"/>

### Simple, Easy, and Friendly Support System That Reaching Out To You First

<img src="Screen Shot.png" alt="AppScreenshot"/>

Cuddle is a mental health service that is design to guide our citizen to find a right service quickly and easily.

Current Support System expects people to know their current mental status and expect to search for a right sevice themself.
This can be very daunting task for those who are not feeling 100% mentally.

In constrast, the Cuddle first estimates 5 most commonly occuring mental diseases based on user's age, gender, and ethnicity.
It displays percentage of people in your group who are also suffering from similar diseases. 
This helps users to open up their feelings and emotion and encourage them to step out and try to get help. 
Knowing you are not alone could help users to increase their awareness and reducing their shamefulness.
Based on the estimate, Cuddle recommands a simple customized survey to diagonos the disease better.
Then, it finally provides the right support service to the patient.

## Background
Cuddle makes statistical prediction based on previously collected health dataset.
The research shows there are strong dependency between mental disease and person's age, gender, ethnicity, and etc.

### Used Dataset
- 2018 Census population and dwelling counts:
Used to obtain age group distribution, gender group distribution, and ethnic group distribution in NZ. Used those and health datasets to calculate the probability of suffering from mental diseases given age, gender, and ethnicity.
[link](https://www.stats.govt.nz/information-releases/2018-census-population-and-dwelling-counts)

- Mental Health and Addiction 2018 - 2019:
Used to extract the conditional probabilities of suffering from 17 listed mental disorders based on age, gender, and ethnicity.
[link](https://www.health.govt.nz/publication/mental-health-and-addiction-service-use-2018-19-tables)

## Challenges
1. Mining from a vast dataset and reformating the necessary data from NZ Health organizations and NZ Census
2. Extracting the meanings out by manipulating and combining multiple datasets.
3. Use statistical techniques for predicting the diseases likelihood.
4. Designing and implementing a simple and easy interface for the user.
5. Effectively displayig information to the users and encourage them to take next diagonosis survey.

## Future works
Due to limited access and availability of publicly database, we could not extend our prediction beyond age, gender, and ethnicity.
It could be interesting to include income, residential region, job status/type, and etc., into mental disease estimation.

## Motivation
In New Zealand, one in five people experience depression at some stage in their life.
One of my own family member suffered severe depression. It is extremely common to feel depressed. Yet, it is often very hard to realize your current condition yourself.
Even if you realize something is not right about your mental health, it is hard to get help due to lack of motivation, embarassment, misunderstanding, and fear of cost of treatment. We envision that we can help more people by predicting their potential mental diseases and show you are not the only one suffering from these. Then, we direct you to all freely available support or goverment subsidized services that can help you to get over this mental diseases and live your life again.

## Team Members
We are a team LockDown.
In lockdown, we all need a good Cuddle.
[Jun Junghyun](https://www.linkedin.com/in/junjunghyun), 
Ahn Joo-Hyun, 
and Changeun Noah Song

## References
We got lots of information from following links and publications

[Health Navigator NZ](https://www.healthnavigator.org.nz/support/m/mental-health/), 
[Ministry of Health NZ](https://www.health.govt.nz/your-health/services-and-support/health-care-services/mental-health-services/mental-health-services-where-get-help), 
[Aunty Dee](https://www.auntydee.co.nz/tips-and-help), 
[Mental Health and Addiction](https://mentalhealth.inquiry.govt.nz/inquiry-report/he-ara-oranga/chapter-3-what-we-think/3-2-our-conclusions/), 
[New Zealand Government Health](https://www.govt.nz/browse/health/help-with-mental-health-and-addiction/), 
[Mental Health Foundation](https://mentalhealth.org.nz/helplines), 
[HHS.Gov](https://www.hhs.gov/hipaa/for-professionals/faq/mental-health/index.html), 
[Safety Culture](https://blog.safetyculture.com/industry-trends/the-striking-role-mental-health-plays-in-construction), 
[Small Steps](https://depression.org.nz/is-it-depression-anxiety/self-test/anxiety-test/#), 

# Case Study: Data Driven Transformation of Springfield's Police Force

##  Problem Statement

Springfield, Virginia in the United States of America has been collecting data on the crimes that have been occurring in the city boundaries between 1998 and 2019. The data includes details on the offender, the nature of the crime, the location of the crime, and further details. The dataset contains over 23,000 instances of crimes which have occurred.

Due to increasing negative media attention, there is a growing perception by the citizens of Springfield that they are no longer safe. They are starting to complain and resent the elected officials. Because next year is an election year, the Mayor, Mayor Jones, is growing increasingly concerned about the social welfare of the citizens she is responsible for. Mayor Jones has previously delegated the responsibility of the crime portfolio to her police chief, Chief Odinson. It is Chief Odinson’s responsibility to run the entire police force across the areas within Springfield: Central Springfield (postal code: 22150), North Springfield (postal code: 22151), and West Springfield (postal code: 22152).

Mayor Jones organised to meet with Chief Odinson to gather the information she needed to transform the city. When she met with Chief Odinson, the Chief was perplexed, he was unsure on how to gather the information the Mayor required. The Chief did know that the police officers in each precinct within each area completed reports about every case (some initiated by the victim, others by witnesses). He also knew that the data on the reports was inputted into an Excel file. Yet, he was not sure on how to extract what he needed from the data file.

Recognising his uncertainty and wanting to provide the necessary information to the Mayor, Chief Odinson decided to hire your team of consultants to see how they can best leverage the data that the Chief had access to. Yet, rather than just finding the information to assist Mayor Jones, the Chief decided to take this opportunity to improve how he manages the police. He also met with Police Officer, Sergeant Steve Rogers to see if there is anything data-related that could help the Sergeant perform his duties. Sergeant Rogers informed the Chief that many of his fellow police officers of the Springfield Police Department required more information to understand the nature of the crimes in the area, so that they can be better equipped to respond.

## Stakeholder Groups

1. **Mayor Jones** – to improve societal issues surrounding crimes (focus on all suburbs overall).
2. **Chief Odinson** – to manage the Springfield Police Department in Central Springfield, North Springfield, and West Springfield (compare the three suburbs).
3. **Sergeant Rogers** – to be more informed of the crimes in the local areas (focus on one suburb only).

## Tasks

- Identify one problem area and visualise the data from each stakeholder perspective.
- Use three different chart types, one for each stakeholder.
- Develop visualisation that can facilitate quick cognition and lead to a fact-based conclusion or assertion. 
- Provide data-driven recommendations relative to the case study context and problem areas.


## Tableau Dashboard Reveal and Walkthrough ✨

Click to interact with the dashboard: [Crime in Springfield](dashboard.html)

![tableau](dashboard.PNG)


## Findings and Recommendations

> **Identified Problem**: Prevalence of underreporting and teenage schoolyard assault issue in Springfield. There has been a notable trend in teenage victims not reporting crimes and increased teenage assault committed by schoolmates.

As the Mayor is concerned about how to increase the safety of citizens in Springfield, it would be helpful for her to know crime sources and when victims tend not to report themselves. Looking at the top chart, verbal threat assault is the most dominant crime channel and has the highest unreported rate – an average 77% over the 20 years and 76% over the last year. The large share of unreported verbal violence could indicate that people are not educated enough on verbal assault, not knowing when to see them as crimes and how to address them. The unreported rate is higher than the reported rate, indicating an increasing privacy concern. A solution to this can be using a violence counselling hotline to foster awareness of verbal threats and support citizens at risk of violence. To encourage reporting and instil public trust, it should be conveyed to people that data are securely encrypted, and that data can help make Springfield safer.

A treemap was created to help the Chief see the crime trends over the three suburbs in relation to victim age. The largest grid shows that verbal assault is still the most popular in all three suburbs. Over the last year, verbal threats, simple assault with injury, and assault with weapon showed a slightly higher number in North Springfield than in central Springfield. As we narrow the age to 12-18, we also can see a higher disparity in verbal threats and simple assault with injury between the two suburbs, with North having almost two-fold the crime counts of the central. Therefore, police should allocate resources to North Springfield to solve teenage crime and look further into victim-offender relationships and other contextual information.

Hence, a third graph focused on North Springfield can help sergeant rogers manage crime in the local area. For victims aged over 19, more crimes have taken place in a private location with a higher unreport number. For teenagers, most crimes were in a public area, and most victims did not report violence. These trends persist when the filter is applied to verbal threat assault and simple assault with injury, noting that these two methods form most of the teenage crime distribution. The color shows that most teenage victims were victims of their schoolmates, inferring that schools are the most common setting for teenage violence.

To address this, Mayor can start a school-based program by engaging police in promoting school crime reporting and delivering education materials concerning violence prevention. Mentoring and restorative conferencing can be held in a safe and intimate setting within the school to offer juvenile offenders a remedial opportunity for moral development. Afterall, mayor should recognise that these youth offenders can approach more aggravated crime methods as they grow up if they are not well educated on crimes.

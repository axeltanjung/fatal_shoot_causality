# Evaluating the Impact of Policy Interventions on Fatal Police Shootings: 

1.	Introduction and Background

Fatal police shootings have been a source of deep concern and intense public scrutiny in the United States, sparking critical discussions about police accountability, racial injustice, and the role of law enforcement in society. The killing of Michael Brown in Ferguson, Missouri, in 2014 was a flashpoint that led to widespread protests, highlighted by the emergence of the Black Lives Matter movement, which called for systemic reform and transparency in policing. In response, The Washington Post began tracking police-involved fatalities in 2015, capturing extensive details about each incident, including the race of the deceased, the circumstances surrounding the shooting, and whether the victim was armed or experiencing a mental health crisis. This effort sought to fill gaps in government data and provide the public with a clearer picture of police use of lethal force. 
The Washington Post’s database has become one of the most comprehensive and widely referenced sources of information on police-involved fatalities in the U.S., complementing existing but incomplete records maintained by federal agencies like the FBI and the Centers for Disease Control and Prevention (CDC). According to The Post’s findings, more than twice as many fatal police shootings occur annually compared to official federal records, a discrepancy that underscores the limitations in government data collection and reporting. This disparity has widened in recent years; in 2021, for example, the FBI was able to track only one-third of departments' fatal shooting incidents.
Since 2022, The Post has also standardized and published the names of the police agencies involved in each shooting, further enhancing the potential for accountability at the department level. This dataset primarily focuses on cases that mirror circumstances like those in the killing of Michael Brown—instances in which on-duty police officers fatally shoot civilians. The dataset excludes fatalities in police custody, off-duty shootings, and non-shooting deaths.
As debates over police reforms continue, the need to understand the impact of policy interventions on fatal police shootings has become paramount. Using a causal inference approach with instrumental variables, this study aims to examine the effectiveness of various policy interventions in reducing fatal police shootings, shedding light on how reforms can lead to meaningful changes in policing practices.

2.	Project Goal

The goal of this project is to evaluate the impact of specific factors on fatal police shootings, focusing on how the presence of certain conditions (e.g., signs of mental illness, the presence of a weapon) affects the likelihood of fatal outcomes. This involves answering causal questions such as:
•	What is the effect of a subject being unarmed on the likelihood of a fatal police shooting?
•	To what extent does mental illness influence threat-level assessment and subsequent outcomes in police interactions?


3.	Design of Study

•	Effect to Estimate: The primary effect of interest is how different attributes of individuals and the context of police encounters affect the likelihood of a fatal shooting. For example, the effect of “being unarmed” or “showing signs of mental illness” on the probability of a fatal outcome.
•	Treatment and Outcome:
o	Treatment: Variables such as "armed status" (armed vs. unarmed), "signs of mental illness," and "threat level."
o	Outcome: The likelihood of a fatal police shooting, potentially operationalized as a binary outcome (fatal vs. non-fatal).
•	Relevant Variables:
o	Demographic Variables: Age, gender, and race of the individuals involved.
o	Contextual Variables: Location data (city, state), body camera presence, whether the individual attempted to flee, and whether they were armed.
o	Interaction-Specific Variables: Threat level, signs of mental illness, and manner of death.
•	Estimation Plan:
o	Use observational data to estimate causal effects, controlling for demographic and contextual variables.
o	Apply causal inference methods such as Instrumental Variables (IV) if suitable instruments can be identified, or Propensity Score Matching (PSM) to account for selection bias.
o	Conduct sensitivity analyses to evaluate the robustness of the findings, particularly to account for unobserved confounding factors.
A Causal Inference Approach Using Instrumental Variable

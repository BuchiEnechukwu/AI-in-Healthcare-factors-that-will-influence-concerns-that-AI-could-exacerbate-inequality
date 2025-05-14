# Factors Influencing Concerns That AI Could Exacerbate Health Inequality

This project analyses data from the 2023 Canada Health Survey to uncover which sociodemographic, socioeconomic, and experiential factors shape people’s worry that clinical AI might worsen structural health inequalities. Through descriptive statistics, χ² tests and a multivariable logistic regression, I identifed who is most concerned—and why.

## Research question
Do public perceptions and experiences with clinical AI influence concerns about its potential to perpetuate health inequality?

## Hypotheses
	•	H1: Comfort with (and worries about) specific AI applications—and relative ranking of privacy/consent/human-interaction concerns—will predict equity fears.
	•	H2: Sociodemographic factors (age, income, education) will independently shape these concerns, with disadvantaged groups more worried.
	•	H3: Direct experience of advanced digital-health services (e.g. accessing one’s own clinical notes) will heighten equity concerns over and above demographic effects.


## Data Source
	•	Dataset: 2023 Canada Health Survey (via Canada Health Infoway)
	•	Sample: N = 10 130 Canadians aged ≥ 16, weighted to match Canadian census on region, age & gender.
	•	Collection window: Nov 28–Dec 28, 2023
	•	Key domains:
	1.	Demographics (age, gender)
	2.	SES (education, income, employment)
	3.	AI knowledge
	4.	Digital-health experiences
	5.	Comfort with AI use-cases
	6.	Top three AI concerns (incl. “inequality”)

## Notebook Walk-through
	1.	Data loading & cleaning
	2.	Variable coding (demographics, AI knowledge, digital-health use, comfort & concerns)
	3.	Descriptive stats & χ² tests
	4.	Logistic regression
	•	Combined model (model_combined) with all predictors
	•	Reporting of coefficients, AORs, 95 % CIs & p-values
	5.	Goodness-of-fit
	•	Pseudo-R²
	•	Hosmer–Lemeshow test
	6.	Key figures & tables
	•	Age, gender, SES, digital-health experience associations
	•	Forest plot of AORs for significant predictors

## Main Findings
	•	Demographics: Younger and non-binary respondents most worried
	•	SES: University-educated less likely to worry; income no independent effect
	•	AI knowledge: Awareness alone didn’t predict concern
	•	Digital experience: Only prior access to personal clinical notes predicted higher worry
	•	Comfort w/ AI: General comfort didn’t allay equity fears; vaccine-R&D comfort showed a protective trend
	•	Other concerns: “Loss of human interaction” inversely related to equity worries

## Author
Buchi Enechukwu

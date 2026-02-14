# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.  Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `1`

Describe the purpose of your survey:
```
Identify the key factors contributing to the high turnover rate among entry and lower level employes at the company. It aims to assess employee satisfaction, workplace conditions, management practices, compensation, and career development oportunities. The findings will help the organization implement targeted strategies to improve retention and overal employee engagement.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
Target population: All current entry and lower level employees at the company across all departments and locations.

Sampling frame: In this study, thre sampling frame is the official list of all entry and lower level employees currently working at the company, obtained from the Human Resources Information System. The list includes employees job level, department, location, tenure in months, work arragement, salary band, job title. 

Sampling units: Each individual employee(one person=one survey response)

Overall Sampling Strategy: Stratified random sampling to ensure representation across groups that may experience turnover differently. First, divide target population into meaningful subgroups based on variables such as department, location, salary band, tenure band. Then, ramdomly select employees within each subgroup, aiming for proportional representation relative to the size of each group. If some departments are small but important for comparison, it may be require slighlty oversample them to ensure reliable analysis. 

```

Your 5-10 question survey:
```
1. How satisfied are you with your overall experience at the company?
Very satisfied, Satisfied, Neutral, Dissatisfied, Very Dissatisfied
2. How likely are you to look for a new job within the next 6 months?
Very satisfied, Satisfied, Neutral, Dissatisfied, Very Dissatisfied
3. Do you feel your compensation is fair for your role and responsabilities?
Very satisfied, Satisfied, Neutral, Dissatisfied, Very Dissatisfied
4. How would you rate your opportunities for career grownth within the company?
Very satisfied, Satisfied, Neutral, Dissatisfied, Very Dissatisfied
5. How supported do you feel by your direct manager?
Very satisfied, Satisfied, Neutral, Dissatisfied, Very Dissatisfied
6. Do you feel your work is valued and recognized?
Very satisfied, Satisfied, Neutral, Dissatisfied, Very Dissatisfied
7. Do you feel your current load is manageable and fair distributed?
Very satisfied, Satisfied, Neutral, Dissatisfied, Very Dissatisfied
8. write your question here... (optional)
9. write your question here... (optional)
10. write your question here... (optional)
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
Sample type:
1. Cross-sectional, probability sample survey.
2. Stratified, two-stage design.
3. Includes a "rejectin sample" sub-samplig component for non-volunteers

Sample Size:
Stated in the official documentation:
1. Field sample: 50.000 units
2. 40.000 invitation letters to the electronic questionnaire were sent.
3. Expected completions: 24.000 questionnaires.
4. Overall response rate: 41.9%

Target Population
1. All persons aged 15+ living in 10 provinces, excluding full-time residents of institutions.

Sampling Frame:
1. Frame combines landline + cellular phone numbers(From Census and administrtaive sources) linked with Statistics Canada's dwelling frame(address-based). Records are groups of telephone numbers associated with the same address(or a single phone number when no link can be made).
2. Covergare note: households without telephones were excluded from the surveyed population.

Survey mode
1. Electronic questionaire(online) and CATI(computer-assisted telephone interviewing)

Timeline:
1. Collection period (actual): 2018-09-04 to 2018-12-28
2. Reference period: past 12 months preceding interview date.
3. Date release: Jan 26, 2021.

Response rate:
1. Overall response rate: 41.9%

Weights:
1. Main person weight on microdata file: WGHT_PER (person-level weight).
2. Bootstrap weights were created for variance estimation, and StatsCan notes bootstrap was used for sampling variability estimation.
3. Weighting adjustments described include:
3.1 an adjustment related to the rejective sampling component
3.2 calibration to population totals by age-sex groups by province (monthly independent estimates)
3.3 an adjustment so the weighted income distribution matches 2017 CIS distribution by province

Data Processing
1. Processing used SSPE generalized processing steps/utilities (a structured processing environment).
2. Edits occurred at multiple stages (automatic + manual; macro + micro), including family/consistency/flow edits; CATI contained built-in range/flow edits, with head-office follow-up.

Cleaning, imputation, etc
1. Donor imputation using a score function is the primary method; if donor imputation couldn’t be used, mean imputation among a donor pool was used.
2. Imputation described as carried out in nine steps, including volunteering variables, informal volunteering variables, donation file variables, and solicitation methods.
3. Income: personal income questions were not asked; income was obtained through tax data linkage for respondents who did not object, then remaining missing values were imputed.

Sources of error:
1. Sampling error (sample-to-sample variability; addressed using bootstrap weights).
2. Non-sampling error, including coverage error, non-response, response error, and processing error.

Limitations/known biases
1. Undercoverage of households without telephones (and possibly other phone-frame coverage limitations), which can bias estimates if excluded groups differ.
2. Non-response bias risk; StatsCan describes weight adjustments (including use of admin characteristics such as income/household composition for nonresponding households) to reduce bias, but it may not eliminate it.
3. Mode change/comparability note: 2018 offered an Internet option for the first time (this can affect comparability with earlier cycles).

Documentation links and sources used
1. IMDB Survey Profile (methods, sampling, processing, error, response rate, weights)
https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234
2. Questionnaire page (instrument list + effective period + archived HTML questionnaire)
https://www23.statcan.gc.ca/imdb/p3Instr.pl?Function=getInstrumentList&Item_Id=1183690&UL=1V
3. PUMF Documentation & User Guide landing page (catalogue entry)
https://www150.statcan.gc.ca/n1/en/catalogue/45250011



```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 09 February 2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.

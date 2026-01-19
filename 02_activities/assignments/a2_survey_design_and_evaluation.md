# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
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

The number of your chosen topic: `3`

Describe the purpose of your survey:
```
The purpose of this survey is to examine how age influences music taste, with a focus on perceptions of popular music. By following participants over multiple years and comparing across age groups, the study aims to understand how music preferences change (or remain the same) over time.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
Target Population: Individuals aged 10 (with parental consent) to 50 at the start of the study. These participants will be tracked overtime to assess changes in music preferences.
Sampling Frame: Participants under the age of 18 will be recruited from school enrollment lists (with parental consent). Participants 18-yrs or older will be recruited from voter registration lists. These two lists will be stratified based on school districts and electoral districts/ridings.
Sampling Units: The stratified school districts or electoral districts, from where partipants are selected.
Observational Units: Individuals (people) who are surveyed for their music preferences over time.
```

Your 5-10 question survey:
```
1. Current age?
2. Current occupation or school year?
3. How many days would you say you listen to music per week? (0-7)
4. Indicate which music genre you prefer. Please indicate your preference for each style from 1 (least preferred) to 5 (most preferred). [Will provide a list of genres, including 'other']
5. Who is your current favourite musician/group? What would you characterize their style as?
6. Indicate which of the following songs you have heard this year. [List of songs from that year's top 10]
7. Do you currently play any instruments? If yes, please write which instrument you play.
8. When/during which scenarios do you listen to music? Please indicate your choice from 1 (never) to 5 (always). [List of things like 'during driving', 'while working', 'doing chores', 'relaxation', 'on a night out', etc]
9. How important would you say music is to your daily life? (1 = not important, 5 = very important)
10. Compared to 5 years ago, how similar are the types of music you currently enjoy? (1 = not similar, 5 = very similar)
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type = Stratified design employing probability sampling of Canadians 15y+ in private households, cross-sectional
2. Sample size = 40,000 invitation were sent (from 50,000 units)
3. Target population = All persons 15 years of age and older living in the ten provinces of Canada. It excludes full-time (residing for more than six months) residents of institutions.
4. Sampling frame = Landline and cellular telephone numbers from the Census and various administrative sources with Statistics Canada's dwelling frame.
5. Survey mode(s) = Electronic questionnaire or through CATI (computer assisted telephone interviewing), no proxy reporting, in English or French
6. Timeline = 2018-09-04 to 2018-12-28
7. Response rate = 41.9% (of 40,000 = 16,760)
8. Weights = (A) The weight is the number of persons represented by a given respondent. (B) To adjust for 'rejecting' participants, the person weight for respondents that are not 'rejected' and are not volunteers is multiplied by a factor. (C) Weights were adjusted so that the weighted income distribution of GVP matched the 2017 CIS distribution by province. (D) Bootstrap weights for design-based variance estimation.
9. Data processing = Processing used the SSPE set of generalized processing steps in a structured environment, with automated and manual edits made at macro and micro levels.
10. Cleaning, imputation, etc = All imputations were made using donor records selected through a score function via 9 steps (except a few cases), and the GVP imputation process helped to fill incomplete responses
11. Sources of error = (A) Non-sampling error: from imperfect coverage or non-response. (B) Non-response bias: Bias that occurs when some respondents do not answer. (C) Coverage error: if parts of target population are not included...this was minimized using several linked sources. (D) Other non-sampling errors: minimized through careful survey design and processing.
12. Limitations, known biases, etc = Households without telephones excluded, households targeted (maybe missing institutions), cross-sectional (cannot track overtime), 10 provinces (missing the 3 territories), Canadians 15+ (could be missing youth volunteering) - although it was a pretty well-designed study.
13. Link to documentation and any additional sources used = https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234
```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 14 January 2026`
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

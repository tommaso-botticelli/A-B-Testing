# Road and Railway Safety Campaign Analysis - A/B Test
## Project Overview:
This project is part of a statistical consultancy for the New Zealand Public Health Authority, aiming to improve road and railway safety awareness among parents of young children. The campaign includes two videos: one focused on road safety, highlighting the importance of care when walking on pavements, and another on railway safety. The objective is to educate parents with children entering the first year of primary school.

## A/B Test Overview:
Our team was tasked with conducting an A/B test to analyze the impact of different music types used in the road safety video. The music played during the road safety video is either ‘Dark and Ominous’ or ‘Happy and Bright’. The goal of the test is to investigate whether the type of music affects:

Whether respondents believe that two children in the road safety video will get hit by a car reversing out of a driveway.

How effective the railway safety video is in teaching children to behave safely near railway tracks.

The two videos are shown sequentially, with the road safety video followed by the railway safety video, and the music accompanying the road safety video is randomized between two groups of respondents.

## Study Methodology:
Randomized A/B Test: A randomized redirect tool was used to allocate respondents to either the ‘Dark and Ominous’ music group or the ‘Happy and Bright’ music group.

Data Collection Period: The A/B test was conducted over a two-year period, from 1st January 2023 to 31st December 2024, with 1532 responses (766 pairwise allocations of test versions A and B).

### Variables:

pairwise: The number of the pairwise allocation (from 1 to 766).

happyBright: A binary variable indicating the type of music played during the road safety video (1 for Happy and Bright, 0 for Dark and Ominous).

hit: A binary outcome where 1 indicates that the respondent believes the children in the road safety video will be hit by the car, and 0 otherwise.

effectiveRailwayVideo: A numerical rating (1-10) of how effective the railway safety video is perceived to be in teaching children safe behavior near railway tracks.

### Objectives:
Determine which type of music—'Dark and Ominous' or 'Happy and Bright'—should accompany the road safety video.

Investigate if the type of music in the road safety video affects perceptions of the effectiveness of the railway safety video.

Evaluate whether the duration of the A/B test (two years) was excessive and if a shorter duration would have been sufficient.

## Analysis Approach:
We will conduct both frequentist and Bayesian analyses to assess the data:

Frequentist Approach: Statistical tests (such as chi-squared, t-tests, or ANOVA) will be used to evaluate the hypotheses.

Bayesian Approach: A Bayesian analysis will be employed to interpret the data with a focus on posterior distributions and credible intervals.

## Expected Deliverables:
Descriptive Analysis: Overview of data trends, distribution of responses, and demographic information.

Assumption Testing: Tests to ensure that assumptions for statistical models are met (e.g., normality, independence).

Results: Present the findings from both frequentist and Bayesian analyses, including the impact of music type on respondents' perceptions.

Conclusions and Recommendations: Provide insights and recommendations based on the analysis:

Which music should be used for the road safety video.

The effect of music on perceptions of the railway safety video.

Whether the two-year test duration was appropriate.

Additional Analysis (Bonus):
If time allows, additional analyses will be conducted to explore challenges outlined in the bonus material, including further investigation into respondent demographics or testing alternative models.

# World Happiness Report EDA
An exploratory data analysis on the World Happiness Report Dataset from 2015 to 2022



More information can be found at: https://worldhappiness.report/


"
How are interviews conducted for the Gallup World Poll?
Gallup uses telephone surveys in countries where telephone coverage represents at least 80% of the population or is the customary survey methodology. In countries where telephone interviewing is employed, Gallup uses a random-digit-dial (RDD) method or a nationally representative list of phone numbers. Telephone methodology is typical in the U.S., Canada, Western Europe, Japan, Australia, etc. Gallup purchases telephone samples from various sample providers located in each region, including Sample Answers and Sample Solutions.

In the developing world, including much of Latin America, the former Soviet Union countries, nearly all of Asia, the Middle East, and Africa, Gallup uses an area frame design for face-to-face interviewing in randomly selected households.

Face-to-face interviews are approximately one hour, while telephone interviews are about 30 minutes.
"

"
How many people are interviewed in a typical World Poll survey?
The typical survey includes at least 1,000 individuals. In some countries, Gallup collects oversamples in major cities or areas of special interest. Additionally, in some large countries, such as China and Russia, sample sizes of at least 2,000 are collected. Although rare, in some instances, the sample size is between 500 and 1,000.
"

"
STEP 1 -- Selecting Primary Sampling Units (PSUs): In countries where Gallup conducts face-to-face surveys, the first stage of sampling is the identification of PSUs, consisting of clusters of households. PSUs are stratified by population size and/or geography and clustering is achieved through one or more stages of sampling. Where population information is available, sample selection is based on probabilities proportional to population size; otherwise, Gallup uses simple random sampling. In countries where telephone interviewing is employed, Gallup uses a RDD method or a nationally representative list of phone numbers. In select countries where cellphone penetration is high, Gallup uses a dual sampling frame. Gallup makes at least three attempts to reach a person in each household.
STEP 2 -- Selecting Households: Gallup uses random-route procedures to select sampled households. Unless an outright refusal occurs, interviewers make up to three attempts to survey the sampled household. To increase the probability of contact and completion, interviewers make attempts at different times of the day, and when possible, on different days. If the interviewer cannot obtain an interview at the initial sampled household, he or she uses a simple substitution method.
STEP 3 -- Selecting Respondents: In face-to-face and telephone methodologies, random respondent selection is achieved by using either the latest birthday or Kish grid method. In a few Middle Eastern and Asian countries, gender-matched interviewing is required, and probability sampling with quotas is implemented during the final stage of selection. Gallup implements quality control procedures to validate the selection of correct samples and that the interviewer selects the correct person in each household.
"
https://www.gallup.com/178667/gallup-world-poll-work.aspx


"
 Average life evaluations,
where 0 represents the worst possible life and
10 the best possible, range from an average
above 7.5 at the top of the rankings to below 3
at the bottom.
"

"
The six factors are
GDP per capita, healthy years of life expectancy,
social support (as measured by having someone to
count on in times of trouble), trust (as measured
by a perceived absence of corruption in government and business), perceived freedom to make
life decisions, and generosity (as measured by
recent donations, adjusted for differences in
income).
"

"
Cost-benefit Analysis Using Happiness as
the Measure of Benefit
If the aim of policy is to increase happiness,
policy makers will have to evaluate their policy
options in a quite new way. This is the subject
of Chapter 4. The benefits of a new policy should
now be measured in terms of the impact of the
change upon the happiness of the population. 
"


"
“Subjective well-being encompasses three differ
-
ent aspects: cognitive evaluations of one’s life,
positive emotions (joy, pride), and negative ones
(pain, anger, worry). 
"

"
 The consensus view
was that “subjective well-being” (SWB) was
both accurate and appropriately serious to be
the chosen generic title for the research field.24
Nonetheless, a number of authors who were
present, while accepting the accuracy of SWB,
nonetheless wrote their own books with
“happiness” in the title because they or their
editors knew that happiness draws more reader
interest than does subjective well-being
"

"
1. GDP per capita is in terms of Purchasing
Power Parity (PPP) adjusted to constant 2011
international dollars, taken from the World
Development Indicators (WDI) released by
the World Bank in November 2014. See the
appendix for more details. GDP data for 2014
are not yet available, so we extend the GDP
time series from 2013 to 2014 using countryspecific forecasts of real GDP growth from the
OECD Economic Outlook (May 2014 release)
for OECD countries, and the World Bank’s
Global Economic Prospects (June 2014 release)
for the rest of the world, after adjustment for
population growth. The equation uses the
natural log of GDP per capita, since that form
fits the data significantly better than does
GDP per capita.
2.
Social support (or having someone to count
on in times of trouble) is the national average
of the binary responses (either 0 or 1) to the
Gallup World Poll (GWP) question “If you
were in trouble, do you have relatives or
friends you can count on to help you whenever
you need them, or not?”
3. The time series of healthy life expectancy at
birth are constructed based on data from the
World Health Organization (WHO) and the
World Development Indicators (WDI). The
WHO publishes the data on healthy life expec
-
tancy for the year 2012. The time series of life
expectancies, with no adjustment for health,
are available in the WDI. We adopt the following
strategy to construct the time series of healthy
life expectancy at birth: first we generate the
ratios of healthy life expectancy to life expectancy
in 2012 for countries with both data. We then
apply the country-specific ratios to other years
to generate the healthy life expectancy data.
See the appendix for more details.
4.
Freedom to make life choices is the national
average of binary responses to the GWP
question “Are you satisfied or dissatisfied
with your freedom to choose what you do
with your life?”
5.
Generosity is the residual of regressing the
national average of GWP responses to the
question “Have you donated money to a charity
in the past month?” on GDP per capita.
6.
Perceptions of corruption are the average
of binary answers to two GWP questions:
“Is corruption widespread throughout the
government or not?” and “Is corruption
widespread within businesses or not?” Where
data for government corruption are missing,
the perception of business corruption is used
as the overall corruption-perception measure.
7.
Positive affect is defined as the average of
previous-day affect measures for happiness,
laughter and enjoyment for GWP waves 3-7
(years 2008 to 2012, and some in 2013). It is
defined as the average of laughter and enjoyment for other waves where the happiness
question was not asked.
8.
Negative affect is defined as the average of
previous-day affect measures for worry,
sadness and anger for all waves. See the
appendix for more detail
"



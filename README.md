# World Happiness Report EDA
An exploratory data analysis on the World Happiness Report Dataset from 2015 to 2022

Presentation can be found at: https://docs.google.com/presentation/d/1dH8gkX2piJPHEoMnGw-Lxs-cyDMe5WNmPSDCfrUt8Ao/edit?usp=sharing


More information can be found at: https://worldhappiness.report/


Method:
Based mostly on Gallup World Polls. Gallup samples each country to represent about 98% of the population. In countries where phones are widely available, Gallup samples numbers and conducts interviews over the phone (~30 minutes). In countries where phones are not prevalent, then Gallup conducts in-person interviews, usually for about an hour. For most countries, the number of interviews was at least 1000. 

Features:
1. Happiness Score - Gallup asked respondents to evaluate their current life as a whole using the mental image of a ladder, with the best possible life for them as a 10 and worst possible as a 0.

2. Economy - based on GDP per capita is in terms of Purchasing Power Parity (PPP). The equation uses the natural log of GDP per capita. 

3. Social Support - is the national average of the binary responses (either 0 or 1) to the Gallup World Poll (GWP) question “If you
were in trouble, do you have relatives or friends you can count on to help you whenever you need them, or not?”

4. Health - based on life expectancy at birth. 

5. Freedom - to make life choices is the national average of binary responses to the GWP question “Are you satisfied or dissatisfied with your freedom to choose what you do with your life?”

6. Generosity - is the residual of regressing the national average of GWP responses to the question “Have you donated money to a charity in the past month?” on GDP per capita.

6. Absence of Corruption - “Is corruption widespread throughout the government or not?” and “Is corruption widespread within businesses or not?” Where data for government corruption are missing, the perception of business corruption is used as the overall corruption-perception measure.



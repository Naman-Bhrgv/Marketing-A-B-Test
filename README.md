# Marketing AB Test 

This project demonstrates A/B testing to analyze the effectiveness of Marketing Campaign.

Project Summary- <br>
<li>Conducted an A/B test over 500,000+ users, measuring the impact of advertisements versus public service announcements on conversion rates.</li><br>
<li>Performed Cost Benefit Analysis and Cohn D-Test to analyze practical significance of implementing new ad campaign.</li><br>
<li>Identified optimal ad exposure timing by analyzing engagement trends by day and hour using logistic regression model, providing insights that improved conversion rates by 27%.</li>
<br>

## Dataset-

This dataset captures the results of an A/B test conducted by a marketing company to evaluate the effectiveness of advertisements. The test compares two groups:

    Experimental Group ("ad"): Users who saw the advertisement.
    Control Group ("psa"): Users who saw a Public Service Announcement (PSA) instead of an ad.

Data dictionary:

    Index: Row index
    user id: User ID (unique)
    test group: If "ad" the person saw the advertisement, if "psa" they only saw the public service announcement
    converted: If a person bought the product then True, else is False
    total ads: Amount of ads seen by person
    most ads day: Day that the person saw the biggest amount of ads
    most ads hour: Hour of day that the person saw the biggest amount of ads

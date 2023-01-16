# A/B test for an educational platform
The experiment: the team is testing new payment mechanics on their website. The control group remained with the basic mechanics and the test group was suggested a new way of payment.

The task: analyse the experiment's results and conclude whether it is worth launching the new payment mechanism for all users or not and why.

The workflow I followed:
* Look at the distributions in two groups and sub-groups.
* Select the proper statistical tests (I used Welch's t-test and chi-squared test).
* Draw the conclusion. In this project, I couldn't recommend implementing the new mechanics because of the drop in CR.

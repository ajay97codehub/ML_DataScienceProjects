1-Problem Statement description :

XYZ Gaming Company makes a freemium gaming app called "QWERTY League" that generates revenue through in-app purchases of "AZERTY jewels". "AZERTY jewels" have a list price of $4 per jewel, but they occasionally go on sale. XYZ Gaming Company also regularly engages in public marketing events to promote the app in order to draw in new users.
XYZ Gaming Company would like you to create two models:
1. A revenue prediction model for their finance team that can help predict weekly revenue up to 3 months (i.e., one quarter) forward.
2. A classification model for their marketing team that can help identify high-value new users for targeted marketing campaigns.

2-Given Data Description :

To facilitate model development, training data has been provided consisting of daily historical user activity and daily in-app purchase transaction data from the app launch on 20150403 through 20160702 as well as well the daily pricing schedule and marketing event schedule for 20150403 through 20161001.
The following data are provided:
1. activity.csv which is the log of user account activity on the app for the 20150403 to 20160702 timeframe.
2. marketing.csv which is the list of major and minor marketing events in the 20150403 to 20161001 timeframe.
3. pricing.csv which is the daily schedule of prices for the in-app purchase for the 20150403 to 20161001 timeframe.
4. transaction.csv which is the log of user in-app purchases for the 20150403 to 20160702 timeframe.
<img width="479" alt="TableDescription" src="https://github.com/user-attachments/assets/d14981e2-8015-4cb7-ab83-764e7a93050c">

3-Instructions
3.1 Predicting weekly revenue :
In this problem, the goal is to predict the weekly revenue of the app for the weeks in the 20160703 to 201601001 timeframe.

3.2 Predicting which new users will be high-value :
In this problem, the goal is to classify whether each of the given users in problem-two-new-users.csv will be high-value.
Each line of problem-two-new-users.csv is a new user, defined as a user who created an account in the app on or after 20160605 and has logged in on at least 10 days in the 20160605 to 20160702 timeframe.
Note : An user is considered high-value if that user spends at least $100.0 in total between 20160703 and 20161001.


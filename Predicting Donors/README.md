# Predicting Donors and Donation Types
 
This project was made in the context of the Machine Learning course from the Faculty of Science from Lisbon University. The [dataset](https://rdrr.io/cran/regclass/man/DONOR.html) concerns donations made to a national veterans organization. Even though we also did unsupervised learning, I focused mainly on supervised learning so that's what will be shown here.

The task is split in three parts:

* Predict if an individual will donate or not (binary classification)
* From the subset of donors, predict the donation type (multiclass classification), based on donation amount (DA):
    * `A` - DA >= 50
    * `B` - 20 <= DA < 50 
    * `C` - 13 <= DA < 20
    * `D` - 10 <= DA < 13
    * `E` - DA < 10
* For each Socioeconomic Group (SES), repeat the two previous tasks.

The work is split in two files:

* EDA.ipynb - Most of Exploratory Data Analysis and preprocessing is explained here.
* Main.ipynb - Main file

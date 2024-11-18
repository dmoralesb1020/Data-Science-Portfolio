# ExtraaLearn Project

## Introduction

The online education sector has witnessed rapid growth and is attracting a lot of new customers. Due to this rapid growth, many new companies have emerged in this industry. With the availability and ease of use of digital marketing resources, companies can reach out to a wider audience with their offerings. The customers who show interest in these offerings are termed as leads. There are various sources of obtaining leads for Edtech companies, like

* The customer interacts with the marketing front on social media or other online platforms.
* The customer browses the website/app and downloads the brochure
* The customer connects through emails for more information.

The company then nurtures these leads and tries to convert them to paying customers. For this, the representative from the organization connects with the lead on call or through email to share further details.

ExtraaLearn is an initial stage startup that offers programs on cutting-edge technologies to students and professionals to help them upskill/reskill. With a large number of leads being generated on a regular basis, one of the issues faced by ExtraaLearn is to identify which of the leads are more likely to convert so that they can allocate resources accordingly. 

This project will focus on the following objectives:
* Analyzing and building an ML model to help identify which leads are more likely to convert to paying customers
* Finding the factors driving the lead conversion process
* Creating a profile of the leads which are likely to convert

## Questions for Analysis

1. Leads will have different expectations from the outcome of the course and the current occupation may play a key role in getting them to participate in the program. Find out how current occupation affects lead status.
2. The company's first impression on the customer must have an impact. Do the first channels of interaction have an impact on the lead status?
3. The company uses multiple modes to interact with prospects. Which way of interaction works best?
4. The company gets leads from various channels such as print media, digital media, referrals, etc. Which of these channels have the highest lead conversion rate?
5. People browsing the website or mobile application are generally required to create a profile by sharing their personal data before they can access additional information.Does having more details about a prospect increase the chances of conversion?

## Data Description

The data contains the different attributes of leads and their interaction details with ExtraaLearn. The detailed data dictionary is given below.


**Data Dictionary**
* ID: ID of the lead
* age: Age of the lead
* current_occupation: Current occupation of the lead. Values include 'Professional','Unemployed',and 'Student'
* first_interaction: How did the lead first interacted with ExtraaLearn. Values include 'Website', 'Mobile App'
* profile_completed: What percentage of profile has been filled by the lead on the website/mobile app. Values include Low - (0-50%), Medium - (50-75%), High (75-100%)
* website_visits: How many times has a lead visited the website
* time_spent_on_website: Total time spent on the website
* page_views_per_visit: Average number of pages on the website viewed during the visits.
* last_activity: Last interaction between the lead and ExtraaLearn.
    * Email Activity: Seeking for details about program through email, Representative shared information with lead like brochure of program , etc
    * Phone Activity: Had a Phone Conversation with representative, Had conversation over SMS with representative, etc
    * Website Activity: Interacted on live chat with representative, Updated profile on website, etc

* print_media_type1: Flag indicating whether the lead had seen the ad of ExtraaLearn in the Newspaper.
* print_media_type2: Flag indicating whether the lead had seen the ad of ExtraaLearn in the Magazine.
* digital_media: Flag indicating whether the lead had seen the ad of ExtraaLearn on the digital platforms.
* educational_channels: Flag indicating whether the lead had heard about ExtraaLearn in the education channels like online forums, discussion threads, educational websites, etc.
* referral: Flag indicating whether the lead had heard about ExtraaLearn through reference.
* status: Flag indicating whether the lead was converted to a paying customer or not.

## Project Overview

In this project I performed an Exploratory Data Analysis (EDA) and built a predictive model to assess lead conversion, utilizing Decision Trees and Random Forest algorithms. I leveraged Python libraries such as Pandas, Seaborn, and Scikit-learn to analyze and model the data.
The analysis was driven by a set of questions related to lead conversion. By the end of the project, I was able to:
* Answer the initial questions.
* Identify the key factors influencing lead conversion.
* Develop a profile of leads most likely to convert into paying customers.

The complete code along with the conclusions are available in the Jupyter notebook. Below are the steps I undertook during this project:

* Performing univariate and bivariate analysis for numerical and categorical variables.
* Answering key questions related to lead conversion.
* Building a Decision Tree model and tuning its hyperparameters to improve its performance.
* Building a Random Forest model and tuning its hyperparameters to improve its performance.
* Presenting conclusions regarding key factors influencing lead conversion.
* Developing a profile of leads most likely to convert into paying customers.


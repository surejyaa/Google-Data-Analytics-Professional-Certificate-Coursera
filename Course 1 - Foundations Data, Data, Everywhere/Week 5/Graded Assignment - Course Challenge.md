<!--
* @Author: Surejya Suresh
-->

### Course Challenge
Grade received 97.50%

&nbsp;

#### Question 1 Scenario 1, question 1-5
You’ve just started a new job as a data analyst. You’re working for a midsized pharmacy chain with 38 stores in the American Southwest. Your supervisor shares a new data analysis project with you.

She explains that the pharmacy is considering discontinuing a bubble bath product called Splashtastic. Your supervisor wants you to analyze sales data and determine what percentage of each store’s total daily sales come from that product. Then, you’ll present your findings to leadership.

You know that it's important to follow each step of the data analysis process: ask, prepare, process, analyze, share, and act. So, you begin by defining the problem and making sure you fully understand stakeholder expectations.

One of the questions you ask is where to find the dataset you’ll be working with. Your supervisor explains that the company database has all the information you need.

Next, you continue to the prepare step. You access the database and write a query to retrieve data about Splashtastic. You notice that there are only 38 rows of data, representing the company’s 38 stores. In addition, your dataset contains five columns: Store Number, Average Daily Customers, Average Daily Splashtastic Sales (Units), Average Daily Splashtastic Sales (Dollars), and Average Total Daily Sales (All Products).

**Considering the size of your dataset, you decide a spreadsheet will be the best tool for your project. You proceed by downloading the data from the database. Describe why this is the best choice.**

* Spreadsheets are most effective when working with queries.
* **Spreadsheets work well for processing and analyzing a small dataset, like the one you’re using.**
* Databases can’t be used for analysis.
* Only spreadsheets let you download and upload data.
> A spreadsheet is a smart choice when working with a dataset of 38 rows and five columns.

&nbsp;

#### Question 2 Scenario 1 continued
You’ve downloaded the data from your company database and imported it into a spreadsheet
Now, it’s time to process the data. As you know, this step involves finding and eliminating errors and inaccuracies that can get in the way of your results. **While cleaning the data, you notice there’s missing data in one of the rows. What might you do to fix this problem? Select all that apply.**
* Delete the row with the missing data point
* Sort the spreadsheet so the row with missing data is at the bottom
* Ask a colleague on your team how they've handled similar issues in the past
* **Ask you supervisor for guidance**
> You could ask your supervisor or a colleague for guidance. Asking questions helps you learn and avoid mistakes.

&nbsp;

#### Question 3 Scenario 1 continued
Once you’ve found the missing information, you analyze your dataset.
** During analysis, you create a new column F. At the top of the column, you add: Average Percentage of Total Sales - Splashtastic. In data analytics, this column label is called an attribute.**
* **True**
* False
> This column label is an attribute, which is a characteristic or quality of data used to label a column.

&nbsp;

#### Question 4 Scenario 1 continued
Next, you determine the average total daily sales over the past 12 months at all stores, The range that contains these sales is E2:E39. To do this, you use a function. **Fill in the blank to complete the function correctly: =_____ (E2:E39).**
* SUM
* SALES
* TOTAL
* **AVERAGE**
> The function begins with an equal sign (=), then the word AVERAGE. The range is all of column E, represented by E:E.

&nbsp;

#### Question 5 Scenario 1 continued
**Next, you create a slideshow, which includes a data visualization to highlight the Splashtastic sales insights you've discovered. You’ve reached which phase of the data analysis process?**
* Manage
* **Share**
* Act
* Analyze
> The share phase involves creating data visualizations, preparing your presentation, and communicating your findings to stakeholders.

&nbsp;

#### Question 6 Scenario 2, questions 6-10
You’ve been working for the nonprofit National Dental Society (NDS) as a junior data analyst for about two months. The mission of the NDS is to help its members advance the oral health of their patients. NDS members include dentists, hygienists, and dental office support staff.

The NDS is passionate about patient health. Part of this involves automatically scheduling follow-up appointments after crown replacement, emergency dental surgery, and extraction procedures. NDS believes the follow-up is an important step to ensure patient recovery and minimize infection.

Unfortunately, many patients don’t show up for these appointments, so the NDS wants to create a campaign to help its members learn how to encourage their patients to take follow-up appointments seriously. If successful, this will help the NDS achieve its mission of advancing the oral health of all patients.

Your supervisor has just sent you an email saying that you’re doing very well on the team, and he wants to give you some additional responsibility. He describes the issue of many missed follow-up appointments. You are tasked with analyzing data about this problem and presenting your findings using data visualizations.

An NDS member with three dental offices in Colorado offers to share its data on missed appointments. So, your supervisor uses a database query to access the dataset from the dental group. The query instructs the database to retrieve all patient information from the member’s three dental offices, located in zip code 81137.

**The table is dental_data_table, and the column name is zip_code. How do you complete the following query?**

```
SELECT *
FROM dental_data_table
```
* zip_code = 81137
* WHERE = 81137
* WHERE_zip_code = 81137
* **WHERE zip_code = 81137**
> The correct syntax is WHERE zip_code = 81137. WHERE indicates where to look for information. The column name is zip_code. And the database is being asked to return only records matching zip code 81137.

&nbsp;

#### Question 7 Scenario 2 continued
The dataset your supervisor retrieved and imported into a spreadsheet includes a list of patients, their demographic information, dental procedure types, and whether they attended their follow-up appointment.

The patient demographic information includes data such as age, gender, and home address. **The fact that the dataset includes people who all live in the same zip code might get in the way of what?**
* Data visualization
* **Fairness**
* Future dental procedures
* Spreadsheet formulas or functions
> It’s your responsibility as a data analyst to make sure your analysis is fair. Although many zip codes do reflect diverse populations, a better choice would be to include data about people who live in multiple zip codes.

&nbsp;

#### Question 8 Scenario 2 continued
As you’re reviewing the dataset, you notice that there are a disproportionate number of senior citizens. So, you investigate further and find out that this zip code represents a rural community in Colorado with about 800 residents. In addition, there’s a large assisted-living facility in the area. Nearly 300 of the residents in the 81137 zip code live in the facility.

You recognize that’s a sizable number, so you want to find out if age has an effect on a patient’s likelihood to attend a follow-up dental appointment. You analyze the data, and your analysis reveals that older people tend to miss follow-ups more than younger people.

So, you do some research online and discover that people over the age 60 are 50% more likely to miss dentist appointments. Sometimes this is because they’re on a fixed income. Also, many senior citizens lack transportation to get to and from appointments.

With this new knowledge, you write an email to your supervisor expressing your concerns about the dataset. He agrees with your concerns, but he’s also impressed with what you’ve learned and thinks your findings could be very important to the project. He asks you to change the business task. Now, the NDS campaign will be about educating dental offices on the challenges faced by senior citizens and finding ways to help them access quality dental care.

**Fill in the blank: Changing the business task involves defining a new _____.**
* **question or problem to be solved**
* gap analysis plan
* data-cleaning strategy
* graphical representation of the data
> A business task is the question or problem data analysis answers for a business.

&nbsp;

#### Question 9 Scenario 2 continued
You continue with your analysis. In the end, your findings support what you discovered during your online research: As people get older, they’re less likely to attend follow-up dental visits.

But you’re not done yet. You know that data should be combined with human insights in order to lead to true data-driven decision-making. So, your next step is to share this information with people who are familiar with the problem. They’ll help verify the results of your data analysis.

**The people who are familiar with a problem and help verify the results of data analysis include customers and competitors.**
* True
* **False**
> Subject-matter experts look at the results of data analysis to identify any inconsistencies, make sense of the gray areas, and eventually validate the choices being made.

&nbsp;

#### Question 10 Scenario 2 continued
The subject-matter experts are impressed by your analysis. The team agrees to move to the next step: data visualization. You know it’s important that stakeholders at NDS can quickly and easily understand that older people are less likely to attend important follow-up dental appointments. This will help them create an effective campaign for members.

It’s time to create your presentation to stakeholders. It will include a data visualization that demonstrates the trend of people being less likely to attend follow-up appointments as they get older. **For this, a pie chart will be most effective.**

* True
* **False**
> A pie chart is used to represent the proportions of certain data categories compared to the whole. A line chart would be effective for tracking trends over time, such as people attending fewer appointments as they get older.

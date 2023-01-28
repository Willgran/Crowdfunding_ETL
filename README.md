# Crowdfunding_ETL
**The instructions for this mini project are divided into the following subsections:**

- Create the Category and Subcategory DataFrames

* Create the Campaign DataFrame

+ Create the Contacts DataFrame

- Create the Crowdfunding Database

**Create the Campaign DataFrame**

 - Extract and transform the crowdfunding.xlsx Excel data to create a campaign DataFrame has the following columns:

* The "cf_id" column

+ The "contact_id" column

- The "company_name" column

* The "blurb" column, renamed to "description"

+ The "goal" column, converted to the float data type

- The "pledged" column, converted to the float data type

* The "outcome" column

+ The "backers_count" column

- The "country" column

* The "currency" column

+ The "launched_at" column, renamed to "launch_date" and with the UTC times converted to the datetime format

- The "deadline" column, renamed to "end_date" and with the UTC times converted to the datetime format

* The "category_id" column, with unique identification numbers matching those in the "category_id" column of the category DataFrame

+ The "subcategory_id" column, with the unique identification numbers matching those in the "subcategory_id" column of the subcategory DataFrame




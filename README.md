![64410a99d52cf88103c4b88c_GDM_16_9](https://github.com/MahsaBakhtiari/Crowdfunding_ETL/assets/131717615/4fc33b7e-58d8-4bd2-8e3c-8fa06e31b6af)
# crowdfunding ETL
<font size="0">Members: Mahsa Bakhtiari, Dylan Kelly, Neel Chunara, Lena Hammoudyour</font>


## Overall Summary
This repository is for a mini ETL project meant to demonstrate the practice of building an ETL pipeline using Python and Pandas; the extraction and transformation of data through regular expressions/ Python dictionary methods. As well as the creation of four csv files used in the development of an ERD/ table schema, which is uploaded into a Postgres databse.

### Category DataFrame
 - The creation of a DataFrame containing the "category_id", entries sequentially order for unique "cat"
 - DataFrame is extracted to csv titled "category.csv"

### Subcategory DataFrame 
  - The creation of a DataFrame containing the "subcategory_id", entries sequentially order for unique "cat"
  - DataFrame is extracted to csv titled "subcategory.csv"
 
### Campaign DataFrame 
  - The creation of a DataFrame containing the following columns: "cf_id","contact_id","company_id","description", "goal", "pledged", "outcome", "backers_count", "country", "currency", "launch_date", and "end_date".
 - DataFrame is extracted to csv titled "campaign.csv"
    
### Contacts DataFrame
  - The creation of a DataFrame containing the following columns "contact_id", "first_name", "last_name", and "email
  - DataFrame is extracted to csv titled "contacts.csv"

### Crowdfunding Database
- The creation of database schema saved as "crowdfunding_db_schema.sql"

### Collaboration Notes
  -TBD on nexts team meeting

### Helpful Resources
  -Link to helpful sources/ code that might have been used

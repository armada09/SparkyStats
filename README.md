# SparkyStats
This Github repo contains the information with the csv file needed for the spark stat book dashboard. 
The objective of the dashboard is to give readers a yearly overview of their readding by month and several categories.

### If you like this site please share using **#sparkystats**

## Website Url
This github repo stores the csv file for the sparky stat dashboard located at the link below:
https://sparkystats.pythonanywhere.com/dashboard/

For any comments,feedbacks and suggestions you can email us at:
**sparkystats@protonmail.com**

You can download the csv file called **sparky_template.csv** from here and populate it with your book data. 
Note that dashboard and csv file gives users maximum flexibility. It allows users to design their own categories and genres. The system does not store the user's records or inputs as there is no database.
The dashboard opens the csv, analyzes the csv and populates the charts and data. Therefore it is the user's responsibility to save, store and manage their own csv file. The user is allowed to rename the csv file as required. 

**NOTE: DO NOT change the name of the header on the csv template file. **


** Sparky suggests the following guidelines to assist users and readers in populating their csv file:
- Put one category per book. E.g. for Harry Potter use magic.
- Make sure the month column in the csv column is **propercase** i.e. January, Feburary, etc...
- A maximum of 25 user created categories can be allowed. Sparky does suggest your max limit to 10 categories so your charts are more visible and clean.
- For genre name, use a maximum of 14 characters otherwise it will truncate.
- For author name, use a maximum of 14 characters otherwise it will truncate.

## CSV data columns 

|Title|Author|Series|Format|Source|Status|Category|Genre|Month Read|Page Count|Pages Read|Hours Listened|Rating / 5|Notes|
|-----|------|------|------|------|------|--------|-----|----------|----------|----------|--------------|----------|-----|


## For each column the following suggested catgories can be used: 

**Genre**: 
_Pick one main genre of the book._
- action
- romance
- contemporary
- adventure
- fantasy
- mystery
- harem
- erotica

**Categories**:
A type of book or an age group you can also combine them as well if you so wish. 
_Pick one main category for each book._
- young adults
- middle grade
- new adultadult
- children
- light novel
- manga
- fiction
- non-fiction
- shoujo
- light novel
- graphic novel/comic

**Book Source**
_Pick one main source of the book._
- Physical
- Tbr
- Kobo
- Kindle
- ARCS
- Owned
- Netgalley

**Status**
_Pick one main status of the book._
- DNF
- Planned to read
- Completed
- Reading

**Format**
_Pick one main format of the book._
- E-Book
- Online
- Paperback

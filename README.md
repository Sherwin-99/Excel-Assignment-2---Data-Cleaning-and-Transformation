# Excel-Assignment-2---Data-Cleaning-and-Transformation
Cleaned &amp; transformed a product dataset in Excel using Power Query: handled missing values, fixed inconsistent text/typos, removed duplicates, split/merged columns, and applied currency &amp; conditional formatting for clear, analysis-ready data. #Excel #PowerQuery #DataCleaning
Here's the updated README with a "Learnings" section added:

**Excel Data Cleaning Assignment
About This Project**

For this assignment, I worked with a raw product dataset that had a bunch of common real-world data issues — missing values, inconsistent text formatting, typos, and duplicate rows — and cleaned it all up using Excel and Power Query.

**What I Did**

I started by checking the Price column for missing values and filled them in using the average price, calculated through Power Query's statistics feature. For missing categories, I first fixed inconsistent labeling (like "Electronic" showing up instead of "Electronics"), then used Group By to find the most common category and used that to fill in the gaps.

Next, I cleaned up the Product Name column, which had inconsistent capitalization and some repeated entries, by applying the Capitalize Each Word formatting. I also fixed typos in the Category column using Find & Replace.

I checked the whole dataset for duplicate rows and removed them using Power Query's Remove Duplicates tool.

I then split the Product ID column into Manufacturing Date and Country Code using a delimiter, reordered the date to DD-MM-YYYY format, and merged the Brand Name and Product Name columns into a new "Product Brand" column.

Finally, I formatted the Price column as currency and applied conditional formatting — data bars on Price, and a custom rule to highlight "Electronics" entries in the Category column.

**Learnings**

This assignment taught me how messy real-world data can actually be, and how much groundwork goes into making it usable. I got hands-on practice with Power Query, especially for tasks like splitting columns, grouping data to spot patterns, and removing duplicates efficiently. I also learned how important it is to fix inconsistencies (like typos and formatting) before doing any kind of imputation, since those small errors can throw off the whole analysis. Overall, this project helped me understand the full data cleaning workflow from start to finish, and gave me more confidence using Excel and Power Query for practical data prep tasks.

Tools Used

Excel, Power Query, Find & Replace, Group By, Conditional Formatting

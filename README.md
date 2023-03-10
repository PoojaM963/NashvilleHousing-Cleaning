# NashvilleHousing-Cleaning

With this housing dataset, I used Microsoft SQL Server to clean and ensure the data was in a much more usable format for future exploration:

1)  Standardising the date format - CONVERT function
2)  Populating property address data and splitting it into seperate columns: Address, City, State - SUBSTRING, CHARINDEX, PARSENAME functions
3)  Ensuring data was consistent by changing 'Y' and 'N' to 'Yes' and 'No' - CASE WHEN function
4)  Removing duplicates - creating CTE, ROW_NUMBER and OVER(PARTITION BY) functions
5)  Removing unused columns - DROP COLUMN function


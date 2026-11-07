Public Holidays (OMIS Class 9 Hands-On Activity)

PublicHolidays.csv: public holidays in 1997 for 37 countries or regions.
418 rows. UTF-8, comma-delimited, header row.
Columns: countryOrRegion, holidayName, normalizeHolidayName, isPaidTimeOff, countryRegionCode, date (yyyy-mm-dd).

Source: Microsoft Azure Open Datasets, Public Holidays
https://learn.microsoft.com/en-us/azure/open-datasets/dataset-public-holidays
which combines data from Wikipedia (Wikimedia Foundation Inc) and the PyPI holidays package.

Licence: Creative Commons Attribution-ShareAlike 3.0 Unported
https://creativecommons.org/licenses/by-sa/3.0/
Changes from the source: converted from Parquet to CSV, kept only 1997, and removed
the weekly "Sondag" (Sunday) rows the source lists for Norway and Sweden.
Rows sorted by country and date. No values changed.

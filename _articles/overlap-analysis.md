---
layout: post
date: 2022-02-23T21:01:32.214Z
title: Overlap Analysis
summary: Overlap analyses can help clarify the uniqueness of, and similarities
  between, two or more databases or collections, and the extent of overlap
  between resources. Knowing the overlap between collections can help you to
  make informed collections decisions, including whether to acquire, renew, drop
  or change access level (ex. Change from full text version to A&I) for a
  resource or collection
working-groups:
  - Data Analysis
authors:
  - Evelyn Bruneau
full_page: false
---
# Overview

When content is available from more than one source, we refer to this as "overlap." Examples of this include when e-journal and e-book titles are available in more than one database; when titles indexed are found in two or more Abstracting & Indexing (A&I) databases; or when online holdings, such as the purchase of journal backfiles, duplicate print or other library holdings.  

The most common types of overlap analysis are: 

1. Comparing the overlap of titles and coverage dates between or among full text and/or aggregator collections or databases. 
2. Comparing the overlap of titles and coverage dates between or among A&I databases
3. Comparing the overlap of titles and coverage dates of an A&I database to full text access
4. Comparing the overlap of titles and coverage dates to print and/or physical holdings
5. Comparing your institution’s holdings with those of peer institutions
6. Comparing your institution’s holdings with consortium offers

# Why Conduct an Overlap Analysis?

Overlap analyses can help clarify the uniqueness of, and similarities between, two or more databases or collections, and the extent of overlap between resources.  Knowing the overlap between collections can help you to make informed collections decisions, including whether to acquire, renew, drop or change access level (ex. Change from full text version to A&I) for a resource or collection.

The results of an overlap analysis can also help to decrease the duplication between physical (print, microforms, etc.) and online holdings and identify titles that your library may want to cancel, weed, or, conversely, want to purchase from a particular provider.  An analysis identifies print materials that can be weeded and replaced due to ownership of online backfiles or one time purchases of archival materials, or based on perpetual/post-cancellation access entitlements, thereby enabling a library to free up and repurpose valuable floor space. 

Overlap analysis can also be used for collaborative collection development; it can be used to determine overlap among libraries.

You could also conduct an overlap analysis when considering a special offer from a publisher; or when budget cuts compel you to review the library’s existing holdings for potential savings.

**Note:** The results of an overlap analysis are not to be used as a single method for determining whether or not to acquire or cancel a particular resource. For example, citations, journal usage, user ratings, programmatic coverage, cost effectiveness (cost-per-use), and uniqueness of content must also be considered. 

# Things to Consider When Conducting an Overlap Analysis

1. Perpetual vs. leased access to content
2. Access via aggregator vs “stable” publisher collection

   * Aggregators

     * Turnover of titles  
     * Lack of access to current content due to moving walls/embargoes
3. Amount of freely available and Open Access content
4. Depth of indexing 
5. Years of coverage. Your analysis must take years of coverage into consideration as different points of access my provide varying years of coverage
6. Which titles are unique? 
7. What do we retain if we stop subscribing?
8. What would be the impact of not having the resource?
9. Overlap analysis does not take into consideration the quality of metadata, ex. Controlled vocabulary subject terms (Belvadi, 2015)

# Overlap Tools/What you will use

1. Electronic Resource Management Systems (ERMS)

   * Serials Solutions
   * Alma: Overlap and Collection Analysis Tool, or Alma Analytics
   * FOLIO
   * OCLC WorldShare Management Service
   * Gold Rush Decision Support (formerly Gold Rush® Reports) allows libraries to do content overlap between electronic resource packages from primary publishers, aggregators and indexing/abstracting services. Users can compare one-to-one or many-to-many in the same simple interface ([Features of Gold Rush](https://www.coalliance.org/software/gold-rush))
2. Excel or similar spreadsheet program (to analyze data)
3. Title list ([KBART](https://airtable.com/shrH2Mwv3xAPuwwQw/tblVCHKrW1p1OYBqd) or publisher list)
4. Export of electronic journal, electronic book, physical holdings from the library catalogue or an analytics or similar report exported from your ERMS.

# Metadata Required/Column Headings*

1. Title
2. pISSN, eISSN (eISBN, pISBN)--used as match point 
3. Year of Publication
4. Edition

# Suggestions for Additional Column Headings*

1. Overlap (Y/N)
2. Overlap (Full or Partial)
3. Overlap Package(s)
4. Physical Holdings (Y/N)
5. Physical Location
6. Format
7. Access Owned or Leased
8. Years of full text coverage or depth of indexing (start and end dates)
9. Embargo (months and/or years)

\*varies by type of material. 

# The Basics

You will conduct your overlap analysis using either a vendor provided tool or by hand. You will use one list as your master document where you will import and compare data using a variety of formulas. 

Identify any overlaps that occur with your holdings and populate the appropriate columns.

## Methodology (Belvadi, 2015) 

1. Acquire the most recent title lists for the journal collections or databases you are comparing.
2. Combine both lists into a single Excel spreadsheet on separate worksheets.
3. Ensure that both lists have a common matchpoint, ISSN or ISBN are recommended. 
4. Because comparisons would be performed on these columns, ensure that ISSNs or ISBNs are similarly formatted (adding or removing dashes) and ensure that the format in Excel are the same (ex. Both are formatted as numbers).

## Useful Excel Features and Formulas

There are a myriad of Excel features and formula options that you can use to massage your data. The features and formulas listed below are only suggestions to get you started.

### Features

* **FLASH FILL**

Data contained in publisher title lists, and/or data sourced from your library catalogue or ERMS may require ‘massaging’ in order to get the data into a form or format that will be usable and calculable. Flash Fill automatically fills your data when it senses a pattern. This feature is found under Editing-->Fill-->Flash Fill, on the Home tab.

In the example below the Start Date was manually entered for the first two titles, then Flash Fill was applied which filled in the remaining start dates.

[![Flash Fill](https://sparcopen.org/wp-content/uploads/2021/07/Flash_Fill-300x38.png)](http://sparcopen.org/wp-content/uploads/2021/07/Flash_Fill.png)

 

* **CONDITIONAL FORMATTING**

Conditional formatting can be used to identify duplicates such as duplicate titles, ISSNs, or ISBNs. Feature found under the Styles section on the Home tab.

[![Conditional Formatting](https://sparcopen.org/wp-content/uploads/2021/07/Conditional_Formatting-300x38.png)](http://sparcopen.org/wp-content/uploads/2021/07/Conditional_Formatting.png)

**Example**

* **TEXT TO COLUMNS**

Use to separate data into separate columns. Feature is found in the Data Tools section of the Data Tab.

**Example**

[![Text to Columns](https://sparcopen.org/wp-content/uploads/2021/07/Text_to_Columns-300x35.png)](http://sparcopen.org/wp-content/uploads/2021/07/Text_to_Columns.png)

### Formulas

The following site is a great resource for detailed information on Excel Functions and Formulas <https://exceljet.net/excel-functions>

**1.IF FUNCTION**

The IF function runs a logical test and returns one value for a TRUE result, and another for a FALSE result.

**Syntax**

\=IF (logical_test, \[value_if_true], \[value_if_false])

**Use**

To compare coverage dates

**Example** 

In cell E2 enter =IF(C2<=D2,"Alternative Access Same or Better","Publisher Start Date Better")[![IF Function Example](https://sparcopen.org/wp-content/uploads/2021/07/IF-300x71.png)](http://sparcopen.org/wp-content/uploads/2021/07/IF.png)

 

**2. COUNTIF**

Count cells in a range that meet a single condition.

**Syntax**

\=COUNTIF (range, criteria)

**Use**

Really useful for determining matches (matching ISSN) among a list of ISSNs that span a number of Excel columns

**Example**

In cell D2 enter =COUNTIF($C$9:$E$16,A2) then copy the formula down the column.  

1= there is only one match

2=there are two matches for this ISBN

[![COUNTIF Function Example](https://sparcopen.org/wp-content/uploads/2021/07/COUNTIF-300x122.png)](http://sparcopen.org/wp-content/uploads/2021/07/COUNTIF.png)

**Note:** Normally you would be comparing lists in different Worksheets or Workbooks. For the example above both lists were combined on one sheet.

 

**3. IF & COUNTIF FUNCTIONS**

**Syntax**

\=IF(COUNTIF(range,criteria),“result if criteria met”,“result if criteria not met”)

**Use**

You can use this nested formula to compare two lists to see whether, for example, an ISSN or ISBN in one list exists in the other list and can return whatever value you assign.

**Example**

In cell C2 enter =IF(COUNTIF($C$12:$C$15,B2),“Yes”,“No”). Copy the formula down the column. [![IF and COUNTIF Function Example](https://sparcopen.org/wp-content/uploads/2021/07/IF_and_COUNTIF-300x127.png)](http://sparcopen.org/wp-content/uploads/2021/07/IF_and_COUNTIF.png)

**Note:** Normally you would be comparing lists in different Worksheets or Workbooks. For the example above both lists were combined on one sheet. 

 

**4. COUNTIFS FUNCTION**

The COUNTIFS function returns the count of cells that meet one or more criteria.

**Syntax**

\=COUNTIFS (range1, criteria1, \[range2], \[criteria2], ...)

**Use** 

You can use this to summarize data. Cell B2, in the example below counts the number of titles to which this institution has current online access and that access is via the EBSCOhost Academic eBook Collection (North America).  

**Example**

In cell B2 enter =COUNTIFS(C5:C12,C5,D5:D12,D5)[![COUNTIFS Function Example](https://sparcopen.org/wp-content/uploads/2021/07/COUNTIFS-300x94.png)](http://sparcopen.org/wp-content/uploads/2021/07/COUNTIFS.png)

 

**5. VLOOKUP**

Use this function to look up data in a table organized vertically. VLOOKUP supports approximate and exact matching, and wildcards (* ?) for partial matches. 

**Syntax**

\=VLOOKUP(lookup value, table array,  column index number, \[range_lookup])

**Use**

Use VLOOKUP to find and pull in data from another workbook or sheet.  

1. Allows you to search on one piece of data and return related data from a table.
2. Can automate the search and return process
3. Works with text and numeric data

**Example**

In cell C2 we enter =VLOOKUP(B2,$B$14:$C$20,2,FALSE) and then copy the formula down the column to fill in the rest.

[![VLOOKUP Function Example](https://sparcopen.org/wp-content/uploads/2021/07/VLOOKUP-300x126.png)](http://sparcopen.org/wp-content/uploads/2021/07/VLOOKUP.png)

**Note:** Normally you would be comparing lists in different Worksheets or Workbooks. For the example above both lists were combined on one sheet.

 

**6. REPLACE** 

REPLACE function replaces characters specified by location in a given text string with another text string.

**Syntax**

\=REPLACE (old_text, start_num, num_chars, new_text)

**Use**

To add a dash to ISSN

**Example**

In cell C2 enter =REPLACE(B2,5,0,"-").Then copy the formula down the column.[![REPLACE Function Example](https://sparcopen.org/wp-content/uploads/2021/07/REPLACE-300x75.png)](http://sparcopen.org/wp-content/uploads/2021/07/REPLACE.png)

**7. SUBSTITUTE**

Use this function to replace text in a given string by matching

**Syntax**

\=SUBSTITUTE (text, old_text, new_text, \[instance])

**Use**

 To remove dash from ISSN

**Example**

In cell  C2 enter  =SUBSTITUTE(B2,"-","")

[![SUBSTITUTE Function Example](https://sparcopen.org/wp-content/uploads/2021/07/SUBSTITUTE-300x77.png)](http://sparcopen.org/wp-content/uploads/2021/07/SUBSTITUTE.png)

**8. RIGHT**

Extracts a given number of characters from the right side of a supplied text string.

**Syntax**

\=RIGHT (text, \[num_chars])

**Use**

Can be used to extract start or end coverage dates

 

**9. LEFT**

Extracts a given number of characters from the left side of a supplied text string.

**Syntax**

\=LEFT (text, \[num_chars])

**Use**

Can be used to extract start or end coverage dates

**Example**

In cell E2 enter =LEFT(D2,4). Then copy the formula down the column.[![LEFT Function Example](https://sparcopen.org/wp-content/uploads/2021/07/LEFT-300x30.png)](http://sparcopen.org/wp-content/uploads/2021/07/LEFT.png)

 

**10. MID**

Extracts a given number of characters from the middle of a supplied text string.

**Syntax**

\=MID (text, start_num, num_chars)

**Example**

In the example below we use the =MID formula in cell E2 to extract the coverage end date from the string in D2 and then the =LEFT formula in cell F2 to extract only the date.

Formula in E2 =MID(D2,FIND(" until ",D2)+7,99)

Formula in F2 =LEFT(E2,4)

## [![MID Function Example](https://sparcopen.org/wp-content/uploads/2021/07/MID-300x17.png)](http://sparcopen.org/wp-content/uploads/2021/07/MID.png)

## Other Useful Formulas

* **\=COUNTA** count a range of cells that are not empty
* **\=COUNTBLANK** count the number of cells that are empty
* **\=AND** use to apply multiple tests to data \[ex. =AND( B3="RED", C3>30)]

# Bibliography

Belvadi, Melissa. (2015). Do-it-yourself title overlap comparisons. *Proceedings of the Charleston Library Conference*. <http://dx.doi.org/10.5703/1288284316261>

Blecic, D., Wiberley, S., Fiscella, J., Bahnmaier-Blaszczak, S., & Lowery, R. (2013). Deal or no deal? Evaluating big deals and their journals. *College & Research Libraries*, 74(2), 178-194, <https://doi.org/10.5860/crl-300> 

ExcelJet (2020). *Excel Function List.* Retrieved November 30, 2020, from <https://exceljet.net/excel-functions>

Harker, Karen R. & Kizhakkethil, Priya. (2015). The quick and the dirty: The good, the bad, and the ugly of database overlap at the journal title level. *The Serials Librarian*, 68(1-4), 249-254, https://[10.1080/0361526X.2015.1016858](https://doi.org/10.1080/0361526X.2015.1016858)

Pope, Barbara M. (2017). Making room for change: Rightsizing PSU’s Axe Library serials collection. *Kansas Library Association College and University Libraries Section Proceedings*: 7(1), <https://doi.org/10.4148/2160-942X.1066>

Vancouver Island University. (n.d.). *Assessment @ VIU Library: Overlap Analysis* Retrieved September 18, 2020, from <https://library.viu.ca/assessment>

Zorian M. Sasyk & Amanda K. Lewis. (2019). Overlap analysis, usage statistics, and the evaluation of aggregator databases. *Journal of Electronic Resources Librarianship*, 31(2), 120-122, https://[10.1080/1941126X.2019.1597459](https://doi.org/10.1080/1941126X.2019.1597459)
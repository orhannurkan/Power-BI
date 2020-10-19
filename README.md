# Using _Power BI_

1 - make an online Power BI subscription
2 - Power BI Desktop(download): have to use to create relations between tables
3 - activate 60days free power BI Pro membership (Optional)
4 - get data to Power BI Desktop and make relations
5 - Publish your data model (and report if you did it offline)
6 - Prepare reports online or in Power BI Desktop. 3. option is Power BI Report Builder(optional download)


# Power BI _Project Steps_

	When preparing a report, the most important thing is to meet the requests of the users as possible.
1 - interviews 	: Obtaining the information they want to see from the users or the project owner and how they want to see
2 - empati 	: If this is not possible, goals are set with empathy for target user groups
3 - collection	: Existing data files should be examined in detail,
	If special characters (such as,:; /. -) are not paid attention before data transfer, correct transfer could not be made,
	After the transfer, it should be checked whether the targeted record number of each record is correct and the column information is in the right place,
	Duplicate records should be deleted,
	Removing non-integrity data from data sets in order for reports to provide accurate information,
	Data types should be corrected as date, currency, number (decimal and thousand separators)
	Some columns can be split into multiple columns and/or additional new columns can be created for some calculations,
	Relationships between tables should be checked and corrected if there are mistakes,
	New tables can be created according to needs,
	And consequently, the data set should be understood and edited correctly
4 - goal	: How are the reports requested with the existing data carried out?
5 - generators	: All filters that can be included in the report must be presented to the user.
	A report without a filter is a static report that does not change unless the data is changed
	A report with filters means hundreds, thousands, or even more static reports,
6 - grafikler	: Filters can also be used as an axis for charts and tables if desired, and any other information can be placed on the other axis.
7 - complexity	: Tables to be displayed in the report can be categorized and displayed on different pages if they do not fit on one page.
8 - daily use	: In the dashboard, each report can be added in the desired order so that all reports can be viewed on a single page by scrolling down.
9 - sort order	: In the table view, users can sort the data according to the column they want.

As a result, users get the reports they want by playing with filters.
Note: You can use Power BI services from a desktop program, browser or mobile app.

# _FOOD ON THE GO_ PROJECT

## What is this?

A data report about the flow of orderings across day times in the online food ordering service **Food On The Go (FOTG)**. 
## Where does it come from?

This project was carried out in October 2020 in the context of the course Bouman 2.22 organized by BeCode, a network of inclusive coding bootcamps.

As data science learners, we were assigned a **use case** from the **Accenture** company, which provided us with a dataset belonging to the (fictitious) online food ordering platform FOTG. 

Using [Microsoft Power BI](https://powerbi.microsoft.com/en-us/) was a requierement of this project.

## Who's there?

Three learners and collaborators elaborated the project contained in this repo: [Orhan Nurkan](https://github.com/orhannurkan), [Opap's Ditudidi](https://github.com/Cassik6) and [Sara Silvente](https://github.com/silventesa).

## Content of this repository

### Data report

The data report can be found in the [fotg_powerBI file](https://github.com/silventesa/accenture_usecase/blob/master/fotg_powerBI.pdf).

![Alt Text](https://github.com/silventesa/accenture_usecase/blob/master/team_assets/Report1.gif)

### Dataset

This dataset belongs to the (fictitious) **Food On The Go** company, an online meal ordering service. 

The data included information about the orderings made by costumers during the months of April and May 2017.

The dataset contains 7 csv files upon which a series of data relationships (view [this document](https://github.com/silventesa/accenture_usecase/blob/master/fotg_powerBI.pdf) for more details) were settled. The folder contains two versions, the original one (raw, provided by Accenture) and the modified one (cleaned, with which the report was performed). 

## Team assets

Files related to the project design and team organisation.

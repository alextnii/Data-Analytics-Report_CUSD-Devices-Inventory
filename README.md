# Data Analytics Report - Building Power BI Dashboards for Clovis Unified School District's Device Inventory Database

## Project Overview:
This repository is a summary of the process of how I created two Power BI dashboards for my internship at Clovis Unified School District (CUSD). Disclaimer: Due to privacy and confidentiality agreements with CUSD's technology department, the actual data used in these projects cannot be included in this repository. The dashboards showcased here were built using their private inventory database. Only screenshots of the final visualizations will be shown here.


## Dashboard 1: Chromebook Data Dashboard

The **Chromebook Data Dashboard** consists of three key pages:
1. **Chromebook OS Version Page**: Displays the distribution of Chromebook OS versions using stacked bar charts and includes dynamic bins for any new OS versions added to the data.
2. **End of Support Page**: Tracks Chromebooks' support statuses, with similar visualization layouts to the OS Version page.
3. **Last Sync Date Page**: Shows the last sync dates of each Chromebook, with the added functionality of filters and bins to easily select devices based on their sync dates.

### Key Features:
- **Slicer Functionality**: Allows users to filter results by one or multiple locations within the district (e.g., Clovis West High School). There are 54 different locations that the user can choose from.
- **Dynamic Binning**: Automatically adjusts OS version bins as new data is pulled.
- **Card Visualizations**: Provides quick, at-a-glance totals for device statistics.
- **Detailed Tables**: Lists individual devices and their associated OS versions.

#### 1. OS Version Page
- The Chromebook OS Version page displays Card Visualizations for Total number of Chromebooks in the selected location(s), and shows two bar charts for the OS Version, and Grouped OS Versions. It also displays a table for the purpose of identifying specific Chromebooks Asset Numbers of interest based on the previous filtering.

Chromebook OS Version Page for 'All Locations'
![Displays Chromebook OS Version Data for all locations](Screenshots/D1_P1_NF.png)

Chromebook OS Version Page for 'CHS' (Clovis High School)
![Displays Chromebook OS Version Data for Clovis High School](Screenshots/D1_P1_CHS.png)

#### 2. End of Support Page
- The Chromebook End Of Support page displays two bar charts that display the Chromebook Count by End of Support Year as well as Chromebook Count by Year Acquired. There is a table for the purpose of identifying specific Chromebooks Asset Numbers of interest based on the previous filtering.

Chromebook End of Support Page for 'All Locations'
![Displays Chromebook End of Support Data for all locations](Screenshots/D1_P2_NF.png)


## Project 2: Windows Device Data Dashboard

The **Windows Device Data Dashboard** was a 2-page interactive dashboard that filtered data by categories such as Year Acquired and OS Version. This project followed a similar structure to the Chromebook dashboard, but I was able to complete it much more efficiently, having gained experience from the previous project.

### Key Features:
- **Slicers and Filters**: Users can filter the data based on year, OS version, and other important categories.
- **Efficient Design**: Leveraged experience from the Chromebook dashboard project to quickly build and refine the Windows device dashboard.

#### Screenshots
*Screenshots from the Power BI dashboard showcasing the layout and filter capabilities.*

---

## Reflection

This internship provided me with invaluable technical and soft skills. I learned to work with data pipelines from MySQL Workbench into Power BI, developing dashboards that were both informative and user-friendly. The biggest challenge was making dynamic bins for OS version data, which I overcame with a deeper understanding of Power BI's functionalities. This experience has greatly enhanced my proficiency in Power BI and MySQL, while also teaching me the importance of data visualization in decision-making.

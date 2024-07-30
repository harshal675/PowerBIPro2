
**COVID-19 Analysis Project in Power BI**

https://drive.google.com/file/d/1JOUAan4egW0O2EhPUVw2P6Z21lipfH_O/view?usp=drive_link

**Introduction:**
This project analyzes COVID-19 data by day, globally, and by country. The steps we followed are:

**Process:**
1. Import data into Power BI using the Get Data function.
2. Clean the data in Power Query Editor by removing duplicates, null values, etc.
3. Create new measures, calculated columns, and calculated tables.
4. Set relationships between tables in Model View. The worldometer table is the central table connected to USA and day-wise tables.
5. Create reports in Report View with various visualizations.

**COVID-19 Report Analysis:**
The report is divided into sections: Home Page, Day-wise Analysis, USA Country-wise Analysis, Country-wise Analysis, World-wise Analysis, and Sign Out.

**Home Page:**
- Header and image related to COVID-19.
- Navigation links to different sections.

**Day-wise Analysis:**
- Navigation to Home.
- Cards showing active cases, deaths, recovered, etc.
- Pie chart: New cases by month (highest in July: 6,030,911).
- Scatter chart: Deaths by month (highest in May and March: 31).
- Donut chart: Confirmed cases by month (highest in March and May: 31).
- Funnel chart: Active cases by month (highest in March and May: 31).
- Area chart: Recovered cases by month (highest in March and May: 31, lowest in January: 10).
- Ribbon chart: New cases by month (highest in March and May: 31).

**USA Country-wise Analysis:**
- Navigation to Home.
- Cards showing confirmed cases and deaths.
- Filled Map: Confirmed cases by state.
- Pie chart: New cases by month (highest in March and May: 103,540).
- Scatter chart: Deaths by iso2 (highest in US: 612,128).
- Donut chart: Deaths by iso3 (highest in US: 612,128, PRI: 15,040).
- Funnel chart: Deaths by state (highest in New York: 3,176,945, lowest in Puerto Rico: 2).
- Area chart: Confirmed cases by month (highest in March and May: 103,540, lowest in January: 33,400).
- Tree Map: FIPS by state (highest in Texas: 2,336,203,056).

**Country-wise Analysis:**
- Navigation to Home.
- Cards showing confirmed, active, deaths, etc.
- Pie chart: New cases by country/region.
- Scatter chart: Deaths by WHO region (highest in Europe: 56).
- Donut chart: Confirmed cases by country/region.
- Funnel chart: Active cases by WHO region (highest in Europe: 56, lowest in South-East Asia: 10).
- Area chart: Recovered cases by WHO region (highest in Europe: 56, lowest in South-East Asia: 10).
- Ribbon chart: Confirmed cases last week (highest in US: 3,834,677).

**World-wise Analysis:**
- Navigation to Home.
- Cards showing confirmed, active, deaths, critical cases, etc.
- Pie chart: Serious cases by WHO region (highest in Americas: 39,973).
- Scatter chart: New cases by country/region (highest in Mexico: 6,590).
- Tree Map: Serious cases by country/region (highest in India: 8,944).
- Line and Stacked Column chart: Active cases by WHO region (highest in Luxembourg: 995,282, lowest in Yemen: 4).
- Area chart: Recovered cases by WHO region (highest in Americas: 2, lowest in Western Pacific Asia: 1).
- Ribbon chart: Confirmed cases last week by population.

**Sign Out:**
- Thank you message.

**Conclusion:**
This analysis provides a comprehensive overview of COVID-19 data using graphs and tables. Power BI is an effective tool for this type of data analysis and reporting.

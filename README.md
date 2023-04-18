# Azure Cost Management Dashboard
I created this Dashboard to display the units consumed and the respective cost for Selected filters.

This Dashboard will be helpful for any Azure Customer, irrespective of their contract agreement with Microsoft.

Customers can view their usage and cost by uploading the Usage files into this Power BI file. Check the attached setup pdf file for details on setting up this dashboard.

Please note that all the screenshots on this page are mock-up screens; hence each screen data will differ. These screens are captured to show you what the screen looks like based on the data you will be uploading.

# Table of Contents
* [Azure Cost Management Dashboard](#dashboard)
  * [Filtering](#Filtering)
* [Monthly Usage and Purchases Dashboard](#monthlycostview)
  * [Monthly Cost View](#monthlycostview)
  * [Monthly Usage Cost View](#monthlyusagecostview)
  * [Monthly Purchase and Refunds Cost View](#monthlypurchasecostview)
  * [Monthly Usage and Cost by Service](#monthlyusagebyserviceview)
* [Daily Usage and Purchases Dashboard](#dailydashboard)
  * [Daily Usage Cost](#dusage)
  * [Daily Purchase and Returns](#dpurchase)
  * [Daily Cost by Service](#dservice)
* [Resource Level View Dashboard](#resdb)
  * [Daily Usage Units and Cost for On Demand, Reservations and Savings Plans](#odrisp)
  * [Top 5 Subscriptions drivers contributing to the cost](#top5subs)
  * [Top 5 Instance Types drivers contributing to the cost](#top5instances)
  * [Top 5 Resource Locations drivers contributing to the cost](#top5loc)

# Azure Cost Management Dashboard <a name="dashboard"></a>

This Dashboard helps customers to understand the billing details, including monthly bill, monthly usage cost, and monthly purchase cost, along with the number of units each Service consumed and the respective cost by Services running on On Demand or Reservations or Savings Plan with the Top 5 drivers contributing to the cost. These drivers are the Top 5 Subscription Names, Top 5 Instance Types, and Top 5 Locations. Customers can view details of any Service monthly and daily insights of usage and respective cost with a granular level of drill down to Resource Name.

## Filtering <a name="Filtering"></a>
Customers can filter the Usage details by Meter Category / Service, Meter Subcategory / Instance Type, Date, Subscription Name, Tags, Resource Location, Resource Group, and Resource Name. These filters can be helpful if you need to view usage and cost based on specific criteria.

For Example, Customers want to view the usage details by specific subscriptions or based on particular tags or months.

![image](https://user-images.githubusercontent.com/130760607/232646175-d490c5c9-c74e-4a51-9cff-6323f227ae7c.png)

# Monthly Usage and Purchases Dashboard <a name="monthlydashboard"></a>
This dashboard displays Monthly usage cost, purchase cost, and service cost for selected filters from the filters dropdown section


## Monthly Cost View <a name="monthlycostview"></a>
Monthly billed amount for selected filters from the Filters dropdown section

![image](https://user-images.githubusercontent.com/130760607/232646302-4057bfa5-c7bc-4f0a-b122-fbf6338d55d0.png)

## Monthly Usage Cost View <a name="monthlyusagecostview"></a>
Monthly usage cost for selected filters from the filters dropdown section

![image](https://user-images.githubusercontent.com/130760607/232646626-bd786fae-4c4c-468e-ad45-98cd0d617b8f.png)

## Monthly Purchase and Refunds Cost View <a name="monthlypurchasecostview"></a>
Monthly purchase and refund cost for selected filters from the filters dropdown section, followed by all the purchases made.

![image](https://user-images.githubusercontent.com/130760607/232646650-4bc3d3d6-c70b-417c-bebd-de7a97d593c8.png)

## Monthly Usage and Cost by Service <a name="monthlyusagebyserviceview"></a>
Cost by Meter Category month-wise with a granular filter to drill down to see Subscription Names, Resource Locations, Resource Groups, and Resource Names.

![image](https://user-images.githubusercontent.com/130760607/232646669-75614284-3548-4300-97bf-b4be9180d335.png)

# Daily Usage and Purchases Dashboard <a name="dailydashboard"></a>
This dashboard displays Daily usage cost, purchase cost, and service cost for selected filters from the filters dropdown section

## Daily Usage Cost <a name="dusage"></a>
Chart displaying the day-wise cost for selected filters from the filters section.

![image](https://user-images.githubusercontent.com/130760607/232649107-1189af41-db2b-4ecf-90fa-6c7b418af433.png)

## Daily Purchase and Returns  <a name="dpurchase"></a>
Chart displaying the day-wise purchase and refund costs for selected filters from the filters section.

![image](https://user-images.githubusercontent.com/130760607/232649152-1091d5b4-72e9-44ad-bda1-afe20ce5f01a.png)

## Daily Cost by Service <a name="dservice"></a>
Chart displaying the day-wise costs for selected filters from the filters section.

![image](https://user-images.githubusercontent.com/130760607/232649183-f34ab7c8-bee9-46ab-990b-46fe745fd997.png)

# Resource Level View Dashboard <a name="resdb"></a>
Detailed resource details of units ran on On Demand, Reservations, Savings Plan, Top 5 Subscription Names, Top 5 Instance Types, and Top 5 Resource Locations drivers contributing cost 

![image](https://user-images.githubusercontent.com/130760607/232649649-0ef4075e-69a5-46f0-ac22-6189fa209137.png)

## Daily Usage Units and Cost for On Demand, Reservations, and Savings Plans <a name="odrisp"></a>
Chart displaying the number of units consumed and the respective cost day-wise for selected filters from the filters section, followed by the display of 4 tables:
* Daily Usage Units and Cost - All the services
* Daily On-Demand Usage Units and Cost - Services running on On-Demand only
* Daily On Reservations Usage Units and Cost- Services running on Reservations only
* Daily On Savings Plan Usage Units and Cost - Services running on Savings Plan only

Each table above displays Meter Categories, consumed units, and respective cost month and day wise, with a granular drill down of Meter Name, Month, Subscription Names, Resource Locations, Resource Groups, and Resource Names. The month column in the table will be helpful when multiple months are selected from the Date dropdown filter to view the cost of each month.

![image](https://user-images.githubusercontent.com/130760607/232649780-26676116-c0a1-4dd8-ab22-0e2ef436bb69.png)

Daily On Demand, Reservations, and Savings Plans display of consumed units and respective costs will be the same as the below Chart.
![image](https://user-images.githubusercontent.com/130760607/232649871-fa1f2ef2-42f8-4cea-8ce1-55f5081d6faf.png)

## Top 5 Subscriptions drivers contributing to the cost <a name="top5subs"></a>
Chart displaying the top 5 Subscription Names contributing to the cost day-wise, followed by a table consisting of all the Subscription Names, Meter Names, Resource Locations, Resource Groups, and Resource names to view how many units each resource utilized along with cost day-wise.

![image](https://user-images.githubusercontent.com/130760607/232650427-52608942-e507-4c20-9f28-71709d64eafe.png)

![image](https://user-images.githubusercontent.com/130760607/232650439-62dd749b-b596-415f-8f65-4fd80edf81bf.png)

## Top 5 Instance Types drivers contributing to the cost  <a name="top5instances"></a>
Chart displaying the top 5 Instance types / Meter Names contributing to the cost day-wise, followed by a table consisting of all the Meter Names, Subscription Names, Resource Locations, Resource Groups, and Resource names to view how many units each resource utilized along with cost day-wise.

![image](https://user-images.githubusercontent.com/130760607/232650451-2bac80f3-7f8a-41ca-a995-d85cf36f0123.png)

![image](https://user-images.githubusercontent.com/130760607/232650466-e87f1963-ae41-4933-8165-3336dec55017.png)

## Top 5 Resource Locations drivers contributing to the cost <a name="top5locs"></a>
Chart displaying the top 5 locations contributing to the cost day-wise, followed by a table consisting of all the Resource Locations with a granular drill down of Subscription Name, Meter Name, Resource Group, and Resource name to view how many units each resource utilized along with cost day-wise.

![image](https://user-images.githubusercontent.com/130760607/232650481-d55d8535-3d56-417b-a9ce-5cf068d1f667.png)

![image](https://user-images.githubusercontent.com/130760607/232650500-829bfffb-2c6f-4953-b5b3-28b4f36b29de.png)


### Feedback and Suggestions
I welcome any feedback or suggestions on this dashboard! If you find any bugs or have ideas for improvements, please create an issue on this repository, and I'll get back to you as soon as possible.

To create an issue, click on the "Issues" tab at the top of this page and then click the green "New Issue" button. Please provide as much detail as possible about your issue or suggestion, including any steps to reproduce the problem or implement the recommendation.

I appreciate your help in making this Dashboard better for everyone!



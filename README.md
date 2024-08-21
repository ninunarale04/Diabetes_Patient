D:\Virtual_Intership_Project\SALES DATA ANALYSIS-20240617T110931Z-001

            SALES DASHBOARD


1. SALES DATA ANALYSIS
PURPOSE:
Analyze sales data to identify trends, top-selling products, and revenue metrics for business decision-making.
DESCRIPTION: In this project, you will dive into a large sales dataset to extract valuable insights. You will explore sales trends over time, identify the best-selling products, calculate revenue metrics such as total sales and profit margins, and create visualizations to present your findings effectively. This project showcases your ability to manipulate and derive insights from large datasets, enabling you to make data-driven recommendations for optimizing sales strategies.

COLUMN DESCRIPTION FOR SALES DATA ANALYSIS:
•ORDER ID
•PRODUCT
•QUANTITY ORDERED
•PRICE EACH
•ORDER DATE
•PURCHASE ADDRESS
•MONTH
•SALES
•CITY
•HOUR

EXECUTION PART
TRANSFORMATION OF DATA
STEP 1:
I downloaded the dataset, uploaded it using the 'Get Data' option in Power BI, and then proceeded to transform the data.

STEP 2:
The column headers are identified in the first row and should be kept as headers by following the steps below.

STEP 3:
After promoting the headers, navigate to the 'Transform' tab and select 'Detect Data Type.' This action will automatically identify the data type of each column and convert them as needed.

STEP 4:
•Split the datetime into date and time stamp
•The aforementioned process starts with selecting the desired column. Following the selection, the option to split the column becomes visible.
•Choose the 'Split Column' option and select the space as the delimiter.
•Upon completing the data transformation, click on 'Close & Apply' located at the top left.
•Remember, this step is crucial after any data transformation process.


        VISUALIZATION OF DATA
STEP 1:
Sales trend over time using the line chart
•Simply click on the Month name and Sales column, drag it to the desired position.
•To create a Chronological order for the months, follow these steps:
1.Select the column containing the months.
2.Navigate to the "Column Tools" and choose "Sort Column."
3.Select "Sort by Month Number" to sort the months in chronological order.

STEP 2: Best selling products using tree map
•To edit them for background color and font size, access the "Format" option for the visualization and adjust the settings as desired.
STEP 3: Top 5 best selling product using stacked bar chart
1.To manipulate the visualization, perform the following steps:
•Drag and drop the "Product" into the Y-axis.
•Place the "Quantity" into the X-axis for appropriate ordering

STEP 2: Best selling products using tree map
•To edit them for background color and font size, access the "Format" option for the visualization and adjust the settings as desired.

STEP 3: Top 5 best selling product using stacked bar chart
1.To manipulate the visualization, perform the following steps:
•Drag and drop the "Product" into the Y-axis.
•Place the "Quantity" into the X-axis for appropriate ordering

STEP 4: Top 5 cities by sales using map
STEP 5: Weekly sales distribution by weekday using column chart

STEP 6: Slicer is used to make this kind of visual
•To create a slicer visualization, drag and drop the "Month Name" field into the slicer option. To display the slicer in a vertical list, access the slicer settings and choose the option for a vertical column layout.

STEP 7: To find the revenue metrics:
•Total profit: Sum up the net profit from all sales transactions.
•Sales quantity: Calculate the total number of units sold.
•Profit margin: Compute the ratio of net profit to total revenue, usually expressed as a percentage.

        REVENUE = SUM OF SALES

1.Select the "Card" visualization type, then drag and drop the "Sales" into the designated field. Convert it to the "SUM" aggregation.
2.Additionally, adjust the display units to show values in millions, billions, trillions, or hundreds, and customize the number of decimal places as needed

1.Select the "Card" visualization type, then drag and drop the "Sales" into the designated field. Convert it to the "SUM" aggregation.
2.Additionally, adjust the display units to show values in millions, billions, trillions, or hundreds, and customize the number of decimal places as needed.

Sales quantity
•Select the "Card" visual, then drag and drop the "Quantity Ordered" int the designated field.
•Access the "Format" option for the visual, and adjust the callout value to change the display unit of the quantity ordered as desired.

Profit margin
PROFIT MARGIN = (( TOTAL SALES -TOTAL COST )/TOTAL SALES)*100;

•Click on new measure
•Find the total cost by using the new measure
•Find the total sales by using the new measure
•Find the profit margin by using this formula in the measure.
•Choose the measure created and place it in the card visual and design using the “Format visual”


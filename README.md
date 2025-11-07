# route-optimization-analysis
Route Optimization for Food Delivery: Improving Delivery Efficiency for Food Delivery Services in Dense Urban Areas.


Business Overview/Problem

Business Introduction

UrbanEats is a pioneering force in the competitive urban food delivery sector, dedicated to redefining the delivery experience for city residents. With a strong presence in densely populated urban areas across multiple cities, UrbanEats has become a trusted name in the food delivery industry. Their mission is to provide convenient, reliable, and efficient delivery services tailored to the unique needs of urban dwellers, underpinned by a commitment to customer-centric excellence, operational efficiency, sustainability, and market leadership.

UrbanEats' overarching goals encompass delivering a superior customer experience, optimizing operational efficiency, implementing eco-friendly practices to reduce their carbon footprint, fostering driver satisfaction, and aiming to be an industry frontrunner by setting high standards for service quality and innovation. These goals drive UrbanEats' mission to enhance the food delivery landscape in densely populated urban areas while addressing key challenges in their quest for excellence.

 

Business Problem


UrbanEats grapples with multifaceted challenges that demand astute resolution strategies:

    ✔ Prolonged delivery times, a primary driver of customer dissatisfaction.
    ✔ Escalating operational costs attributed to suboptimal routing.
    ✔ Inaccurate delivery estimates, causing vexation among customers.
    ✔ A high attrition rate among delivery drivers, a consequence of stressful working conditions.

The company's commitment to surmounting these challenges is unwavering, fueling the need for a robust route optimization solution.
Rationale for the Project

    Route Optimization involves the use of algorithms and technology to find the most efficient and cost-effective delivery routes for food orders. It aims to reduce delivery times, fuel consumption, and operational costs while improving overall service quality.

    The logistics and supply chain industry have undergone a profound transformation, driven by evolving consumer expectations for swift and dependable deliveries. Overall, the goal of route optimization for food delivery in dense urban areas is to create a more efficient and customer-friendly delivery process while managing the unique challenges of urban environments.

    UrbanEats, attuned to the dynamism of this industry, must evolve to remain at the forefront.

     

    Significance of the Project: The compelling reasons underpinning the project's significance encompass:
        ✔ Enhanced customer satisfaction through accelerated, precise deliveries.
        ✔ Substantial operational cost reduction via route optimization.
        ✔ Elevated driver morale and retention.
        ✔ A competitive edge in the ever-evolving food delivery landscape.
        ✔ The opportunity for UrbanEats to carve its identity as an industry pioneer in food delivery route optimization.

Aim of the Project

Objectives:

    ✔ Streamline delivery routes in dense urban areas, culminating in a minimum 20% reduction in delivery lead times.
    ✔ Mitigate operational costs by 15% through the implementation of efficient routing strategies.
    ✔ Augment driver satisfaction by alleviating the stressors associated with route planning and execution.

 

Goals:

    ✔ Deployment of a data-driven route optimization solution adeptly harnessing SQL and Power BI.
    ✔ Provision of real-time order status updates to customers.
    ✔ Enhancement of the overall food delivery experience within densely populated urban locales.

Data Description

This case study contains 4 datasets and they are as follows;

 

Table 1: Customer Orders

    ✔ OrderID (Primary Key, Integer): A unique identifier for each customer order.
    ✔ CustomerID (Foreign Key, Integer): An identifier for the customer placing the order. This field references the "CustomerID" in the "Customers" table.
    ✔ DeliveryAddress: The precise address where the food delivery is to be made.
    ✔ Latitude (Decimal): The geographical latitude coordinate of the delivery address. Units: Degrees (°).
    ✔ Longitude (Decimal): The geographical longitude coordinate of the delivery address. Units: Degrees (°).
    ✔ OrderTimestamp (DateTime): The date and time when the order was placed. Units: Date and Time (e.g., YYYY-MM-DD HH:MM:SS).
    ✔ OrderStatus (Text): The current status of the order.
    ✔ DriverID (Foreign Key, Integer): An identifier for the driver assigned to deliver the order. This field references the "DriverID" in the "Drivers" table.
    ✔ RestaurantID (Foreign Key, Integer): An identifier for the restaurant where the order originated. This field references the "RestaurantID" in the "Restaurants" table.

 

Table 2: Traffic Data

    ✔ LocationID (Primary Key, Integer): A unique identifier for each urban location.
    ✔ LocationName: A descriptive name for the urban location.
    ✔ TrafficDensity (Decimal): Traffic congestion or density data for the location. Units: Vehicles per Minute.

 

Table 3: Drivers

    ✔ DriverID (Primary Key, Integer): A unique identifier for each driver.
    ✔ DriverName: The name of the driver.
    ✔ ShiftID (Integer): An identifier for the driver's shift.
    ✔ ShiftStart (DateTime): The start time of the driver's shift. Units: Date and Time (e.g., YYYY-MM-DD HH:MM:SS).
    ✔ ShiftEnd (DateTime): The end time of the driver's shift. Units: Date and Time (e.g., YYYY-MM-DD HH:MM:SS).

 

Table 4: Restaurants

    ✔ RestaurantID (Primary Key, Integer): A unique identifier for each restaurant.
    ✔ RestaurantName: The name of the restaurant.
    ✔ Address: The restaurant's address.

Tech Stack

Tools- SQL and Power BI 

MySQL will be used for ;

    ✔ Data Collection and Storage
    ✔ Structured Data Storage
    ✔ Data retrieval
    ✔ Data for analysis 
     ✔ Route optimization

Project Scope

 

    ✔ Exploratory Data Analysis: Explore the data to understand its characteristics and discover patterns.
    ✔ Data Transformation:  Prepare the data for analysis by transforming, encoding, or normalizing it.
    ✔ Data Analysis : Analyze data on SQL to understand pattern in order to generate insights that will be visualized on Power BI
    ✔ Data Visualization: Create visual representations to communicate insights effectively.
    ✔ Interpretation and Insight Generation: Extract meaningful insights and interpret the results.

Project Contributor 
*DANIEL KUMAH*

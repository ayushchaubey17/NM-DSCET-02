# NM-DSCET-02
live link of our project is
https://food-delivery-dscet.netlify.app/


screenshots

<img width="512" alt="restaurantSearch" src="https://github.com/ayushchaubey17/NM-DSCET-02/assets/123767430/e13c0c25-1b7d-465b-bb20-6a19ea28c882">
<img width="510" alt="restaurantMenu" src="https://github.com/ayushchaubey17/NM-DSCET-02/assets/123767430/a7e7287f-3404-4f92-a5e1-933450bdc010">
<img width="513" alt="restaurantInfo" src="https://github.com/ayushchaubey17/NM-DSCET-02/assets/123767430/c046854a-b7cb-4020-822d-65ad7cfec71e">
<img width="513" alt="register" src="https://github.com/ayushchaubey17/NM-DSCET-02/assets/123767430/fa95d093-048e-41d6-828a-dfbd3ea40d78">
<img width="518" alt="placeOrder" src="https://github.com/ayushchaubey17/NM-DSCET-02/assets/123767430/fff0d1c7-43e7-4291-a4ec-f49b7dc2471b">
<img width="514" alt="login" src="https://github.com/ayushchaubey17/NM-DSCET-02/assets/123767430/8b3eb055-c3ee-4a98-ad94-a7cc6b0a4fbe">
<img width="512" alt="driverFinishOrder" src="https://github.com/ayushchaubey17/NM-DSCET-02/assets/123767430/237175ad-e4b7-471f-b61c-80cb3daa355e">
<img width="511" alt="customerAddComment" src="https://github.com/ayushchaubey17/NM-DSCET-02/assets/123767430/efaa2a94-43af-4d2f-8720-e531583d3f51">


upload srs file


1. Introduction
1.1 Purpose
The purpose of this document is to outline the software requirements for the development of a food delivery website. The website will serve as a platform for users to browse restaurants, view menus, place orders, and track deliveries.

1.2 Scope
The project includes the development of both the backend and frontend components. The backend will be developed using Java, while the frontend will use HTML, CSS, JavaScript, and React.js.

1.3 Definitions, Acronyms, and Abbreviations
SRS: Software Requirement Specification
UI: User Interface
API: Application Programming Interface
SQL: Structured Query Language

System Overview
2.1 System Description
The food delivery website will allow users to perform the following actions:
Register and log in as customers or restaurant owners.
Search for restaurants by location, cuisine, or restaurant name.
Browse restaurant menus and view item details.
Add items to the shopping cart and place orders.
Track order status and delivery.
Restaurant owners can manage their menus and view orders.

2.2 System Architecture
The system will consist of two main components:

Backend: Java-based server handling business logic and data management.
Frontend: HTML, CSS, JavaScript, and React.js-based user interface.

3. Functional Requirements
3.1 User Registration and Authentication
Users can register and log in using email or social media accounts.
User roles include customers and restaurant owners.
Authentication and authorization mechanisms will be implemented.

3.2 Restaurant Listings
Users can search for restaurants by location, cuisine, or restaurant name.
Restaurant details include name, location, cuisine, ratings, and reviews.



3.3 Menu Management (Restaurant Owners)
Restaurant owners can log in and manage their menus.
Add, edit, or remove items from the menu.
Set item prices and descriptions.

3.4 Ordering Process
Customers can browse restaurant menus.
Add items to the shopping cart.
Review and modify the cart.
Place orders, providing delivery details and payment information.

3.5 Order Tracking
Users can track the status of their orders (e.g., order received, preparing, out for delivery).
Receive notifications when the order status changes.


3.3 Menu Management (Restaurant Owners)
Restaurant owners can log in and manage their menus.
Add, edit, or remove items from the menu.
Set item prices and descriptions.

3.4 Ordering Process
Customers can browse restaurant menus.
Add items to the shopping cart.
Review and modify the cart.
Place orders, providing delivery details and payment information.

3.5 Order Tracking
Users can track the status of their orders (e.g., order received, preparing, out for delivery).
Receive notifications when the order status changes.


3.6 Payment Processing
Securely process payments using a third-party payment gateway.

3.7 User Reviews and Ratings
Users can leave reviews and ratings for restaurants.
Reviews should include text comments and star ratings.

4. Non-Functional Requirements
4.1 Performance
The website should load quickly and handle a large number of concurrent users.
Response times for critical functions should be below predefined thresholds.

4.2 Security
Implement encryption for user data and transactions.
Protect against common web application security threats (e.g., SQL injection, cross-site scripting).


4.3 Usability
The user interface should be intuitive and easy to navigate.
Ensure accessibility compliance.

4.4 Scalability
The system should be designed to scale horizontally to accommodate increased user load.

4.5 Reliability
The system should be highly available and minimize downtime.

5. Technical Requirements
5.1 Backend
Develop the backend using Java.
Use a relational database (e.g., MySQL) for data storage.
Implement RESTful APIs for communication between the frontend and backend.


5.2 Frontend
Develop the frontend using HTML, CSS, JavaScript, and React.js.
Ensure cross-browser compatibility.
Implement responsive design for mobile devices.

6. Testing
Perform unit testing, integration testing, and user acceptance testing.
Ensure the website is compatible with various browsers and devices.

7. Deployment
Deploy the application on a reliable web hosting platform.
Set up continuous integration and continuous deployment (CI/CD) pipelines.

8. Maintenance and Support
Provide ongoing maintenance and support to address issues and updates.

9. Appendix
Include any additional information or diagrams, such as database schemas, wireframes, or flowcharts, as needed.

10. Entities:
User
Attributes: UserID (Primary Key), Username, Email, Password, Role (Customer or Restaurant Owner)

Restaurant
Attributes: RestaurantID (Primary Key), Name, Location, Cuisine, Ratings

Menu Item
Attributes: ItemID (Primary Key), Name, Description, Price, RestaurantID (Foreign Key)





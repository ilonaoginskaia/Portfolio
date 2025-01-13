# Project 1: [Journey-Tracker-Application](https://github.com/ilonaoginskaia/Journey-Tracker-Application)

This is a simple web-based application that allows users to track their journeys by logging starting points, destinations, and distances traveled. The application ensures user authentication for secure data entry and includes session management for personalized experiences.

## Features

- **User Authentication**: 
  - Login system to ensure secure access to user data.
  - Session management to maintain user state.
  
- **Data Input**:
  - Users can input starting and ending points of their journey.
  - Option to record total distance traveled.

- **Data Security**:
  - Sessions are used to secure user data.

## Technologies Used

- **PHP**: For server-side scripting.
- **HTML/CSS**: For structuring and styling the application.
- **Session Handling**: Ensures security and persistence.

![Tracker_LogIn](https://github.com/user-attachments/assets/1b93dfd8-feb8-48c7-84be-66ccd71cd3b4)
![RegisterForm](https://github.com/user-attachments/assets/e6f83fed-90ec-45bf-b726-2b2c5bf22733)
![DataInput](https://github.com/user-attachments/assets/4f15348e-0e9e-4393-8f63-2f00cca71cf2)
![Output](https://github.com/user-attachments/assets/b5455b13-90ae-4ed0-abf1-32dc75e8be8e)
![contact form](https://github.com/user-attachments/assets/6daff3fa-98a6-43b8-9c33-13f6ac084e60)

# Project 2: [ToDo List Application](https://github.com/ilonaoginskaia/ToDo-List-app)

A simple, interactive ToDo list application that allows users to manage their tasks efficiently. This project demonstrates core web development skills, including HTML, CSS, JavaScript, and local storage for persistent task saving.

## Features

- Add tasks with ease using an intuitive interface.
- Edit and delete individual tasks.
- Clear all tasks at once with a single button.
- Save tasks automatically using browser local storage.
- Convert task data to PDF for easy sharing or printing.
- Clean and responsive design for various screen sizes.

## Technologies Used

- **HTML**: For structuring the application.
- **CSS**: For styling and layout.
- **JavaScript**: For interactivity and functionality.
- **Local Storage**: For saving user tasks persistently across sessions.

  ## How It Works

1. **Add Tasks**: Type your task in the input box and click "Add".
2. **Manage Tasks**: Use the delete button to remove individual tasks or "Clear All" to start fresh.

3. **Save Tasks**: Tasks are saved in the browser's local storage and reloaded upon revisiting the app.
4. **Export Tasks**: Use the feature to save tasks as a PDF document for external use.

![ToDoList_Interface](https://github.com/user-attachments/assets/86197012-4b45-44b5-a044-3a92c43ea97a)
![ToDoList_example](https://github.com/user-attachments/assets/cf0d9028-1918-4a32-bd08-ccb4a243939e)


# Project 3: Job Application Automation
This is an automation tool designed to simplify the process of job searching and applying. The program scrapes job postings from selected platforms, organizes them in an Excel file, converts the data to PDF format, and sends the document to a client via email.

## Features
Automated Job Search:
- Uses UiPath to scrape job postings by keywords from platforms like mol.fi and Jobly.fi.
## Data Organization:
- Extracted job details (e.g., job title, company, and location) are stored in a structured Excel file.
## PDF Conversion:
- The Excel file is automatically converted to a PDF file.
## Email Integration:
- The PDF is sent to an email address, simplifying the communication process.
## Technologies Used
- UiPath: For end-to-end automation of the job application process.
- Excel Automation: For managing and formatting data.
- PDF Activities: To handle file conversion within UiPath.
- Email Activities: Automates the sending of the final PDF via email.
## UiPath Workflow
![Main1](https://github.com/user-attachments/assets/9fdd8457-5dd1-4ffa-9226-2c86a24a3ee4)
![main2](https://github.com/user-attachments/assets/8dae7fe0-05a0-48b0-a392-779be55b0019)
![Main3](https://github.com/user-attachments/assets/cb97d3f7-ab5f-4782-a3f4-f44e8b9119cd)
![main4](https://github.com/user-attachments/assets/f55d1ac3-ff82-47a8-ac46-c8e9dc7ac6f4)
![mol1](https://github.com/user-attachments/assets/c26cf3fe-f69c-4bb1-8f60-3d06e9355f5b)
![mol2](https://github.com/user-attachments/assets/99ab9f50-c727-4bf2-96d1-b6350a897bce)
![jobly1](https://github.com/user-attachments/assets/6ce051c6-843f-48d2-8394-79db2767a845)
![jobly2](https://github.com/user-attachments/assets/7e730acd-31ce-4e39-8259-2b7ed2e2cfe2)

## Running the Automation 
![UserInput](https://github.com/user-attachments/assets/5b76d091-0808-42e2-bdd7-ad78e647700a)
![Reports](https://github.com/user-attachments/assets/bd89e2bc-e282-4a8e-b569-8f90216ea550)
![Report1excel](https://github.com/user-attachments/assets/8c1b598e-43d4-4e11-b123-84fd481df008)
![Report2excel](https://github.com/user-attachments/assets/61449be6-8bf1-4f45-9ee4-27e56a0a2aa9)
![PDFreport](https://github.com/user-attachments/assets/3bd6676f-e487-417d-9362-42a546a45bd7)
![ClientEmail](https://github.com/user-attachments/assets/124ef9a5-f40e-4514-a7af-65db4b229931)


# Project 4: E-commerce Database System
This project focuses on designing and implementing a MongoDB database for an e-commerce system. The database stores and manages critical information about customers, products, orders, and payment transactions, enabling efficient and scalable data handling.

## Features
- Structured Data Management:
Organized into four main collections: Customers, Products, Orders, and Payment Transactions.

## Customer Data:

Stores customer details like name, email, address, and order history.

![customer data](https://github.com/user-attachments/assets/1d98f603-f0bf-4ac2-8258-b748713d36e4) ![customer data input](https://github.com/user-attachments/assets/6980dfb0-977e-45b5-89bc-cfb6753961e7)


## Product Information:

Maintains product details such as name, description, price, and availability.
Ensures that customers only see products currently in stock.

![product info](https://github.com/user-attachments/assets/a93d61ba-eaaa-4668-813e-7a10f1a722eb) ![product info input](https://github.com/user-attachments/assets/2d971152-7d98-4314-8ad3-8bbfe7a86613)

## Order Processing:

Manages order details including order number, customer, products ordered, and order status.
Tracks order status updates throughout the order lifecycle.

![order](https://github.com/user-attachments/assets/f91c7307-3673-4bb4-9b80-8dec271f3174) ![order input](https://github.com/user-attachments/assets/0fa20c18-d794-4bdb-99f6-8b7cc7798fda)

## Payment Handling:
Records payment transactions with details such as payment method, order number, amount, and date.
Separates payment processing from orders for streamlined analytics and reporting.

![payment](https://github.com/user-attachments/assets/62f50f87-6528-4496-9ead-1100aa23526a) ![payment input](https://github.com/user-attachments/assets/0ee1985b-a0db-4436-bdbb-8ea3d1355633)

## CRUD Queries examples:
Add a New Customer:

![add client](https://github.com/user-attachments/assets/a400890f-c2ad-44f1-acc6-5e3a5eb1b20e)

Update a Customer's Email Address:

![update email](https://github.com/user-attachments/assets/38d68d35-2c59-4433-9aa2-d02365a54300)

Add an Order to a Customer's Order History:

![add order](https://github.com/user-attachments/assets/ea1d1b5f-9675-4d97-92a1-88c7add1e892)

## Example of Aggregation Framework
We want to determine how many orders have been placed by each customer:

![aggregation1](https://github.com/user-attachments/assets/ed17b4c7-2430-4c9e-8ebc-8b94c5a3f874)

![aggregation 2](https://github.com/user-attachments/assets/d0b0c822-21e1-4aab-a7ff-f75253a7c2aa)
![aggregation 3](https://github.com/user-attachments/assets/e8e51076-d290-4e06-ab91-dc133137a9d8)

## Charts: 

![chart1](https://github.com/user-attachments/assets/52bd3257-8ea1-4635-8de1-1fad86764dcf)

![chart 2](https://github.com/user-attachments/assets/d2552d3f-6726-47a6-9ca0-83b25d3f5004)

![chart 3](https://github.com/user-attachments/assets/2760c57d-e160-46c5-8f6f-77c012510b89)

## Index Creation:

An index was created on the sähköposti (email) field in the Asiakkaat collection:

![index](https://github.com/user-attachments/assets/bd80454a-1577-4357-b5d1-13faaf36956f)

Adding the index improved query performance significantly, reducing execution time by 82.35%.

## Technologies Used
- MongoDB

# Project 5: Hotel Room Reservation System (SSMS)
This project involves developing a hotel room reservation system using Microsoft SQL Server Management Studio (SSMS). The system facilitates room bookings for customers based on room size, amenities, furnishings, and pricing. It also manages staff operations, ensuring smooth hotel functionality.

## Features

### Customer Operations:
- Room Booking:
Customers can book rooms for specific dates via the hotel's website or in-person at the reception.
Bookings consider room size, features, and availability.
- Data Logging:
Receptionists record customer details and stay duration.
Rooms are marked as reserved upon booking.
### Admin Operations:
- Online Bookings:
Bookings made via the website are managed by the system admin.
- Check-Out Management:
Upon customer departure, the reservation is removed, and the room is flagged for cleaning.
### Staff Operations:
- Housekeeping:
Cleaners can check which rooms require cleaning via the system.
Rooms can be marked as cleaned once the task is completed.

## Use Case example: Booking

![case booking](https://github.com/user-attachments/assets/811e8b75-541a-473d-86fa-6337b2cac3d4)


##  Use Case example: Reservation Confirmations and Cancellations

  ![case](https://github.com/user-attachments/assets/2b570f36-6272-4884-8ae2-cc624d06ed4c)

## ER Diagram: 

![Kaavio](https://github.com/user-attachments/assets/62ced177-8a8c-4378-999c-f9b9e7beac81)

![diagram](https://github.com/user-attachments/assets/db2ead40-df53-4343-bbda-98f8bdddab14)

## Tables example: 

![tables](https://github.com/user-attachments/assets/8988b6cf-3f6d-40dd-87ca-6abaec20fbbe)

## Views, CREATE VIEW examples: 

![view 1](https://github.com/user-attachments/assets/787ad1ac-a7f7-41e7-a1ef-9be3d8bfcac4)  ![view 2](https://github.com/user-attachments/assets/5b999184-8b02-430d-8fb8-d4b5f3289277)

![view 3](https://github.com/user-attachments/assets/60e8a0d7-94c2-4772-ad8e-080d3ae435ee)

## Procedure example: 

![procedure 1](https://github.com/user-attachments/assets/bfee442d-5cfe-4c33-8fc5-e2d0223630be) ![procedure 2](https://github.com/user-attachments/assets/27f68b5a-144b-4413-99a5-5de7c0ee4b15)


## Technologies Used:
Microsoft SQL Server Management Studio (SSMS):
Database management and query execution.
Used for structuring and maintaining the reservation database.



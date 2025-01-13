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


## Project 4: E-commerce Database System
This project focuses on designing and implementing a MongoDB database for an e-commerce system. The database stores and manages critical information about customers, products, orders, and payment transactions, enabling efficient and scalable data handling.

## Features
- Structured Data Management:
Organized into four main collections: Customers, Products, Orders, and Payment Transactions.
- Each collection is tailored to a specific domain of the e-commerce system.

## Customer Data:

Stores customer details like name, email, address, and order history.
![customer data](https://github.com/user-attachments/assets/1d98f603-f0bf-4ac2-8258-b748713d36e4)
![customer data input](https://github.com/user-attachments/assets/6980dfb0-977e-45b5-89bc-cfb6753961e7)


## Product Information:

Maintains product details such as name, description, price, and availability.
Ensures that customers only see products currently in stock.

![product info](https://github.com/user-attachments/assets/a93d61ba-eaaa-4668-813e-7a10f1a722eb)
![product info input](https://github.com/user-attachments/assets/2d971152-7d98-4314-8ad3-8bbfe7a86613)

## Order Processing:

Manages order details including order number, customer, products ordered, and order status.
Tracks order status updates throughout the order lifecycle.

![order](https://github.com/user-attachments/assets/f91c7307-3673-4bb4-9b80-8dec271f3174)
![order input](https://github.com/user-attachments/assets/0fa20c18-d794-4bdb-99f6-8b7cc7798fda)

## Payment Handling:
Records payment transactions with details such as payment method, order number, amount, and date.
Separates payment processing from orders for streamlined analytics and reporting.

![payment](https://github.com/user-attachments/assets/62f50f87-6528-4496-9ead-1100aa23526a)
![payment input](https://github.com/user-attachments/assets/0ee1985b-a0db-4436-bdbb-8ea3d1355633)

## CRUD Queries examples:
Add a New Customer:
![add client](https://github.com/user-attachments/assets/a400890f-c2ad-44f1-acc6-5e3a5eb1b20e)

Update a Customer's Email Address:
![update email](https://github.com/user-attachments/assets/38d68d35-2c59-4433-9aa2-d02365a54300)

Add an Order to a Customer's Order History:
![add order](https://github.com/user-attachments/assets/ea1d1b5f-9675-4d97-92a1-88c7add1e892)



## Technologies Used
- MongoDB



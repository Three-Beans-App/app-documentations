# Esther Faith Dennis, Brett Russell and Nicholas Rowe T3A2 - Part A

# R1 Description of your website, including:

### Purpose
#### The Problem
Three Beans is a small suburban cafe who specialise in take away coffee. The owner approached us to create a web application for their staff and customers in order to assist them in improving their efficiency of service.

Recently Three Beans Cafe has grown and become a lot more busy, while this success has been great for the business, it has also introduced a new issue with longer lines and increased wait times.

#### The Solution
With the store becoming more and more crowded during peak times and many customers having to wait far too long in store to get their morning coffee, we have suggested an app which allows customers to place orders in advance and view the status and wait time of their order.  
This allows users to plan their commute and arrive at the cafe as their coffee order is being completed instead of needing to wait unnecessarily in store.  
The secondary purpose of this application is to add some extra convenience by allowing users to save their favourite orders so that customers with a regular order don't need to worry about manually customising it each time they use the app.  
Creating this system would allow the business to be less crowded at peak times while giving more convenience to customers, this results in increased productivity and customer satisfaction.

### Functionality / features
The 3 beans cafe website is accessible by all members of the public, once inside the basic functionalities and features include:
- A navbar for easily accessing different pages.
- A menu page with images and descriptions of each item sold.
- A login/signup portal for users to create profiles for placing orders.
- The ability to customise and add items to a cart for purchase.
- The ability to place orders through a checkout feature.
- Confirmation of orders through QR code.
- Order status tracking in app where users can track wait time.

Users who create a profile within the 3 beans cafe web application will have access to the following additional features:
- An option to add selected items to a favourite list.
- The ability to customise and remove items within that list.


Admin users (staff) will also have a portal within the application which will allow them to:
- View ongoing and previous orders .
- Update the completion status of orders.
- Add new items to the existing menu.
- Make adjustments to existing menu items.
- Delete menu items that are no longer available.
- Track and modify inventory supplies.

### Target audience
The target audience will be the following groups:
- Regular customers who want to conveniently save and place orders.
- People looking for information about food and coffee options in the surrounding area.
- Commuters who want a convenient way to order coffee that saves time on the way to work.
- Cafe staff who can use the tracking and order history to improve efficiency.
- Management wanting to track sales and update menu options.


### Tech stack
#### Front end
- [JavaScript](https://www.javascript.com/)
- [ReactJS](https://react.dev/)
- [HTML5](https://developer.mozilla.org/en-US/docs/Glossary/HTML5)
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

#### Database
- [MongoDB](https://www.mongodb.com/)

#### Object Document Mapping
- [Mongoose](https://mongoosejs.com/docs/)

#### Back end
- [Node.JS](https://nodejs.org/en)
- [ExpressJS](https://expressjs.com/)

#### Testing
- [Jest](https://jestjs.io/)

#### Package Management
- [npm](https://www.npmjs.com/)

#### Diagrams
- [draw.io](https://www.drawio.com/)

#### Design
- [Figma](https://www.figma.com/)

#### Project Management
- [Trello](https://trello.com/home)

#### DevOps
- [Visual Studio Code](https://code.visualstudio.com/)
- [GitHub](https://github.com/)

#### Hosting
- [Netlify](https://www.netlify.com/) (front end)
- [Render](https://render.com/) (back end)
- [MongoDB atlas](https://www.mongodb.com/products/platform/atlas-database) (database)



# R2 Dataflow Diagram

### Overview Diagram

We first created a process decomposition of the application using the Gene & Sarson method of notation. This shows a broad overview of our apps system processes:
![overview diagram](./docs/revised-dataflow-diagram.png)

### Sequence Diagrams

We also created four sequence diagrams to show a more comprehensive representation of how various pieces of data move throughout our application.

This diagram shows user login/signup:
![login sequence diagram](./docs/dataflow-diagram-login.png)

This diagram shows the process of placing an order:
![order sequence diagram](./docs/dataflow-diagram-order.png)

This diagram shows an admin user updating the status of an ongoing order:
![status sequence diagram](./docs/dataflow-diagram-status.png)

This diagram shows and admin user adding a new item to the menu:
![add item sequence diagram](./docs/dataflow-diagram-add-item.png)

# R3 Application Architecture Diagram

![architecture diagram](./docs/architecture_diagram.png)

# R4 User Stories

# R4 User Stories

### Standard User

1. As a user, I want to be able to view the home page and navigate to the menu page.
2. As a user, I want to be able to view the menu items.
3. As a user, I want to be able to add menu items to a cart.
4. As a user, I want to be able to modify items in the cart.
5. As a user, I want to be able to checkout.
6. As a user, I want to be able to receive an order confirmation and a QR code which I can use to collect my order.
7. As a user, I want to be able to check my order's status.
8. As a user, I want to be able to sign up and create an account.
9. As a user, I want to be able to log in and log out of my account.

### Signed In User

1. As a user, I want to be able to save menu items to a favourite page.
2. As a user, I want to be able to delete menu items on my favourite page.
3. As a user, I want to be able to select items from my favourite list and add them to the cart.
4. As a user, I want to be able to view my order history.

### Cafe Order Management System

1. As a staff mamber using the system, I want to be able to see a list of current orders.
2. As a staff mamber using the system, I want to be able to view an individual order.
3. As a staff mamber using the system, I want to be able to change the status of an order.
4. As a staff mamber using the system, I want to be able to scan a customer's QR code.
5. As a staff mamber using the system, I want to be able to view the availability of menu items.
6. As a staff mamber using the system, I want to be able to change the availability of menu items.

### Admin

1. As an admin using the system, I want to be able to create menu items.
2. As an admin using the system, I want to be able to update and delete menu items.
3. As an admin using the system, I want to be able to check the sales figures.

## User Personas

### User - Jon Graham - First time Customer

![John user story](./docs/user-story-john.png)

### User - Emma William - Regular Customer

![Emma user story](./docs/user-story-emma.png)

### Staff mamber - Misha Harrington

![Misha user story](./docs/user-story-misha.png)

### Manager - Patrick LeBreton

![Patrick user story](./docs/user-story-patrick.png)

# R5 Wireframes for multiple standard screen sizes, created using industry standard software
#### Home Page - Logout out
![Home Page screenshot1](docs/HomePage.png)

#### Login page
![Login Page](docs/Login.png)

#### Register Page
![Register page](docs/register.png)

#### Home Page Logged in
![Register page](docs/loggedin.png)

#### Menu
![Register page](docs/OrderingScreen.png)

#### Menu cart
![Register page](docs/Opencart.png)

#### Extended menu
![Register page](docs/extended.png)

#### Cart
![Register page](docs/Cart.png)

#### Order Confirmation
![Register page](docs/Orderconfirmation.png)

#### User Order History
![Register page](docs/Userorderhistory.png)

#### User Favourite List
![Register page](docs/UserFavouritelist.png)

#### Admin current orders
![Register page](docs/Admincurrentorders.png)

#### Edit and add items
![Register page](docs/editaddmenuitems.png)

#### Add items
![Register page](docs/additems.png)

#### Edit items
![Register page](docs/edititems.png)

### Iphone

#### Home - logged out
![Register page](docs/phonehomeloggedout.png)

#### Log in
![Register page](docs/phonelogin.png)

#### Register
![Register page](docs/phoneregister.png)

#### logged in
![Register page](docs/phonehomeloggedin.png)

#### Menu
![Register page](docs/phonemenu.png)

#### Menu Extended
![Register page](docs/phonemenuextended.png)

#### Cart 
![Register page](docs/phonecart.png)

#### Order Confirmation
![Register page](docs/phoneorderconfirmation.png)

#### User Order History
![Register page](docs/phoneuserorderhistory.png)

#### User Favourites
![Register page](docs/phoneuserfavourites.png)

#### Admin Current Orders
![Register page](docs/phoneadmincurrentorders.png)

#### Admin edit/add Menu
![Register page](docs/phoneeditaddmenu.png)

#### Admin edit 
![Register page](docs/phoneadmineditmenu.png)

#### Admin add
![Register page](docs/phoneadminadditem.png)
# R6 Trello

For the project, we will use the below platforms to do our project management and planning:

- Trello - We will use Trello to plan the project. There are four sprints as shown below:

  - Documentation: Documentation tickets start out in the "To do" column. This is for part A of the assignment. We divide the questions into tickets on the board and each team member can pick up a ticket and drag it to the "Doing" section.
  - Frontend: Frontend also starts with tickets for each part of the Frontend work in the "To do" column. Each ticket will have a name and description describing what needs to be done for that ticket. This sprint will be done after the documentation part is done, then the team members who will develop the Frontend can pick up a ticket and drag it to the "Doing" section.
  - Backend: Backend also starts with tickets for each part of the work in the "To do" column. Each ticket also has a name and description describing what needs to be done as part of that ticket. After the Documentation sprint is done, then the team members who will develop the Backend can pick up a ticket and drag it to the "Doing" section.
  - Deployments: The deployment sprint is for near the end of the development when we want to start making our app available online. This will include deployment of both Frontend and Backend.

  Progress during a sprint:

  - Backlog: If any ticket is blocked and not able to progress because of another ticket, we will drag it to the Backlog section, then the team will review what needs to be done, and help to unblock that ticket as soon as possible.
  - Todo: During a sprint each team member when they finish their current ticket can pick up a new ticket out of the correct Todo section.
  - Doing: Tickets in the Doing column are used to track the work which which is currently in progress.
  - Code Review: When we finish one ticket, we will open a pull request and allow other team members to review it.
  - Test: After we have done a feature/ticket, we will drag it to the "Test" column, then other team members will have a chance to test it is working properly.

- Discord - We have created a team channel for the project using Discord. We can share our ideas in the Discord, and organise meetings and stand ups in the chat. For meetings we will use Zoom.

Below are some screenshots for Trello project.

![trello screenshot1](./docs/trello1.png)

![trello screenshot2](./docs/trello2.png)

![trello screenshot3](./docs/trello3.png)

![trello screenshot4](./docs/trello4.png)

![trello screenshot5](./docs/trello5.png)

![trello screenshot6](./docs/trello6.png)

![trello screenshot7](./docs/trello7.png)

![trello screenshot8](./docs/trello8.png)

![trello screenshot9](./docs/trello9.png)

![trello screenshot10](./docs/trello10.png)

![trello screenshot11](./docs/trello11.png)

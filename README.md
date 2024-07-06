# R1 Description of your website, including:

### Purpose

### Functionality / features

### Target audience

### Tech stack

# R2 Dataflow Diagram

# R3 Application Architecture Diagram

![architecture diagram](./docs/architecture_diagram.png)

# R4 User Stories

### Standard User

1. As a user, I want to be able to view the home page and navigate to the menu page.
2. As a user, I want to be able to view the menu items.
3. As a user, I want to be able to add menu items to the cart.
4. As a user, I want to be able to modify items in the cart.
5. As a user, I want to be able to checkout.
6. As a user, I want to be able to receive an order conformation and a QR code which I can use to collect my order.
7. As a user, I want to be able to check my order's status.
8. As a user, I want to be able to sign up and create an account.
9. As a user, I want to be able to log in and log out of my account.

### Signed In User

1. As a user, I want to be able to save menu items to my favourite page.
2. As a user, I want to be able to delete menu items on my favourite page.
3. As a user, I want to be able to select items from my favourite list and add them to the cart.
4. As a user, I want to be able to view my order history.

### Cafe Order Management System

1. As a staff using the system, I want to be able to see a list of current orders.
2. As a staff using the system, I want to be able to view an individual order.
3. As a staff using the system, I want to be able to change the status of an order.
4. As a staff using the system, I want to be able to scan the customer's QR code,
5. As a staff using the system, I want to be able to view the availability of menu items.
6. As a staff using the system, I want to be able to change the the availability of menu items.

### Admin

1. As an admin using the system, I want to be able to create menu items.
2. As an admin using the system, I want to be able to to update and delete menu items.
3. As an admin using the system, I want to be able to to check the sales report.

## User Personas

### User - Jon Graham - First time Customer

- Name : Jon Graham
- Age: 30
- Work: Professional developer
- Bio: Jon is a professional developer who is working permanently from home. During the week day, he is very busy with his work, but on weekends he loves to go out with his wife to explore some new cafes and food.
- Story: Jon just recently moved to the area and hasn't explore much yet. Monday morning, Jon wants to have a cup of coffee and breakfast before his meeting starts, and he quickly checks some cafe around the area. Three Beans Cafe has really high reviews and he wants to try out the online order. Jon also wants to save time and doesn't want to be late for his meeting. He wants to view the menu without needing to sign up for an account. When making an online order, Jon is concerned about how to pick up his order as he has previously had mix ups where other people made online orders with the same name. So he is wondering if the app can provide a better solution then using name to pickup the order.
- Acceptance Criteria: As a standard user, Jon should be able to
  - View photos and descriptions of the menu.
  - Add menu items to the cart.
  - Modify items in the cart.
  - Checkout.
  - Receive a QR code for the order, so he can scan to pick up the order and avoid somebody else wrongly picking up his order.
  - Check the order status.
  - Not be required to sign up or login.

### User - Emma William - Regular Customer

- Name : Emma William
- Age: 25
- Work: Officer
- Bio: Emma is very outgoing and pretty lady. She alway has beautiful make up and a nice hair style. She has been a regular at Three Beans Cafe since it opened.
- Story: Emma is a very busy officer and she needs to travel one hour to work and needs a coffee for her drive. Every morning, she will spend most time on her time on make up and not leave her much time to wait at the cafe for her coffee. She like to quickly order a coffee through the online app while she is doing her make up. She has previously had experiences where she browsed the menu and clicked the wrong item and it caused her to order the wrong coffee. She also knows exactly what she wants each day and doesn't need to go through the menu every time. So she would like the app allow her to customise her favourite items for easy reorder.
- Acceptance Criteria: As a signed in user, Emma should be able to
  - Place orders online.
  - Track the progress of the orders.
  - View order history.
  - Add and remove items from the favourite list.
  - Use the favourite list to make a order.
  - Receive a QR code for the order, so she can scan to pick up the order.

### Staff - Misha Harrington

- Name : Misha Harrington
- Age: 18
- Role: Cafe staff
- Bio: Misha is a student, part time barista and all rounder staff at Three Beans cafe. She values customer satisfaction and good organisation. She wants to ensure she is always delivering quality product and customer service.
- Story: As a staff member, Misha want to be able to improve the efficiency of the service so that our valued customers can get their morning caffeine fix as quickly as possible.
- Acceptance Criteria: As a staff member using the Cafe Order Management System, Misha should be able to
  - View all the customers order so that she can prepare them.
  - Change the customer's order status so that customer will see how the order is going.
  - Change the availability of menu items to avoid customer's ordering unavailible items.
  - Scan the customer's QR code to identify the order.

### Cafe Owner and Manager - Patrick LeBreton

- Name : Patrick LeBreton
- Age: 45
- Role: Cafe owner and manager
- Bio: Patrick is a cafe owner and manager of the cafe. He values every customers and he loves to cook and serve customers. He mainly works in the kitchen and jumps up to the counter and coffee machine as needed. Basically, he is everywhere.
- Story: Patrick wants to change his menu by adding some new food items which includes pictures, descriptions and prices. Also everyday by the end of shift, he will need to check a report of how much money he made, and do a count of the money to finish off the day.
- Acceptance Criteria: As a cafe owner and manager, Patrick should be able to
  - Add menu items.
  - Delete and edit menu items.
  - Change menu items.
  - View the sale reports.

# R5 Wireframes for multiple standard screen sizes, created using industry standard software

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

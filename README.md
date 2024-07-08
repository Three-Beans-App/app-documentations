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
- A navbar for easily accessing different pages
- A menu page with images and descriptions of each item sold
- A login/signup portal for users to create profiles for placing orders

Users who create a profile within the 3 beans cafe web application will have access to the following additional features:
- The ability to customise and add items to a cart for purchase
- The ability to place orders through a checkout feature
- An option to select items to a favourites list
- Confirmation of orders through QR code
- Order status tracking in app where users can track wait time

Admin users (staff) will also have a portal within the application which will allow them to:
- View ongoing and previous orders 
- Update the completion status of orders
- Add new items to the existing menu

### Target audience
The target audience will be the following groups:
- Regular customers who want to conveniently save and place orders.
- People looking for information about food and coffee options in the surrounding area.
- Commuters who want a convenient way to order coffee that saves time on the way to work.


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

# R3 Application Architecture Diagram

![architecture diagram](./docs/architecture_diagram.png)

# R4 User Stories

### Standard User

1. As a user, I want to be able to view home and navigate to the menu page.
2. As a user, I want to be able to access the menu items.
3. As a user, I want to be able to add the menu items to the cart.
4. As a user, I want to be able to modify the items in the cart.
5. As a user, I want to be able to checkout the cart
6. As a user, I want to be able to receive a comfirmation of the order and a QR code so that I can use for collect my order.
7. As a user, I want to be able to check what is my order's status.
8. As a user, I want to be able to sign up and create an account.
9. As a user, I want to be able to log in and out of my account.

### Signed In User

1. As a user, I want to be able to save some menu items to my favourite page.
2. As a user, I want to be able to delete some menu items on my favourite page.
3. As a user, I want to be able to select the items in my favourite list and add it to the cart.
4. As a user, I want to be able to view my order histories.

### Cafe Order Management System

1. As a staff using the system, I want to be able to see all the orders come through.
2. As a staff using the system, I want to be able to view the individual orders.
3. As a staff using the system, I want to be able to change the order status.
4. As a staff using the system, I want to be able to scan the customer's QR code,
5. As a staff using the system, I want to be able to view the menu items availability.
6. As a staff using the system, I want to be able to change the menu items availability.

### Admin

1. As an admin using the system, I want to be able to create menu items.
2. As an admin using the system, I want to be able to to update and delete the menu items.
3. As an admin using the system, I want to be able to to check the sales report.

## User Personas

### User - Jon Graham - First time Customer

- Name : Jon Graham
- Age: 30
- Work: professional developer
- Bio: Jon is a professional developer who working permanently at home. During the week day, he is very busy of his work, but weekend he love to go out with his wife to explore some new cafes and food.
- Story: Jon just recently moved to this area, he hasn't explore much this area yet. Monday morning, Jon want to have a cup of coffee and breadfast before his meeting start, he quickly check some cafe around this area, Three Beans Cafe has really high review and it comes up to him. He wants to try out the online order, due to he wants to save some time and don't want to be late for the meeting. He wants to view the menu easily and also does not need to sign up for an account as he is first time try out Three Beans cafe and he is not sure whether he will order second time, mostly he want to save some time. Also with the online order, Jon is concern how to pick up his order, in before he had experience people have the same name as his, and pick up his order. So he is wondering if the app could provide a better solution for that instead they calling the name to pick up an online order.
- Acceptance Criteria: As a Standard User
  - User can view photos and descriptions of the menu.
  - User can add the menu items to the cart.
  - User can modify the items in the cart.
  - User can checkout the cart.
  - User can receive a QR code of the order, so the user can scan to pick up the order, avoid somebody wrongly pick up.
  - User can check the order status.
  - User not require to sign up or login.

### User - Emma William - Regular Customer

- Name : Emma William
- Age: 25
- Work: officer
- Bio: Emma is very outgoing and pretty lady. She alway have a beautiful make up and nice hair style. She has been a regular at Three Beans Cafe since it opened.
- Story: Emma is a very busy officer and she need to travel one hour to work. She needs a coffee to go with her every morning drive. Every morning, she will spent most time on her make up, it leave her not have too much time to wait at the cafe for her coffee. She like to hurry to order a coffee through the online order app while she doing her make up. She has experienced browse the menu and click the wrong item, it cause her order a wrong coffee, also she think she don't need to go throuth the menu to pick her order it is save her time, due to she alway want to order the same things. So she would like the app allow her to customlise her favourite list, then could make her morning operational multiple tasks better.
- Acceptance Criteria: As a Signed In User
  - User can place orders remotely.
  - User can track the progress of the orders.
  - User can view order histories.
  - User can add and remove favourite list.
  - User can use the favourite list to make a order.
  - User can receive a QR code of the order, so the user can scan to pick up the order.

### Staff - Misha Harrington

- Name : Misha Harrington
- Age: 18
- Role: cafe staff
- Bio: Misha is a student and part time barista and all rounder staff at Three Beans cafe, she values customer satisfaction and good organisation. She wants to ensure she is always delivering quality product and customer service.
- Story: As a staff member, Misha want to be able to improve teh efficiency of the service, so that our valued customers get their morning caffeine fix as quickly as she can.
- Acceptance Criteria: By staff useing Cafe Order Management System
  - Staff can view all the customers order so that she can prepare it.
  - Staff can change the customers order status so that customer will see how the order goes.
  - Staff can change the menu availability avoid customer order the unvailible items.
  - Staff can scan the customer's QR code to identify the order.

### Manager - Patrick LeBreton

- Name : Patrick LeBreton
- Age: 45
- Role: cafe owner and manager
- Bio: Patrick is the cafe onwer and also manager the cafe. He value every customers, he love to cook and serve customers. He mainly work at the kitchen and jump in the counter and coffee machine as need it. Basically, he is everywhere.
- Story: Patrick want to change his menu, he want put up some new food item to the menu. He is going to add some new items and pictures, descriptions and price. Also everyday by the end of the shift, he will need to check how much money he made, and do the money count to finish of the day.
- Acceptance Criteria: Sign in the system as Admin
  - Admin can add menu items.
  - Admin can change menu items.
  - Admin can view the sale report.

# R5 Wireframes for multiple standard screen sizes, created using industry standard software

# R6 Trello

![trello screenshot1](./docs/trello1.png)

![trello screenshot2](./docs/trello2.png)

![trello screenshot3](./docs/trello3.png)

![trello screenshot4](./docs/trello4.png)

![trello screenshot5](./docs/trello5.png)

![trello screenshot6](./docs/trello6.png)

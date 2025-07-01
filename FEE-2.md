# Q. What is Web Architecture ?
-> Web architecture is the overall structure of a website of web app, encompassing how it's built, deployed, and interacts with users.



# Components of Web Architecture
1. Client
2. Web Server
3. Application Server
4. Database
5. Load Balancer
6. DNS (Domain Name System)
7. Rendering Engine


# Core Goals
Maintainability and Scalability
Responsive and Dynamic U.I.


<!-- # Web Architecture Diagram -->
# Q. What is a Web Architecture Diagram?
A web architecture diagram shows how different parts of a web application are organized and how they communicate with each other. Think of it like a building plan, but for websites or web apps.

The Layered Model breaks down the architecture into layers, where each layer has a specific responsibility. These layers work from top to bottom and are connected like a sandwich (also called a 5-tier architecture).

1. **Client Layer** (User Device / Browser / Mobile App)
📌 What it does:
This is the end-user’s device (like a computer, phone, or tablet).

Runs a browser or app that loads the web app from the internet.

💡 Key Points:
Sends requests (like clicking a link) to the web server.

Displays what is returned (like a webpage or error message).

🧠 Example:
When you open Chrome on your laptop and go to www.amazon.in, your browser is part of the client layer.

✅ 2. **Presentation Layer** (Frontend/UI Layer)
📌 What it does:
Handles how things look and behave on the screen.

Manages user interactions, forms, animations, etc.

💻 Tech:
HTML, CSS, JavaScript

Frameworks: React, Angular, Vue

🧠 Example:
The homepage of Amazon, the cart button, search bar — all live in this layer.

✅ 3. **Application Layer** (Backend/Business Logic Layer)
📌 What it does:
Processes logic and connects frontend with database.

Handles login, orders, payment, etc.

💻 Tech:
Languages: Python, Java, Node.js

Frameworks: Express, Django, Spring

🧠 Example:
When you search for “Shoes”, this layer runs logic like “filter by price” or “sort by popularity”.

✅ 4. **Data Layer** (Database Layer)
📌 What it does:
Stores and retrieves structured data.

Securely manages user data, transactions, content, etc.

💻 Tech:
Relational DBs: MySQL, PostgreSQL

NoSQL DBs: MongoDB, Redis

🧠 Example:
When you place an order, your order details get stored in a table in this layer.

✅ 5. **Infrastructure Layer** (Deployment/Hosting/Network Layer)
📌 What it does:
Hosts and runs the entire web application.

Manages servers, load balancers, CDNs, firewalls, etc.

Ensures uptime, speed, and scalability.

💻 Tech:
Hosting: AWS, Azure, Google Cloud, Netlify, Vercel

Tools: Docker, Kubernetes, NGINX, Apache

🧠 Example:
When millions of users visit Amazon, the infrastructure layer keeps the app running smoothly by distributing load and securing traffic.

🧱 Final 5-Layer Web Architecture Diagram (Text-Based)
scss
Copy
Edit
┌────────────────────────────┐
│      Client Layer          │ 👤
│   (Browser / Mobile App)   │
└────────────────────────────┘
             ↓
┌────────────────────────────┐
│   Presentation Layer        │ 🎨
│ (HTML, CSS, JavaScript)     │
└────────────────────────────┘
             ↓
┌────────────────────────────┐
│   Application Layer         │ ⚙️
│ (Business Logic & APIs)     │
└────────────────────────────┘
             ↓
┌────────────────────────────┐
│       Data Layer            │ 🗃️
│     (Database Storage)      │
└────────────────────────────┘
             ↓
┌────────────────────────────┐
│   Infrastructure Layer      │ 🌐
│ (Servers, Hosting, Network) │
└────────────────────────────┘
# Supplier Tracker

This is a Node.js web application built with **Express.js** and **MySQL**, allowing CRUD operations (Create, Read, Update, Delete) on suppliers and products.  

**Features**
- View all suppliers and their products
- Add, update, and delete supplier records
- Dynamic HTML rendering with **EJS templates**
- Reusable layout via partials (header, footer)
- 404 page for invalid URLs

**Project Structure**
- **app.js** → main Node.js server file.
- **public/** → contains CSS files and other static assets.
- **views/** → contains EJS files for page templates.
  - **partials/** → contains reusable HTML snippets (e.g., header, footer).
- **index.ejs** → main landing page showing all suppliers.
- **404.ejs** → displayed for invalid routes.

**Database Setup**
1. Open `supplier-tracker_DBschema.sql` in your MySQL client.
2. Execute the SQL to create the database and insert sample data.
3. Update the database credentials in `app.js`:
const mysqlConnection = mysql.createConnection({
  host: "localhost",
  user: "your_db_username",
  password: "your_db_password",
  database: "supplier_tracker",
  multipleStatements: true
});

**Start the server:** <br>
npm start

**Open in your browser:** <br>
http://localhost:3000
<br> <br> <br>
**Screenshots:**
<br> <br> 
<img width="600" height="653" alt="All Suppliers" src="https://github.com/user-attachments/assets/455eb52a-77bb-4a5d-a3fd-3bddc792e28b" />
<br>
######
<br> <br> 
<img width="600" height="742" alt="Update Supplier" src="https://github.com/user-attachments/assets/d9cfb236-697c-4629-87ea-72b0591ba9e8" />




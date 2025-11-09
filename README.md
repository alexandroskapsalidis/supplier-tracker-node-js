This is a Node.js web application using the Express.js framework. It connects
to a Database and carries out mainly CRUD (Create, Read, Update, Delete) operations.

The node.js code resides inside the app.js file. There is a folder called
public which has the CSS files. Another folder called views, has the content
to be shown in the browser (the ejs files). The ejs files allow us to write
html templates and also inject dynamic data logic into them. Some repeated html
code is in separate ejs files inside the partials folder. When application runs
it loads first the "index.ejs" file. If the URL is wrong, it redirects to a 404 page.

The "supplier-tracker_DBschema.sql" file contains the SQL code to create the
Database and enter some data. Then to connect to the Database you have to enter
the username and password of the Database, in the mysql.createConnection() function,
inside the "app.js" file or create a user and use his credentials.

To test the application:
Create a local server, like live server of Visual Studio Code, listening to a port.
Then in the web browser type "http://localhost: [port number]". It will automatically
load the "index.ejs" file.

A visual view of All Suppliers
<img width="1532" height="1000" alt="All Suppliers" src="https://github.com/user-attachments/assets/160cddc7-861c-45f5-b142-6981f530b76d" />


A visual view of the Update Supplier page
<img width="1348" height="1000" alt="Update Supplier" src="https://github.com/user-attachments/assets/cddd1aa5-a4bd-4f26-80e6-ab2e1112855c" />



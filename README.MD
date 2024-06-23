# Family Travel Tracker
Family Travel Tracker is a web application designed to visually track the countries visited by your family members. It features an interactive world map where each country visited by a family member is highlighted.
### How to Use:
- Add Family Members: Start by adding each family member and their details.
- Track Travel: For each family member, mark the countries they have visited.
- Visualize on Map: View the world map to see the accumulated travels of your family.
### Technologies Used:
- EJS
- CSS
- Javascript
- PostgreSQL (Local Database)
### Getting Started:
1. cd to the folder of the project "Family Travel Tracker"
2. run npm install to install all the dependencies
3. Follow the queries.sql file to create the database
4. Create .env file (Details below)
5. run nodemon index.js to initialize the page
5. Your app is live and can be running on localhost:3000

### .env file 
PG_USER="postgres" \
PG_HOST="localhost" \
PG_DATABASE="world" \
PG_PASSWORD="<Your password here>" \
PG_PORT="5432"

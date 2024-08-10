Social Media Admin Dashboard

Overview
This project is an admin dashboard for a social media application, allowing administrators to manage users and posts effectively. The dashboard is built using React.js and includes essential features such as user and post listings, control buttons, and key performance indicators (KPIs).

Features

1. Home Page:
   o Displays 4 Key Performance Indicators (KPIs):

- Total Users
- Total Posts
- Users Active in the Last 24 Hours
- Posts Published in the Last 24 Hours

2. Users Listing Page:
   o Displays 2 KPIs:

- Total Users
- Users Active in the Last 24 Hours
  o Below the KPIs, there is a paginated list view of users.
  o Columns: User_id, Username, Name, Email
  o Each row has control buttons:
- Ban User: Deactivate the user.
- Edit User: Edit user details.

3. Posts Listing Page:
   o Similar layout to the Users Listing Page.
   o Columns: Post_id, Post Caption, Media URL
   o Each row has control buttons:

- Delete Post: Remove the post.
- Hide Post: Temporarily hide the post from the feed.

4. Navigation Bar:
   o Persistent navigation bar on the left side of all pages.
   o Allows easy navigation between Home, Users Listing, and Posts Listing pages.

5. Dummy Login Page:
   o Basic login page with email and password fields.
   o Use the following credentials to access the dashboard:

- Username: user
- Password: password
  Setup Instructions
  Prerequisites
- Node.js and npm installed
- Basic knowledge of React.js

Installation

1. Download the project files and navigate to the project directory.
2. Install dependencies:
   npm install
3. Run the development server:
   npm start
   The application will be available at http://localhost:3000.

Dummy Data

- The project includes a dummy dataset for users and posts.
- The dataset can be modified in the src/data folder.
  Project Structure
- /src/pages: Contains the main pages for Home, Users, Posts and Login.
- /src/components: Reusable components like the Navigation Bar, KPI boxes, and Table.
- /src/data: Contains dummy data for users and posts.
- /src/styles: Contains the styling files for each component.

Customization

- To customize KPIs, modify the logic in the Home component.
- To modify table columns, update the UserList and PostList components.
- Styling can be adjusted in the /src/styles folder using CSS or a CSS-in-JS solution.
  Future Enhancements
- Implement real authentication and authorization.
- Connect to a real database for user and post data.
- Add more control features like user role management.

Conclusion

This admin dashboard is a starter template for managing a social media platform. It is built with modern web technologies and provides a clean and intuitive interface for administrators.

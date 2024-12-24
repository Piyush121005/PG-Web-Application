# 🏠 PG Life Web Application  

PG Life is a **Full-Stack Web Application** designed to simplify the search for Paying Guest (PG) accommodations. This project was developed as part of a web development internship, where I gained valuable insights and guidance. The application reflects my understanding, creativity, and efforts to enhance its functionalities from a user’s perspective.  

---

## 🌟 About the Project  

PG Life is a fully responsive web application built using a modern tech stack. The application allows users to explore PG accommodations across various cities, view details, and mark their interests seamlessly. While the app is not hosted live, the complete code is included in this repository, and it can be run locally for demonstration purposes.  

---

## 💻 Tech Stack  

- **Frontend:** HTML, CSS, Bootstrap 5, JavaScript, AJAX  
- **Backend:** PHP, MySQL  

---

## ✨ Features  

### **Home Page**  
- **Search Bar:** Enter a city name (in any case), and PGs available in that city (if in the database) are displayed.  
- **City Shortcuts:** Circular buttons for major cities; clicking on a city displays the list of PGs available there.  

### **PG List Page**  
- Displays PGs in the selected city with key features in a card layout.  
- **Filter Bar:** Sort PGs by rent or rating in ascending/descending order.  
- Shows the number of users who have marked a PG as "interested."  
- Logged-in users can mark PGs as interested by toggling the heart icon, which dynamically updates the count and changes its fill color.  

### **PG Details Page**  
- Displays complete details of a selected PG, including:  
  - A **carousel** showcasing PG images.  
  - Amenities, testimonials, and address of the PG.  
  - Number of users marking the PG as "interested."  
- Logged-in users can toggle the heart icon to like or dislike a PG dynamically.  

### **User Dashboard**  
- Accessible only for logged-in users.  
- Displays the user's account details and their list of interested PGs.  
- Users can remove PGs from their interested list by toggling the heart icon, with the page dynamically updating.  

### **Navigation Bar**  
- Displays brand name.  
- **For Guests:** Signup and Login options are available.  
- **For Logged-In Users:** Dashboard and Logout options are displayed, along with the user's first name (via SESSION).  
- Fully responsive toggler navbar.  

### **Breadcrumb Navigation**  
- Displays the user’s location within the web app with hyperlinks for easy navigation.  

### **Footer**  
- Provides quick links to PG listings in popular cities.  
- Displays copyright information.  

---

## ⚙️ Application Behavior  

- The entire web app can be browsed without logging in to provide a seamless experience for new users.  
- Exclusive features like the dashboard and marking PGs as interested are only available for logged-in users.  
- Comprehensive exception handling ensures a smooth user experience, with custom error messages and prompts guiding users in case of issues.  

---

## 🚀 Running the Project Locally  

To view the application on your local machine:  
1. Clone this repository.  
2. Set up a local server (e.g., XAMPP or WAMP).  
3. Import the database from the provided SQL file.  
4. Access the application from your local server URL (e.g., `http://localhost/PGLife/`).  

---

## 📫 Contact  

Feel free to reach out to me for feedback, questions, or collaborations:  
- **Email:** Piyush121004@gmail.com  
- **LinkedIn:** [Your LinkedIn Profile](#)  

---  

Enjoy exploring the PG Life application! 😊  

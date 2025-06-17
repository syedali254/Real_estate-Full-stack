# Real_estate-Full-stack

  # 🏡 Real Estate Property Portal

A **full-stack real estate listing web application** where users can create accounts, list their properties for sale, explore listings, interact with AI-powered agents, schedule visits, and more.  
Built with **PHP**, **MySQL**, **JavaScript**, and integrated with **Google Gemini API** and **Web Speech API** for smart AI responses and voice interaction.

---

## 🚀 Features

### 👤 Authentication
- User registration & login system
- User type classification (e.g., buyer/seller/agent)

### 🏘️ Property Listing & Selling
- Sellers can list properties via a comprehensive form with:
  - Description, features, amenities
  - Location details
  - Photo uploads
- Listings are displayed as **property cards** showing:
  - Images, price, details, and contact info
  - View full details
  - Mark as favorite
  - Add reviews

### 🔍 Smart Search & Filtering
- Filter by price range, property name, and more
- Search dynamically updates listings in real-time

### ⭐ Favorites Management
- Save any listing to your favorites
- "View Favorites" section to manage your saved properties

### 📅 Visit Scheduling System
- Schedule a visit to a property with a selected date
- Real-time visit request management:
  - Approved, Rejected, or Pending (controlled by the property owner)
- View visit statuses in your **Notifications panel**

### ✍️ Property Reviews
- Add detailed reviews with ratings
- View others’ feedback on each listing

### 🤖 AI Agent (Google Gemini API)
- Integrated **AI chatbot** to assist with general real estate queries
- Behaves like a human real estate agent using Gemini’s LLM

### 💸 Price Estimation with AI
- Predict the estimated value of a property
- Users input location, size, features, and more
- Gemini API returns a fair market estimate

### 🔊 Voice-Powered Interaction (JS Web Speech API)
- AI agent responds **with voice**
- Hands-free querying and more accessible UX

---

## 🛠️ Tech Stack

| Tech | Purpose |
|------|---------|
| PHP | Backend logic |
| MySQL (phpMyAdmin) | Database |
| HTML, CSS, JavaScript | Frontend |
| JS Web Speech API | Voice replies |
| Google Gemini Free API | AI-powered assistant & price predictor |
| XAMPP | Localhost server environment |

---

## 📥 Setup Instructions

### 1. Clone this repository

### 2. Start XAMPP
Launch XAMPP

Start Apache and MySQL

### 3. Import the Database
from the zip folder use database.sql file

Click "New" and create a database with the name project

Open the Import tab

Choose the file below and click Go

This will set up all necessary tables with primary and foreign key constraints.

### 4. Run the Project
Place the project folder in htdocs directory of your XAMPP

Access it via:
http://localhost/foler_name/  ### in place of folder name  use directory where u cloned the project or downloaded foler name 

📂 Database Schema (Key Tables)
Here’s a simplified structure:

users – Manages users and roles

properties – Main listings with FK to users and locations

property_images – Linked images per property

favorites – Properties marked by users

schedule_visit – Booking visits with status updates

review – Ratings and feedback for properties/agents

property_amenities / property_features – Descriptive data

agents – Agent profiles

agent_reviews – Feedback about agents

categories, property_categories – For property classification

🧠 AI Integration
Google Gemini API (Free)
Used to power a chatbot and price prediction tool

Chatbot responds as a real estate expert

Input property specs → get price prediction

Responses include text and voice

Web Speech API (Browser JS)
Converts AI responses into spoken voice

Enhances user experience especially for accessibility

💡 Room for Improvement
This project is open-source and in active development.
Future enhancements might include:

✨ Real ML model for smarter price prediction

🗺️ Google Maps integration for location visualization

📱 Mobile responsive layout

📊 Dashboard for agents/sellers

🔐 OTP or email verification

🧾 Admin panel for listings moderation

📤 Email/SMS notifications for scheduled visits

🤝 Contributing
We welcome community collaboration!

If you'd like to:

Fix bugs

Suggest UI/UX improvements

Add new features or AI integrations

Please feel free to fork the repo and open a pull request!





# Pages Overview – DishDive  

This document provides a detailed explanation of each page in the **Tasty Tales** platform, including the layout, buttons, and input fields available to users.

---

## 1️⃣ Home Page (`/`)

### **Purpose:**

The homepage serves as the main entry point where users can explore trending recipes and search for specific dishes.  

### **Layout & Features:**

- 🔥 **Trending Recipes Section** – Displays a list of popular recipes with images, names, and short descriptions.  
- 🔎 **Search Bar** – Allows users to search recipes by **name, category, or ingredient**.  
- 🔗 **Navigation Options:**  
  - **Sign Up / Login** Button → Redirects to **Signup & Login Page**.  
  - **Click on Recipe Card** → Opens **Recipe Details Page**.  

---

## 2️⃣ Signup & Login Page (`/auth`)

### **Purpose:**

Handles user authentication, allowing new users to register and existing users to log in.  

### **Layout & Features:**

- **Sign Up Section:**  
  - 📝 **Fields:**  
    - Full Name  
    - Email  
    - Password (with visibility toggle)  
    - Confirm Password  
  - ✅ **Sign Up Button** – Registers the user and redirects to **User Dashboard**.  

- **Login Section:**  
  - 🔑 **Fields:**  
    - Email  
    - Password  
  - 🔓 **Login Button** – Authenticates user and redirects to:  
    - **User Dashboard** (for regular users)  
    - **Admin Dashboard** (for admin users)  

- 🔄 **Forgot Password?** – Allows users to reset their password.  

---

## 3️⃣ User Dashboard (`/dashboard`)

### **Purpose:**
Provides users with a personalized space to manage their recipes and favorites.  

### **Layout & Features:**

- 📋 **My Recipes Section:** Lists recipes uploaded by the user.  
- ❤️ **Bookmarked Recipes Section:** Displays saved favorite recipes.  
- ➕ **Add Recipe Button:** Redirects to **New Recipe Page**.  
- ⚙️ **Navigation:**  
  - Click on any recipe → Redirects to **Recipe Details Page**.  
  - Click **Logout** → Redirects to **Home Page**.  

---

## 4️⃣ Recipe Details Page (`/recipe/:id`)

### **Purpose:**
Displays the complete details of a selected recipe.  

### **Layout & Features:**

- 🖼 **Recipe Image & Title**  
- 🍽 **Ingredients List**  
- 📜 **Step-by-Step Instructions**  
- ⏳ **Cooking Time & Difficulty Level**  
- ⭐ **Ratings & Reviews Section:**  
  - Users can add ratings (1-5 stars).  
  - Comment box for user reviews.  
  - **Post Comment Button** to submit a review.  
- ❤️ **Save to Favourites Button** to bookmark the recipe.  
- 🔙 **Back Button** to return to the previous page.  

---

## 5️⃣ New Recipe Page (`/add-recipe`)

### **Purpose:**
Allows users to submit new recipes to the platform.  

### **Layout & Features:**

- 📝 **Fields:**  
  - Recipe Name  
  - Ingredients (multi-line input)  
  - Cooking Steps (rich text editor)  
  - Estimated Cooking Time  
  - Upload Image (optional)  
- ✅ **Submit Recipe Button** – Saves the recipe and redirects to **User Dashboard**.  

---

## 6️⃣ Admin Dashboard (`/admin`)

### **Purpose:**
Provides administrative controls for managing recipes and user interactions.  

### **Layout & Features:**

- 📜 **List of All Recipes:**  
  - Admin can **Edit** or **Delete** any recipe.  
- 💬 **User Comments & Ratings Section:**  
  - Admin can **Remove Inappropriate Comments**.  
- 🚪 **Logout Button** – Redirects to **Home Page**.  

---

## Summary of Pages & Features  

| **Page**               | **Key Features** |
|------------------------|-----------------|
| Home Page (`/`)       | Trending Recipes, Search Bar, Login/Signup |
| Signup & Login (`/auth`) | User authentication, password reset |
| User Dashboard (`/dashboard`) | View uploaded & bookmarked recipes, add new recipes |
| Recipe Details (`/recipe/:id`) | View full recipe, comments, ratings, save to favorites |
| New Recipe (`/add-recipe`) | Submit new recipe with ingredients, steps, and image |
| Admin Dashboard (`/admin`) | Manage recipes, remove comments |

This structure ensures a seamless user experience and organized content flow throughout the **Tasty Tales** platform. 🚀
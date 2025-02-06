# Navigation Flow – Tasty Tales

## Home Page (`/`)

- Displays trending recipes.  
- Provides a **Search Bar** to find recipes by name, category, or ingredient.  
- Users can browse recipes **without logging in**, but actions like bookmarking and commenting require authentication.  
- **Navigation Options:**  
  - Click on a recipe → Redirects to **Recipe Details Page** (`/recipe/:id`).  
  - Click on **Login / Signup** → Redirects to **Signup & Login Page** (`/auth`).  

## Signup & Login Page (`/auth`)

- Users can **sign up** or **log in** using email and password.  
- On successful login:  
  - **User** → Redirects to **User Dashboard** (`/dashboard`).  
  - **Admin** → Redirects to **Admin Dashboard** (`/admin`).  

## User Dashboard (`/dashboard`)

- Displays:  
  - User's **uploaded recipes**.  
  - **Bookmarked recipes**.  
  - Option to **add a new recipe**.  
- **Navigation Options:**  
  - Click on a recipe → Redirects to **Recipe Details Page** (`/recipe/:id`).  
  - Click **Add Recipe** → Redirects to **New Recipe Page** (`/add-recipe`).  
  - Click **Logout** → Redirects to **Home Page** (`/`).  

## Recipe Details Page (`/recipe/:id`)

- Displays:  
  - Recipe name, ingredients, steps, and cooking time.  
  - User-uploaded images (if any).  
  - **Comment and Rating** section for user interaction.  
  - **"Save to Favourites"** option for bookmarking.  
- **Navigation Options:**  
  - Click **Back** → Redirects to **previous page**.  
  - Click on **a different recipe** → Redirects to **that recipe’s details page**.  

## Admin Dashboard (`/admin`)

- Displays:  
  - **All uploaded recipes**.  
  - **User comments and ratings**.  
- Admin can:  
  - **Edit or delete any recipe**.  
  - **Remove inappropriate comments**.  
- **Navigation Options:**  
  - Click on a recipe → Redirects to **Recipe Details Page** (`/recipe/:id`).  
  - Click **Logout** → Redirects to **Home Page** (`/`).  

---

## Summary of Navigation Flow  

1️⃣  **Home Page** → Browse recipes / Login or Signup  
2️⃣ **Signup & Login Page** → Redirects to User/Admin Dashboard  
3️⃣ **User Dashboard** → View recipes / Add new recipes / Open Recipe Details  
4️⃣ **Recipe Details Page** → View recipe details / Comment & Rate / Save to Favourites  
5️⃣ **Admin Dashboard** → Manage recipes & comments  

This structured navigation ensures a **smooth user experience** and **easy accessibility** to all features in the **Tasty Tales** platform. 🚀
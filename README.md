# 📊 ECommerce Dashboard Analysis

## 📝 Project Description
This project represents a significant advancement over previous work by leveraging advanced dynamic measures and interactive elements to deliver a fully customizable and user-friendly dashboard experience for an American eCommerce company.

---

## 🔎 Overview
I designed a highly interactive **Home Page** that allows seamless navigation between two primary dashboards:

- **Sales & Profit Analysis Dashboard**  
  Analyzes sales and profit metrics by product, store location (branch), and marketing campaigns.

- **Customer & Salesperson Analysis Dashboard**  
  Provides insights into customer distribution by region and segments (Loyal, High Value, etc.) and evaluates the performance of each salesperson.

---

## 🎛 Interactive Features
The dashboards empower users to dynamically explore data using interactive buttons to switch between:

- **Top N performers**
- **Bottom N performers**
- **Custom selections**

👉 Users can define the value of **N** (e.g., Top 5, Top 8) with a slicer, which updates chart titles dynamically.  
👉 In **Custom Mode**, users can select specific products or individuals via a hidden slicer that appears only when needed, keeping the interface clean.

---

## ⚙️ Technical Highlights
- Developed **DAX measures** for flexible data display and dynamic chart updates.  
- Applied **conditional formatting** in charts with colors:  
  - 🟢 Green → Top performers  
  - 🔴 Red → Lowest performers  
  - 🟡 Beige → Intermediate values  
- Built **dynamic titles** that adjust automatically based on slicer choices.  
- Created logical measures to minimize excessive filtering and boost report performance.  
- Designed supporting tables:  
  - **ViewMode** → For mode selection (Top/Bottom/Custom).  
  - **TopN_Selector** → For setting number of displayed items.  
- Implemented **Bookmarks** to toggle slicer visibility in Custom Mode for a tidy interface.  

---

## 👤 User Experience
All interactivity is managed through **a single visual per dashboard**, which:  
- Optimizes space.  
- Reduces visual clutter.  
- Simplifies user interaction.  
- Improves understanding of complex datasets.  

---

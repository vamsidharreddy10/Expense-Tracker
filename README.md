# Expense-Tracker
by vamsidharredy
# Expense Tracker (LocalStorage)

A simple **Expense & Income Tracker** built with HTML, CSS, and JavaScript.  
It uses **LocalStorage** to save your data in the browser — no backend required.  
Charts are powered by **Chart.js**.

---

## 🚀 Features
- Add/Edit/Delete **income & expense** entries.
- Categorize transactions:
  - Food, Travel, Shopping, Bills, Health, Salary, Freelance, Other.
- Save all data in `localStorage` (`expenseTracker_entries`).
- **List view**:
  - Filter by month.
  - Delete individual entries.
  - Edit entries.
  - Clear all data.
- **Export/Import JSON**:
  - Backup your transactions.
  - Restore or share data across devices.
- **Sample Data Inserter** (for quick testing).
- **Charts** (via Chart.js):
  - Bar Chart → Income vs Expense per month.
  - Pie Chart → Expense breakdown by category (selected month).
- **Responsive Design**:
  - Works on desktop, tablet, and mobile screens.

---

## 📂 Project Structure
index.html → Main app
style.css → Styling
script.js → Functionality



---

## 🛠️ How to Run
1. Download or clone this repo.
2. Open `index.html` in any browser.
3. Start tracking your expenses 🚀

---

## 📦 Storage
- All data is saved in your browser’s **localStorage**.
- Key used: `expenseTracker_entries`
- Data persists even after refresh or closing the browser.
- To share or migrate data → use **Export/Import JSON**.

---

## 📊 Example Use
1. Add income (Salary ₹50,000).
2. Add expense (Food ₹500, Travel ₹200).
3. View charts:
   - Bar chart: Monthly income vs expenses.
   - Pie chart: Expense distribution.

---

## ⚠️ Limitations
- Data is stored **locally only** (per browser).
- Clearing browser storage will remove your data.
- For cross-device sync → backend (Firebase, Supabase, etc.) would be required.

---

## 📜 License
Free to use, modify, and distribute.

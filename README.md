# 3G-Calc
# 3G Project Revenue Calculator

This interactive calculator helps attribute project revenue across team members based on defined roles, credit percentages, and ownership. It was built for use in **ClickUp dashboards** via the Custom Embed widget and is hosted on GitHub Pages.

## 🔗 Live Link

Use this URL in your ClickUp embed:  
**https://deeitz.github.io/3G-Calc/**  
(You can append `?v=1`, `?v=2`, etc. to force refresh in ClickUp)

---

## 🔧 Features

- Editable **projected revenue** input (auto-formatted)
- Role-by-role **credit percentage** and **owner assignment**
- “Split” logic automatically divides values between the first two owners
- **Comma-formatted dollar amounts**
- Auto-updating **owner totals with percentage of project total**
- Fully editable — change roles, owners, and percentages as needed
- Dark and light theme compatible for ClickUp

---

## 📁 File Overview

- `index.html` – Main calculator interface (auto-served via GitHub Pages)
- `README.md` – This file

---

## 🧠 Usage Notes

- To update logic, appearance, or default values, simply modify `index.html` and commit changes.
- ClickUp may cache pages aggressively. To bust the cache, use `?v=` in the URL:

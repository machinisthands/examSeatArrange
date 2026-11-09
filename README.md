# 🎓 Exam Seating Arrangement System

A powerful, offline-first, single-file web application designed to automate and manage exam seating arrangements, hall layouts, question paper requirements, and attendance sheets effortlessly.

<a href="https://machinisthands.github.io/examSeatArrange/" target="_blank">
  <img src="https://img.shields.io/badge/🚀_Live_Preview-Click_Here-blue?style=for-the-badge" alt="Live Preview">
</a>

---

## ✨ Features

- **100% Offline Support:** Built into a single HTML file with embedded styles and scripts (Bootstrap included). Runs entirely in your browser without needing an internet connection. No data is stored externally.
- **Student & Subject Management:** Easily add students and subjects individually or via **Bulk CSV/Excel Import**.
- **Hall Layout & Customization:** Configure multiple halls with custom rows, columns, and bench seating capacities (1, 2, or 3 students per bench). Block specific seats or aisles easily.
- **Smart Seating Patterns:** Supports various distribution patterns (ABAB, AABB, ABBA, ABCABC, and Custom) with built-in checks to ensure no same-subject students sit adjacent to each other.
- **Comprehensive Reports & Export:**
  - Hall-wise Seating Charts & Notice Board displays.
  - Hall-wise Question Paper Requirement lists.
  - Attendance sheets and absentee tracking.
  - Direct **PDF downloads** and **Print** support.
- **Backup & Restore:** Save your complete arrangement state using Excel Backup and restore it anytime.

---

## 🚀 Getting Started

1. **Clone or Download:** Clone this repository or download the `index.html` file directly.
2. **Run:** Open the `index.html` file in any modern web browser (Chrome, Firefox, Edge, etc.). No server setup or installation is required!

---

## 📖 How to Use

1. **Setup Tab:** 
   - Enter your Exam Name, Date, Institution, and Session (FN/AN).
   - Add your subjects and manage your student list (manual entry or bulk upload via Excel/CSV).
   - Configure your exam halls with respective rows and columns.
2. **Hall Layout Tab:**
   - Select your hall, view the visual seating grid, and click **Assign** to automatically generate the seating arrangement based on your chosen pattern.
3. **Export / Reports Tab:**
   - View, print, or download PDF/Excel reports, notice boards, and question paper requirements.
   - Use the **Excel Backup** feature to save your work securely.

---

## 🛠️ Built With

- **HTML5 / CSS3 / JavaScript**
- **Bootstrap 5** (Embedded styling)
- **SheetJS (xlsx)** for Excel processing and data handling.

---

## 📄 License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute this software for educational and institutional purposes.

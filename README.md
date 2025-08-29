
---

## 🚀 How to Use

1. Clone or download this repo.  
2. Open `Birthday_Reminder.html` in any modern browser (Chrome, Edge, Firefox).  
3. Use **Add / Edit** to create or update birthday entries.  
4. Click **Save Birthday File** to export data to Excel (`.xlsx`).  
5. Click **Send** to export **today’s birthdays** into a styled **PDF**.  
6. Reload later and use **Open Birthday File** to import the saved Excel again.

---

## 🛠️ Tech Used

- **[SheetJS (xlsx)](https://github.com/SheetJS/sheetjs)** — Excel import/export  
- **[jsPDF](https://github.com/parallax/jsPDF)** + **[AutoTable plugin](https://github.com/simonbengtsson/jsPDF-AutoTable)** — PDF generation  


---

## 📌 Notes

- Works fully offline after first load (libraries included via CDN).  
- Phone numbers are stored as **text** in Excel to avoid number formatting issues.  
- Month parsing accepts: `Jan`, `January`, `1`, `01`, etc.  
- If no birthdays are found today, PDF shows a placeholder row with `—`.

---

## 📜 License

MIT License © 2025 — Free for personal and commercial use.

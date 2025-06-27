# Excel Assessment Project

This project contains solutions to a structured Excel-based assessment with 5 tasks, aimed at testing Excel proficiency including data formatting, formula usage, conditional formatting, and data aggregation.

## 📁 Tabs Used

- **Dataset**: Main sheet containing data and solutions for Tasks 3, 4, and 5.
- **Datasheet**: Supporting sheet used for Tasks 1 and 2.

---

## ✅ Tasks Completed

### **Task 1: Conditional Formatting**
- **Objective**: Highlight all `-1` values in **red** and `0` values in **green** in the *Datasheet* tab.
- **Solution**: Used Conditional Formatting rules:
  - Formula: `=A1=-1` → Format: Fill Red
  - Formula: `=A1=0` → Format: Fill Green

### **Task 2: Freeze Top Row**
- **Objective**: Freeze the top row in the *Datasheet* tab to keep headers visible while scrolling.
- **Solution**: View → Freeze Panes → Freeze Top Row.

### **Task 3: Sum of Values > 20**
- **Objective**: Compute the **sum of all values greater than 20** in column **H ('car2')** of the *Dataset* tab.
- **Formula Used**:
  ```excel
  =SUMIF(H:H, ">20")

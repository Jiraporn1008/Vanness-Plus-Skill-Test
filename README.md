# Vanness-Plus-Skill-Test
# 📁 Excel Data Mapper

A web application that reads two types of Excel files and maps **passed candidates** from daily reports to newly joined employees, generating a clean dashboard of matched data.

## ✨ Features

- Upload and parse `.xls` files directly in the browser
- Detects two Excel file types:
  - `Daily report_YYYYMMDD_Name_Surname.xls`
  - `New Employee_YYYYMM.xls`
- Only candidates with **Status = "Pass"** in daily reports are processed
- Cross-maps passed candidates with new employees
- Builds a dashboard with matched data (Employee Name, Join Date, Role, and Team Member)

## 🚀 How to Use

### Run Locally

1. **Clone** or **download** the repository.
2. Open `index.html` in any modern web browser.
3. Upload one or more Excel files following these formats:
   - `Daily report_YYYYMMDD_First_Last.xls`
   - `New Employee_YYYYMM.xls`
4. The app will automatically:
   - Parse uploaded files in-browser
   - Display data tables for each file
   - Identify candidates with `"Pass"` status
   - Match them with employee records
   - Show results in a unified dashboard

### Run on GitHub Pages

1. Visit the [GitHub Pages deployment](#) *([Vanness Plus Skill Test](https://jiraporn1008.github.io/Vanness-Plus-Skill-Test/))*.
2. Upload your Excel files:
   - `Daily report_YYYYMMDD_First_Last.xls`
   - `New Employee_YYYYMM.xls`
3. The app will:
   - Parse and display tables
   - Perform cross-mapping
   - Generate the dashboard view

## 📁 Sample data

Use the link below to access and download sample Excel files for testing: 
https://drive.google.com/drive/folders/1SFCYdKnnb9kayWI30Bo9Z6cHD-PafuhB?usp=sharing
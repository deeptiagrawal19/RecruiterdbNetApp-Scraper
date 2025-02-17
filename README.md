# RecruiterdbNetApp-Scraper
Automate the extraction of recruiter emails from RecruiterDB using Selenium and AppleScript on macOS. This script interacts with the website, clicks on email buttons, copies email addresses via the Mail app, and stores them in an Excel file.

## **Disclaimer: Designed Exclusively for RecruiterDB**
🔴 **This script is specifically developed to extract recruiter emails from [RecruiterDB](https://recruiterdb.web.app/).**  
🔴 **The logic is tailored to the structure and behavior of this website, including button interactions, email retrieval, and pagination handling.**  

💡 While the core automation principles remain the same, the script may require modifications to adapt to other websites due to variations in UI elements and authentication mechanisms.  

---

## **Overview**
This Python script automates the extraction of recruiter emails from **RecruiterDB** using:  
✅ **Selenium** for web interactions  
✅ **AppleScript** (macOS) to copy email addresses from the Mail app  
✅ **Pagination handling** to process all available recruiters  
✅ **Excel export** (`recruiters.xlsx`) for easy access  

---

## **⚙️ Prerequisites**
### **System Requirements**
- **macOS** (AppleScript is required)
- **Python 3.x**
- **Google Chrome**
- **ChromeDriver** (ensure correct installation)

### **Install Dependencies**
Run the following command to install required libraries:
```bash
pip install selenium pandas
```
---
How It Works
Manually log in to RecruiterDB when prompted.
Press Enter after logging in to allow the script to proceed.
The script will extract recruiter names & emails and store them in recruiters.xlsx.
It will automatically process pagination and stop once all recruiters have been scraped.

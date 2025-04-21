# CTRL-ALT-DEBT
A versatile Python-based financial tracker that calculates expenses, visualizes weekly, monthly, and yearly spending, generates PDF reports, and emails them seamlessly for effective personal budgeting and insights.



---

# CTRL-ALT-DEBT (Personal Finance Tracker with Visualizations)

## Overview
The **Personal Finance Tracker** is a Python-based tool designed to help users track their financial details, generate visual insights, and export the data in a comprehensive report. This tool combines functionality, data visualization, and email delivery, making it an all-in-one solution for personal financial management.

---

## Features
- **Comprehensive Input:** Capture financial data such as income, taxes, health plans, rent, groceries, and more.
- **Balance Calculation:** Calculate your remaining balance after accounting for all expenses.
- **Expense Breakdown:** View categorized expenses to understand your spending habits.
- **Visualizations:**
  - Weekly Spending Breakdown
  - Monthly Spending Breakdown
  - Yearly Spending Breakdown
- **PDF Export:** Generates a PDF report that includes your financial data and visualizations.
- **Email Delivery:** Automatically emails the PDF report to a specified email address.
- **User-Friendly Interface:** Designed for ease of use with validation and prompts.

---

## Installation
To get started, you’ll need Python and the following dependencies:
1. Install Python packages:
   ```
   pip install matplotlib fpdf
   ```

2. Ensure you have an email account (e.g., Gmail) configured for SMTP to enable the email feature.

---

## Usage
1. **Run the Script:** Start the program by running `python script_name.py` in your terminal.
2. **Input Your Data:** Enter financial details as prompted.
3. **View Results:** See a summary of your balance and expense breakdown.
4. **Generate Visualizations:** Automatically creates bar charts for weekly, monthly, and yearly spending.
5. **Export and Email:** A PDF report containing your financial summary and visualizations will be emailed to `robert.hodgkiss@my.utsa.edu` by default. Update the recipient email in the script if needed.

---

## Example Output
- **Weekly Spending Chart:** A bar chart that shows your weekly spending per category.
- **Monthly Spending Chart:** Aggregates weekly spending to show a monthly overview.
- **Yearly Spending Chart:** Projects yearly spending based on weekly data.
- **PDF Report:** Contains a financial summary and all generated visualizations.

---

## Configuration
1. **SMTP Email Settings:** Update the following fields in the script:
   ```python
   sender_email = "your_email@example.com"
   sender_password = "your_password"
   ```
2. **Recipient Email:** Replace the email address in the line:
   ```python
   email_pdf(pdf_filename, "robert.hodgkiss@my.utsa.edu")
   ```

---

## Libraries Used
- **Matplotlib:** For data visualization.
- **FPDF:** For generating PDF reports.
- **smtplib:** For sending emails.

---

## Notes
- Ensure accurate input of financial data.
- Use a secure, application-specific password for your email account when configuring SMTP settings.

---

## Future Enhancements
- Adding more financial categories or customizing them.
- Providing additional visualization types like pie charts or time-series trends.
- Integrating with cloud storage for secure data backup.

---

Enjoy managing your finances effortlessly with this tool! If you encounter any issues or need further customization, feel free to reach out.

--- 

Let me know if you’d like me to further refine this!

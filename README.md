## 📌 Project Overview
This dashboard provides a comprehensive 360-degree view of the bank’s loan portfolio, enabling stakeholders to monitor lending performance and financial stability in real-time. By aggregating key metrics like **Total Funded Amount**, **MTD (Month-to-Date) Applications**, and **Average Interest Rates**, it offers a strategic snapshot of capital deployment.

The summary highlights the balance between **'Good' and 'Bad' loans**, allowing for immediate assessment of credit risk and net interest margins to ensure long-term portfolio sustainability.

---

## 📊 Key Features & Metrics
The dashboard is divided into three main areas of analysis:

### 1. Summary
* **Total Loan Applications:** Tracking the volume of requests received.
* **Total Funded Amount:** The total capital currently deployed.
* **Total Amount Received:** Monitoring cash inflow from repayments.
* **Average Interest Rate & DTI:** Assessing the cost of lending and borrower debt health.
* * **Good Loans:** Monitoring fully paid and current loans to measure portfolio strength.
* **Bad Loans (NPL):** Identifying non-performing loans (Charged Off) to mitigate risk.

  <img width="1769" height="1018" alt="Screenshot 2026-01-16 110647" src="https://github.com/user-attachments/assets/dae8965e-f935-4189-a441-5e248d06c106" />


### 2. Overview
* **Total Loan Application by month:** To identify seasonality and long-term trends in lending activities
* **Total Loan Application by State:** To identify regions with significant lending activity and assess regional disparities
* **Total Loan Application by Teram:** To allow the client to understand the distribution of loans across various term lengths.
* **Employee Length Analysis (Bar Chart):** How lending metrics are distributed among borrowers with different employment lengths, helping us assess the impact of employment history on loan applications.
* **Loan Purpose Breakdown (Bar Chart):** Will provide a visual breakdown of loan metrics based on the stated purposes of loans, aiding in the understanding of the primary reasons borrowers seek financing.
* **Home Ownership Analysis (Tree Map):** For a hierarchical view of how home ownership impacts loan applications and disbursements.




* <img width="1765" height="978" alt="Screenshot 2026-01-16 110934" src="https://github.com/user-attachments/assets/6a73ed3b-0820-4940-9b0d-e3334c0beffc" />



### 3.Details
GRID:Need for a comprehensive 'Details Dashboard' that provides a consolidated view of all the essential information within our loan data. This Details Dashboard aims to offer a holistic snapshot of key loan-related metrics and data points, enabling users to access critical information efficiently.

Objective: The primary objective of the Details Dashboard is to provide a comprehensive and user-friendly interface for accessing vital loan data. It will serve as a one-stop solution for users seeking detailed insights into our loan portfolio, borrower profiles, and loan performance.

<img width="1765" height="978" alt="Screenshot 2026-01-16 112408" src="https://github.com/user-attachments/assets/70e2c11a-b514-42ac-9353-20872fe5c75d" />



---

## 🛠️ Tech Stack
* **Data Analysis:** SQL (PostgreSQL/MySQL)
* **Data Visualization:** [Power BI / Tableau / Excel]
* **Data Processing:** Python (Pandas)

---

## 📂 Installation & Usage
1. **Clone the repository:**
   ```bash
   git clone https://github.com/jatinkanyan/Bank-Loan-Dashoard/tree/main


Database Setup: Run the provided SQL scripts in the /sql folder to generate the necessary tables.

Open the Dashboard: Open the .pbix or .twb file using the respective visualization software.

📝 Business Impact
This tool allows financial institutions to:

Identify high-risk segments before they impact the bottom line.

Optimize interest rate strategies based on borrower profiles.

Streamline the loan approval process by monitoring MTD application trends.

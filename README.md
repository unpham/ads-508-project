# **Ads-508-project: Data Science With Cloud Computing**

### **Partner(s)/Contributor(s)**
Authors: Harini Lakshmanan, Uyen Pham, Stephen Reagin

Company Name: Clever Compensation Company Name [C3N]

Company Industry: HR consulting

Company Size: 3 people

### **Abstract**
We are an HR consulting firm which has been tasked by several municipalities in California to perform an audit on the compensation practices for municipal employees.

Municipal budgets are funded through taxpayer resources, and voters have a right to know how their resources are being allocated for city employment practices. Several cities in California, notably Los Angeles, San Francisco, and San Jose have all released their city payroll 10-year historical information for public consumption. Auditing this information is vital to ensure the public trust in continuing to fund municipal employees for the services they perform on behalf of the public.

As an HR consulting firm, we see this as an opportunity to understand the current state of affairs, recognize the historical trends in pay practices, and identify areas for improvement. The open data sources allow us to look for trends in overall pay practices, as well as take a nuanced dive into differentiation by geographic region and by department.

### **Goals:**
Anomaly detection, and seeing if there are any groups or individuals who have been historically underfunded relative to their municipal counterparts. Understanding the different components of compensation, e.g. salary, bonus, overtime, benefits, etc. This will allow municipalities to better understand their payroll budgets on a going-forward basis.

### **Non-Goals:**
We are intentionally not tying crime statistics to police department budgets. While we recognize this is an active area of interest and research, and would be a great next step for further development, such an undertaking would be outside the scope of our company’s objective to audit current pay practices. We are not predicting or recommending any overall municipal budgets because that is normally decided by a City Council working in partnership with a Mayor’s office, all of whom are answerable to voters.

### **Data Sources:**
The data was stored in an AWS S3 bucket.

Los Angeles [city controller data] https://controllerdata.lacity.org/Payroll/City-Employee-Payroll-Current-/g9h8-fvhu 1 CSV file with 753,458 rows and 18 columns

San Jose open data portal https://data.sanjoseca.gov/dataset/employee-compensation-plan 10 CSV files (1 per year), each having 7500 - 8500 rows and 12 columns

San Francisco DataSF https://data.sfgov.org/City-Management-and-Ethics/Employee-Compensation/88gCity Employee Payroll (Current) | Control Panel LA8-5mnd 1 CSV file with 799,652 rows and 22 columns

Consumer Price Index https://www.minneapolisfed.org/about-us/monetary-policy/inflation-calculator/consumer-price-index-1913- 1 CSV file with 9 rows and 3 columns

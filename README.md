**HR-Analytics-Employee-Attrition**

**A. Project Overview**

- This project analyzes employee attrition in X company.
- The focus is on identifying key risk factors and support HR improve retention.

**B. Dataset Information**

**Source**

- Kaggle Dataset: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data
- In my Analysis, Performance Rating was dropped since most employees were rated as 3 or 4, leading to very low variance and limited predictive power.
- Irrelevant or constant variables (EmployeeNumber, EmployeeCount, Over18, StandardHours, etc.) were removed during preprocessing to keep the dataset clean and focused on impactful features.
- Monthly income was not segmented across the whole company because compensation is inherently tied to JobRole/JobLevel. Without a market salary benchmark or within-role normalization, such segmentation would be misleading, so it was excluded.

**Period**

This Dataset is updated 08 years ago.

**C. Methodology**

Data Cleaning (Python) → Descriptive Analysis → Actionable Insights

**D. Key Findings and Actionable Plans**

**Key Findings**

- Overall attrition rate is 16.1%, while the average tenure is over 7 years → Ít nhân sự lâu năm --> Phúc lợi công ty có vấn đề
- R&D is the department which has the highest number of employees (65.37%), however attrition rate of this department is also high too
- Employees is mainly get married (45.78%)
- Nhân viên chủ yếu là nhà gần
- Trình độ học vấn phần lớn ở mức 3/5
- Phần lớn NV chỉ làm ở 1 công ty (nghĩa là trước đây không làm công ty khác). Vậy công ty X này là nhận fresher đào tạo rồi cho nên phần lớn level nhân viên chỉ ở mức 1, 2
- Employees with lower Engagement Score is more likely to leave (2.77 > 2.54).
- Employees who worked overtime is more likely to leave (74.52%) → Emergency
- Nguy cơ nghỉ việc cao nhất ở nhóm NV mới vào (0 - 2 years)
- Attrition rate tăng khi NV sau 5 năm không được thăng chức
- Thời gian làm việc với quản lý càng lâu thì càng giảm tỷ lệ nghỉ việc

**Actionable Plans**

- Đào sâu phúc lợi công ty (các chỉ số liên quan:

**E. Visualization**

[Dashboard Overview](Dashboard/Overview.png)

**F. About Me**

Hi, I'm Navin (Bao Vy) – an aspiring Data Analyst passionate about turning raw data into actionable business insights. For more details, please reach out at: 

- 📊 Skills: SQL, Python, Power BI.  
- 🌐 LinkedIn: https://www.linkedin.com/in/navin826/
- 📂 Portfolio: https://github.com/CallmeNavin/  

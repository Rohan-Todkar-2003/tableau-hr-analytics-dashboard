# 📊 HR Analytics Dashboard

<div align="center">

  
  [![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)](https://public.tableau.com/app/profile/rohan.todkar/vizzes)
  [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rohan-Todkar-2003/tableau-hr-analytics-dashboard)
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rohantodkar0705/)

</div>

## 🎯 Business Overview

A comprehensive **Human Resources Analytics Dashboard** designed to empower HR managers, executives, and department heads with actionable workforce insights. This interactive Tableau dashboard transforms raw employee data into strategic intelligence, enabling data-driven decisions for workforce optimization, diversity monitoring, and compensation analysis.

**🔍 Business Impact:**
- **Optimize Workforce Planning** - Monitor hiring trends and departmental growth
- **Ensure Pay Equity** - Analyze salary distributions across demographics  
- **Track Employee Lifecycle** - From recruitment to retention analytics
- **Support Strategic Decisions** - Executive-level workforce insights

---

## ✨ Key Features

### 📈 **Summary Analytics**
- [x] 📊 **Workforce Overview** - Total employees, hiring trends, and termination analytics
- [x] 🏢 **Department Insights** - Employee distribution across all departments and job titles
- [x] 🗺️ **Geographic Analysis** - Headquarters vs. branch office comparisons
- [x] 👥 **Demographics Deep-dive** - Gender ratios, age groups, and education levels
- [x] 💰 **Compensation Analysis** - Salary equity across education, gender, and age groups

### 📋 **Detailed Employee Records**
- [x] 🔍 **Comprehensive Employee List** - Complete employee directory with all key attributes
- [x] 🎛️ **Advanced Filtering** - Filter by department, role, location, salary range, and more
- [x] ⏱️ **Employment Timeline** - Track hire dates and length of employment
- [x] 📊 **Performance Insights** - Performance ratings linked to employee profiles

---

## 📱 Dashboard Pages

<details>
<summary><strong>🏠 Overview Dashboard (Summary View)</strong></summary>

### Overview Section
- **Total Employees**: 7,984 Active | 8,950 Hired | 966 Terminated
- **Hiring Trends**: Year-over-year hiring and termination patterns
- **Department Distribution**: Operations leads with 2,429 employees, followed by Sales (1,634) and Customer Service (1,489)
- **Geographic Spread**: Headquarters vs. branch analysis with interactive map

### Demographics Section  
- **Gender Distribution**: 46% Female | 54% Male
- **Age Groups**: Balanced across 25-34 (25%), 35-44 (31%), 45-54 (24%)
- **Education Mix**: Bachelor's degree holders dominate the workforce

### Income Analysis
- **Salary by Education**: PhD holders earn 93K | Master's 86K | Bachelor's 74K | High School 63K
- **Age-Salary Correlation**: Clear progression showing experience-based compensation
- **Gender Pay Analysis**: Comparative salary analysis across education levels

[/dashboard/snapshots/HR  Summary.png](https://github.com/Rohan-Todkar-2003/tableau-hr-analytics-dashboard/blob/main/dashboard/snapshots/HR%20%20Summary.png)

</details>

<details>
<summary><strong>📋 Employee Records Dashboard (Detailed View)</strong></summary>

### Interactive Employee Directory
- **Complete Employee List**: 8,950+ employee records with comprehensive details
- **Smart Filtering**: Filter by ID, Demographics, Role, Geography, Salary, and Status
- **Key Information Display**:
  - Employee ID and personal details
  - Department and job title
  - Location (city/state)
  - Current salary
  - Employment status and tenure
  - Length of employment visualization

### Filter Capabilities
- 🆔 **ID**: Search specific employees
- 👥 **Demographics**: Age, gender, education level
- 💼 **Role**: Department and job title filtering  
- 🌍 **Geography**: State and city-based filtering
- 💰 **Salary**: Salary range selection
- 📊 **Status**: Active vs. terminated employees

[/dashboard/snapshots/HR  Details.png](https://github.com/Rohan-Todkar-2003/tableau-hr-analytics-dashboard/blob/main/dashboard/snapshots/HR%20%20Details.png)

</details>

---

## 🎯 Business Value & Use Cases

### 👔 **For Executives**
- **Strategic Workforce Planning**: Monitor hiring trends and departmental growth patterns
- **Cost Management**: Analyze total compensation costs across departments
- **Diversity Metrics**: Track gender and education diversity across the organization
- **Geographic Distribution**: Optimize office locations and remote work policies

### 🎭 **For HR Managers**  
- **Recruitment Analytics**: Identify hiring patterns and department needs
- **Retention Analysis**: Track termination trends and identify risk factors
- **Compensation Equity**: Ensure fair pay across gender, education, and experience levels
- **Performance Correlation**: Link education background to performance ratings

### 🏢 **For Department Heads**
- **Team Composition**: Understand department demographics and skill levels
- **Budget Planning**: Analyze age-salary correlation for compensation planning
- **Talent Development**: Identify education and performance improvement opportunities
- **Resource Allocation**: Balance team sizes and experience levels

---

## 🚀 Live Demo

**🌐 Interactive Dashboard**: [View on Tableau Public](https://public.tableau.com/app/profile/rohan.todkar/vizzes)

*Experience the full interactive capabilities including filtering, drill-down analysis, and real-time data exploration.*

---

## 🛠️ Getting Started

### Prerequisites
- Tableau Desktop (2020.1 or later recommended)
- CSV file handling capability
- Basic understanding of Tableau workbooks

### 📥 Quick Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Rohan-Todkar-2003/tableau-hr-analytics-dashboard.git
   cd tableau-hr-analytics-dashboard
   ```

2. **Open the Dashboard**
   - Launch Tableau Desktop
   - Open `dashboards/main_dashboard.twb`
   - Connect to the data source: `data/HumanResources.csv`

3. **Refresh & Explore**
   - Refresh data connections
   - Navigate between "Overview" and "Details" pages
   - Use interactive filters to explore insights

### 📊 Working with Your Own Data

To use this dashboard with your own HR data:

1. **Data Format**: Ensure your CSV includes these columns:
   - `employee_id`, `first_name`, `last_name`, `gender`
   - `state`, `city`, `hiredate`, `department`, `job_title`
   - `education_level`, `salary`, `performance_rating`
   - `birthdate`, `termdate` (optional)

2. **Replace Data Source**: 
   - In Tableau, go to Data → Replace Data Source
   - Select your CSV file
   - Verify field mappings

---

## 🔧 Tech Stack

| Technology | Purpose |
|------------|---------|
| **Tableau Public** | Data visualization and dashboard creation |
| **Python** | Data generation and preprocessing |
| **CSV** | Data storage format |
| **GitHub** | Version control and project hosting |

---

## 📈 Dataset Overview

**Dataset Specifications:**
- **Records**: 8,950 employee records
- **Time Period**: 2015-2024 employment data
- **Geographic Coverage**: 8 US states with 24+ cities
- **Departments**: 7 major departments with 28 unique job titles
- **Demographics**: Balanced gender and age distribution
- **Education Levels**: High School to PhD representation

<details>
<summary><strong>📋 Data Schema</strong></summary>

| Column | Description | Data Type |
|--------|-------------|-----------|
| `employee_id` | Unique employee identifier | String |
| `first_name` | Employee first name | String |
| `last_name` | Employee last name | String |
| `gender` | Gender (Male/Female) | String |
| `state` | US state location | String |
| `city` | City location | String |
| `hiredate` | Date of hire | Date |
| `department` | Department name | String |
| `job_title` | Specific job title | String |
| `education_level` | Education qualification | String |
| `salary` | Annual salary (USD) | Integer |
| `performance_rating` | Performance evaluation | String |
| `overtime` | Overtime eligibility | String |
| `birthdate` | Date of birth | Date |
| `termdate` | Termination date (if applicable) | Date |

</details>

---

## 🚀 Future Enhancements

### 🎯 **Planned Features**
- [ ] **Predictive Analytics**: Employee attrition prediction models
- [ ] **KPI Scorecards**: Department-specific performance metrics  
- [ ] **Real-time Integration**: Connect to live HR database systems
- [ ] **Mobile Optimization**: Responsive design for mobile devices
- [ ] **Advanced Filtering**: Multi-level hierarchical filters

### 💡 **Potential Integrations**
- **HR Systems**: ADP, Workday, BambooHR integration
- **Performance Tools**: 360-degree feedback system connection
- **Recruitment Platforms**: LinkedIn, Indeed analytics integration

---

## 🤝 Contributing

We welcome contributions to improve this HR analytics solution!

### How to Contribute

1. **Fork** this repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### 💡 **Contribution Ideas**
- Additional visualization types
- New KPI calculations
- Enhanced filtering options
- Performance optimizations
- Documentation improvements

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Contact & Connect

**📧 Project Maintainer**: Rohan Todkar

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/rohantodkar0705/)
[![Tableau Public](https://img.shields.io/badge/Tableau-Portfolio-orange?style=for-the-badge&logo=tableau)](https://public.tableau.com/app/profile/rohan.todkar/vizzes)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=for-the-badge&logo=github)](https://github.com/Rohan-Todkar-2003)

</div>

---

<div align="center">

**⭐ If this project helped you, please give it a star! ⭐**

*Built with ❤️ for better HR analytics*

</div>

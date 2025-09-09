# Amazon Sales Dashboard - Q2 2022 Analysis

A comprehensive Power BI dashboard analyzing Amazon sales performance for Q2 2022, providing actionable insights for business growth and optimization.

![Dashboard Overview](https://github.com/KIRANRW9/Amazon-Sales-Insights-PowerBI/blob/repo-exercise/images/1_overview.png)

## 📊 Dashboard Overview

This interactive Power BI dashboard provides deep insights into Amazon sales performance across multiple dimensions including geographic distribution, customer segmentation, product categories, and operational metrics.

### Key Metrics at a Glance
- **Total Orders**: 129K orders (↗ +41.1% vs previous month)
- **Total Revenue**: ₹78.49M (↗ +42.4% vs previous month)
- **Average Order Value**: ₹609.38 (↗ +10.8% vs previous month)
- **Order Success Rate**: 62.75%
- **Customer LTV Ratio**: 3.7x (Premium vs Basic)

## 🗂️ Project Structure

```
Amazon-Sales-Dashboard/
│
├── data/
│   ├── sample_data.csv
│   └── data_dictionary.md
│
├── dashboards/
│   ├── Amazon_Sales_Dashboard.pbix
│   └── Amazon_Sales_Dashboard.pdf
│
├── images/
│   ├── overview.png 
│   ├── analytics.png
│   └── insights.png
│
├── README.md
└── LICENSE
```

## 📈 Key Features

### 1. **Overview Tab**
![Overview Analytics](https://github.com/KIRANRW9/Amazon-Sales-Insights-PowerBI/blob/repo-exercise/images/1_overview.png)

- **Date Range Filter**: Flexible filtering for Q2 2022 (Apr-June)
- **Order Status Distribution**: Visual breakdown of shipped (62.73%), delivered (22.32%), cancelled (14.22%), and pending (0.73%) orders
- **Monthly Trend Analysis**: Order volume tracking showing decline from 49.1K (April) to 37.7K (June)

### 2. **Analytics Tab**
![Analytics Dashboard](https://github.com/KIRANRW9/Amazon-Sales-Insights-PowerBI/blob/repo-exercise/images/2_analytics.png)

- **Geographic Revenue Analysis**: State-wise performance with Maharashtra leading at ₹12M
- **Customer Segmentation**: LTV analysis across Premium (₹1,217), Regular (₹710), and Basic (₹326) segments
- **Product Category Performance**: Top categories including Set (₹39M), Kurta (₹21M), and Western Dress (₹11M)
- **Daily Performance Patterns**: Order status breakdown by day of the week

### 3. **Insights Tab**
![Strategic Insights](https://github.com/KIRANRW9/Amazon-Sales-Insights-PowerBI/blob/repo-exercise/images/3_insights.png)

Strategic recommendations and actionable insights including:
- Revenue concentration risk analysis
- Geographic expansion opportunities
- Operational excellence improvements
- Customer segment optimization strategies

## 🎯 Key Business Insights

### 🚨 **Critical Findings**

1. **Revenue Concentration Risk**: 27% of revenue from Kurta category alone
2. **Geographic Concentration**: Maharashtra and Karnataka command 55% of total sales
3. **Declining Order Volume**: 22% decline from April (49K) to June (38K)
4. **Weekend Performance**: Saturday and Sunday show highest order volumes

### 📊 **Performance Metrics**

| Metric | Value | Trend |
|--------|-------|-------|
| Total Orders | 129K | ↗ +41.1% |
| Total Revenue | ₹78.49M | ↗ +42.4% |
| Average Order Value | ₹609.38 | ↗ +10.8% |
| Order Success Rate | 62.75% | - |
| Cancellation Rate | 14.22% | ⚠️ Needs attention |

## 🗺️ Geographic Performance

| State | Revenue | Market Share |
|-------|---------|--------------|
| Maharashtra (MH) | ₹12M | 15.3% |
| Karnataka (KA) | ₹10M | 12.7% |
| Tamil Nadu (TN) | ₹6M | 7.6% |
| Uttar Pradesh (UP) | ₹6M | 7.6% |
| Telangana (TS) | ₹6M | 7.6% |

## 👥 Customer Segmentation Analysis

### Customer Lifetime Value (LTV)
- **Premium Customers**: ₹1,217 LTV
- **Regular Customers**: ₹710 LTV  
- **Basic Customers**: ₹326 LTV

**Key Opportunity**: 3.7x LTV difference between Premium and Basic customers indicates significant upgrade potential.

## 📅 Recommended Action Plan

### 🚨 **Immediate Priority (30 days)**
- [ ] Investigate June order decline root causes
- [ ] Reduce Thursday cancellation rates
- [ ] Launch Premium customer upgrade campaigns
- [ ] Optimize inventory management

### 📊 **Short-term Actions (Quarter)**
- [ ] Diversify product mix to reduce Kurta dependency
- [ ] Expand operations in Karnataka & Telangana
- [ ] Implement weekend-focused marketing campaigns
- [ ] Develop targeted customer segmentation strategies

### 🗺️ **Geographic Expansion Strategy**
- [ ] Analyze successful Maharashtra strategies
- [ ] Replicate winning approaches in Karnataka and Telangana
- [ ] Localize product offerings for regional preferences

## 🛠️ Technical Requirements

### Power BI Requirements
- **Power BI Desktop**: Version 2.0 or higher
- **Data Sources**: CSV files, database connections
- **Refresh Schedule**: Daily/Weekly as per business needs

### Data Sources
- Order transaction data
- Customer demographic data  
- Product catalog information
- Geographic mapping data

## 📁 File Descriptions

- **`Amazon_Sales_Dashboard.pbix`**: Main Power BI dashboard file
- **`Amazon_Sales_Dashboard.pdf`**: Static PDF version for sharing
- **`sample_data.csv`**: Anonymized sample dataset
- **`data_dictionary.md`**: Data field definitions and descriptions

## 🔧 Setup Instructions

1. **Download Power BI Desktop** from Microsoft's official website
2. **Open the .pbix file** in Power BI Desktop
3. **Refresh data sources** if connecting to live data
4. **Configure filters** for your desired date range
5. **Publish to Power BI Service** for team collaboration

## 📊 Dashboard Navigation

### Filter Controls
- **Date Range Slider**: Select custom time periods
- **State Filter**: Focus on specific geographic regions
- **Category Filter**: Analyze specific product categories
- **Customer Segment**: Filter by Premium/Regular/Basic customers

### Interactive Features
- Click on charts to cross-filter other visuals
- Hover over data points for detailed tooltips
- Use drill-down capabilities in geographic and time-based charts

## 🎨 Visualization Types Used

- **Line Charts**: Monthly trends and time-series analysis
- **Bar Charts**: Category and state-wise comparisons
- **Pie Charts**: Order status and segment distribution
- **Cards**: Key performance indicators
- **Tables**: Daily performance summaries
- **Maps**: Geographic revenue distribution

## 🔍 Future Enhancements

- [ ] Real-time data connectivity
- [ ] Predictive analytics integration
- [ ] Mobile-optimized layouts
- [ ] Automated alert system for KPI thresholds
- [ ] Customer journey mapping
- [ ] Inventory forecasting models

## 📈 Business Impact

This dashboard enables data-driven decision making by:
- **Identifying growth opportunities** in underperforming regions
- **Optimizing inventory** based on demand patterns
- **Improving customer experience** through operational insights
- **Maximizing revenue** through strategic focus areas

## 📋 Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | Q2 2022 | Initial dashboard release |
| 1.1 | Current | Added insights tab and strategic recommendations |

---

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 About the Developer
**Kiran Rangu - Data Analyst | Business Intelligence | AI & Data Science Graduate**
* 🎓 **AI & Data Science Graduate** with strong foundation in statistical analysis and machine learning concepts
* 💡 **BI Enthusiast** skilled in Power BI, DAX, Python, SQL, and learning advanced data modeling techniques
* 🚀 **Analytical Thinker** passionate about transforming datasets into meaningful business insights
* 📊 **Dashboard Creator** focused on building clear, actionable visualizations and KPI tracking
* 🎯 **Business-Minded** professional eager to identify growth opportunities and performance improvements
* 🌟 **Quick Learner** with hands-on project experience in analytics and continuous skill development
* 🌟 **Self-Driven Innovator** with hands-on project portfolio and relentless pursuit of cutting-edge analytics skills

### Connect with Me
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kiranrangu)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/KIRANRW9)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kiranrw09@gmail.com)

---

## 📞 Contact & Support

### For Project-Related Inquiries:
- 📧 **Email**: kiranrw09@gmail.com
- 💼 **LinkedIn**: [linkedin.com/in/kiranrangu](https://www.linkedin.com/in/kiranrangu)
- 🐛 **Issues**: Please use GitHub Issues for bug reports and feature requests

### For Technical Support:
- **Dashboard Issues**: Contact the developer or your IT/BI team
- **Business Insights**: Reach out for consultation on analytics strategy
- **Data Questions**: Consult the data dictionary and documentation

---

**Note**: This dashboard is created for educational purposes using Kaggle data to demonstrate business intelligence skills. It contains sample e-commerce data and is not affiliated with Amazon Inc. Please ensure proper attribution when referencing this educational project.

## 🏷️ Tags

`PowerBI` `Sales-Analytics` `Dashboard` `Business-Intelligence` `E-commerce` `Educational-Project` `Kaggle-Dataset` `Data-Visualization` `KPI-Tracking` `Portfolio` `Kiran-Rangu`

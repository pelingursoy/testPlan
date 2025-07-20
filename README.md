 Amazon E-Commerce Test Plan

 Overview
This project documents a robust testing strategy for Amazon's e-commerce platform, focusing on both manual and automation testing methods to ensure seamless user experiences at scale. With millions of global users, the platform demands rigorous testing across functionality, performance, security, and usability.

Features
- Automated test scripts using Selenium with hybrid frameworks: POM, DDT, and KDT
- Regression testing through pytest integration
- Performance evaluation using JMeter or Locust
- Security testing with Burp Suite, OWASP ZAP, and SonarQube
- PostgreSQL database verification and backup integrity checks
- Responsive UI verification for cross-browser/device compatibility

Tech Stack
- **Programming Languages:** Python (pytest), Java (optional)
- **Automation Libraries:** Selenium, Apache POI
- **Performance Tools:** JMeter, Locust
- **Security Tools:** Burp Suite, OWASP ZAP, SonarQube
- **Database:** PostgreSQL
- **CI/CD:** GitHub Actions, GitLab CI/CD
- **Bug Tracking:** Jira

📁 Folder Structure
```
📂 amazon-test-plan/
├── tests/
│   ├── functional/
│   ├── regression/
│   └── security/
├── data/
│   ├── test_data.xlsx
│   └── config.json
├── reports/
│   └── test_summary.html
├── scripts/
│   └── setup_env.py
├── docs/
│   └── TestPlan.md
├── README.md
└── requirements.txt
```

 Test Strategy
- **Framework Type:** Hybrid Selenium using Page Object Model (POM), Data-Driven Testing (DDT), Keyword-Driven Testing (KDT)
- **Data Management:** Externalized using Excel (Apache POI) or JSON
- **Environment Setup:** Dockerized containers simulating staging, QA, and production
- **Defect Lifecycle:** Integrated with Jira for traceability and sprint planning
- **Metrics Tracked:** Test case pass rate, defect severity, coverage percentage, page load time, time to resolution


Project Goals

- Deliver flawless UX across devices and regions
- Ensure robust performance under heavy load
- Catch and mitigate vulnerabilities via proactive security testing
- Achieve over 95% automation coverage in regression suites
- Maintain clear documentation and traceable execution records

How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/pelingursoy/amazon-test-plan.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute tests:
   ```bash
   pytest tests/
   ```
4. View test summary in `/reports/` directory
5. Track bugs and fixes in integrated Jira dashboard

Contributors
- **Test Architect & Author:** Pelin
- **Framework Support:** Selenium, pytest, PostgreSQL
- **Security Review:** ZAP, SonarQube Integration
- **Documentation & Branding:** README, TestPlan.md

License
MIT License – Free to use with attribution.

 Contact
Have questions or want to collaborate? Feel free to connect via https://linkedin.com/i/pelincodes or send an email to pelincodes@gmail.com

```

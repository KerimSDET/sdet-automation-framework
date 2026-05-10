# sdet-automation-framework

1. Problem:

“This project simulates a real-world scalable QA system used in fast-paced product teams.”

2. Architecture:
POM
API layer
CI integration

3. Tech stack:

Java, Selenium, TestNG, REST, Maven

4. Features:
parallel execution
reporting
retry logic
CI pipeline ready


sdet-automation-framework/
│
├── src/test/java/
│   ├── base/
│   ├── pages/
│   ├── tests/
│   ├── api/
│   ├── utils/
│   └── config/
│
├── src/test/resources/
│   ├── config.properties
│   └── testng.xml
│
├── .github/workflows/
│   └── ci.yml
│
├── reports/
├── pom.xml
└── README.md

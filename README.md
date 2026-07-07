# 🚀 API Performance Testing Using JMeter

Apache JMeter Performance Testing | REST API Validation | JMeter Dashboard Analysis | Software Quality Assurance

## 📖 Project Overview

This project demonstrates end-to-end API Performance Testing using **Apache JMeter**. The main objective of this project is to evaluate API responsiveness, stability, reliability, and overall performance behavior during execution.

The test plan includes multiple REST API requests, response validation, dynamic data handling, and performance result analysis using the **JMeter HTML Dashboard Report**.

This project reflects practical Software Quality Assurance activities such as API verification, performance measurement, response assertion, result analysis, and reporting.

---

## 🎯 Testing Objectives

The objectives of this performance testing project are:

* Verify API functionality during execution
* Measure API response times
* Evaluate request success and failure rates
* Analyze API responsiveness
* Validate request and response behavior
* Generate JMeter HTML Dashboard Report
* Understand performance metrics and reporting
* Gain practical experience in API Performance Testing using Apache JMeter

---

## 🌐 Application Under Test

| Item                     | Details                         |
| ------------------------ | ------------------------------- |
| Application Name         | API Performance Testing Project |
| Application Type         | REST API                        |
| Testing Type             | API Performance Testing         |
| Protocol                 | HTTP / HTTPS                    |
| Performance Testing Tool | Apache JMeter                   |
| Result Analysis          | JMeter HTML Dashboard           |
| Version Control          | Git                             |
| Repository Hosting       | GitHub                          |

---

## 🛠️ Technology Stack

| Category                 | Technology              |
| ------------------------ | ----------------------- |
| Performance Testing Tool | Apache JMeter           |
| API Type                 | REST API                |
| Test Script Format       | JMX                     |
| Result File Format       | JTL                     |
| Reporting Engine         | JMeter HTML Dashboard   |
| Runtime Environment      | Java                    |
| Operating System         | macOS / Windows / Linux |
| Version Control          | Git                     |
| Repository Hosting       | GitHub                  |

---

## 📋 Test Scenarios Covered

The following API performance testing scenarios were covered during execution:

| Scenario              | HTTP Method                       | Purpose                            |
| --------------------- | --------------------------------- | ---------------------------------- |
| API Request Execution | GET / POST / PUT / PATCH / DELETE | Execute REST API requests          |
| Response Validation   | Assertions                        | Validate expected API responses    |
| Header Configuration  | Header Manager                    | Configure required request headers |
| Dynamic Data Handling | Extractor                         | Capture and reuse runtime values   |
| Result Monitoring     | Listener                          | Observe request and response data  |
| Dashboard Reporting   | HTML Report                       | Analyze performance metrics        |

---

## 🔄 End-to-End Test Workflow

```text
Start Test Execution
        │
        ▼
Send API Request
        │
        ▼
Validate Response
        │
        ▼
Extract Required Data
        │
        ▼
Execute Next API Request
        │
        ▼
Collect Test Result
        │
        ▼
Generate Dashboard Report
```

This workflow helps validate API behavior and measure performance throughout the execution cycle.

---

## ⚙️ JMeter Components Used

### Thread Group

Used for configuring:

* Number of Virtual Users
* Ramp-Up Time
* Loop Count
* Test Execution Flow

### HTTP Request Sampler

Used to send API requests to the target endpoints.

Supported methods may include:

* GET
* POST
* PUT
* PATCH
* DELETE

### HTTP Header Manager

Used to configure request headers such as:

```text
Content-Type: application/json
Accept: application/json
```

### JSON Extractor

Used for dynamic data extraction and runtime parameterization.

Examples:

* Extracting ID values
* Extracting authentication tokens
* Reusing response data in later requests

### Response Assertions

Used to validate:

* Expected status codes
* Response body content
* API success criteria
* Functional correctness

### View Results Tree

Used for:

* Request inspection
* Response validation
* Debugging
* Verifying test execution results

### Summary Report / Aggregate Report

Used for analyzing:

* Average response time
* Minimum response time
* Maximum response time
* Error percentage
* Throughput

---

## 📊 Performance Test Execution Summary

### Execution Statistics

| Metric                  | Result                       |
| ----------------------- | ---------------------------- |
| Total Requests Executed | Update from JMeter Dashboard |
| Successful Requests     | Update from JMeter Dashboard |
| Failed Requests         | Update from JMeter Dashboard |
| Success Rate            | Update from JMeter Dashboard |
| Error Rate              | Update from JMeter Dashboard |

---

## ✅ Test Outcome

### Successful Execution

The API performance test was executed successfully using Apache JMeter.

### Functional Validation

Response assertions were used to verify expected API behavior.

### Performance Validation

The generated test results were analyzed using JMeter reports and dashboard metrics.

### Stability Observation

API responses were monitored during execution to identify errors, slow responses, or failed requests.

---

## ⏱️ Response Time Analysis

| Metric                | Value                        |
| --------------------- | ---------------------------- |
| Average Response Time | Update from JMeter Dashboard |
| Minimum Response Time | Update from JMeter Dashboard |
| Maximum Response Time | Update from JMeter Dashboard |
| Median Response Time  | Update from JMeter Dashboard |
| 90th Percentile       | Update from JMeter Dashboard |
| 95th Percentile       | Update from JMeter Dashboard |
| 99th Percentile       | Update from JMeter Dashboard |

### Performance Observations

* API response time was measured during execution.
* Request success and failure rates were analyzed.
* Slow-performing requests were identified from the dashboard report.
* Overall API behavior was evaluated based on response time, throughput, and error percentage.

---

## 📈 APDEX Analysis

APDEX, or Application Performance Index, is a performance metric used to measure user satisfaction based on response time.

| Metric      | Score                        |
| ----------- | ---------------------------- |
| APDEX Score | Update from JMeter Dashboard |

### APDEX Interpretation

| Score Range | User Satisfaction |
| ----------- | ----------------- |
| 0.94 – 1.00 | Excellent         |
| 0.85 – 0.93 | Good              |
| 0.70 – 0.84 | Fair              |
| Below 0.70  | Poor              |

The APDEX score helps understand how satisfactory the application performance was under the executed test conditions.

---

## 📊 Dashboard Overview

The Apache JMeter HTML Dashboard provides a visual representation of performance test results.

### Metrics Evaluated

* APDEX Analysis
* Request Summary
* Statistics Report
* Response Time Overview
* Throughput Analysis
* Error Analysis
* Percentile Response Times

### Dashboard Screenshot

Add dashboard screenshot here:

```markdown
<img width="1900" height="957" alt="Report" src="https://github.com/user-attachments/assets/b9afef6b-926e-49bb-bbad-d5e10f7db85c" />

```

---

## 📂 Repository Structure

```text
API_performance_testing/
│
├── README.md
│
├── Dashboard_Report/
│   ├── index.html
│   ├── content/
│   └── sbadmin2-1.0.7/
│
├── Screenshots/
│   ├── dashboard-overview.png
│   ├── statistics.png
│   ├── response-times.png
│   └── throughput.png
│
├── JMX_File/
│   └── API_performance_testing_Test_Plan.jmx
│
├── Test_Results/
│   └── API_performance_testing_Test_Plan.jtl
│
└── Documentation/
    └── Performance_Test_Report.pdf
```

---

## 🌍 Live Dashboard

The JMeter HTML Dashboard can be hosted using GitHub Pages.

### View Dashboard

```text
https://nur-jahan-smrity.github.io/API_performance_testing/Dashboard_Report/
```

Replace this link with the actual GitHub Pages URL after deployment.

---

## ▶️ How to Execute the Test

### Clone Repository

```bash
git clone https://github.com/Nur-Jahan-Smrity/API_performance_testing.git
```

### Navigate to Project Directory

```bash
cd API_performance_testing
```

### Launch Apache JMeter

```bash
jmeter
```

### Open Test Plan

```text
File → Open → API_performance_testing_Test_Plan.jmx
```

### Run Test from JMeter GUI

```text
Run → Start
```

---

## 🧪 Run Test from Command Line

```bash
jmeter -n -t API_performance_testing_Test_Plan.jmx -l API_performance_testing_Test_Plan.jtl
```

---

## 📊 Generate HTML Dashboard Report

```bash
jmeter -g API_performance_testing_Test_Plan.jtl -o Dashboard_Report
```

If running both test execution and dashboard generation together:

```bash
jmeter -n -t API_performance_testing_Test_Plan.jmx -l API_performance_testing_Test_Plan.jtl -e -o Dashboard_Report
```

---

## 🔍 Key Findings

### Positive Outcomes

* API requests executed successfully
* Response assertions helped validate expected output
* JMeter dashboard provided clear performance insights
* Test result file was generated in JTL format
* HTML dashboard report was generated successfully
* Response time, throughput, and error rate were analyzed
* The project demonstrates practical API performance testing workflow

---

## 💡 Software Quality Assurance Perspective

From an SQA perspective, this project demonstrates:

### Requirement Validation

Ensuring API endpoints behave according to expected requirements.

### Functional Verification

Validating API responses, status codes, and expected output.

### Performance Evaluation

Measuring application responsiveness and request processing time.

### Quality Assurance Reporting

Presenting performance metrics using dashboard reports and result analysis.

### Risk Identification

Identifying slow requests, failures, or potential performance bottlenecks.

### Continuous Quality Monitoring

Creating reusable performance test scripts for future comparison and improvement.

---

## 📚 Learning Outcomes

This project enhanced practical knowledge in:

* Apache JMeter
* API Performance Testing
* REST API Validation
* HTTP Request Testing
* Header Configuration
* JSON Extraction
* Response Assertions
* JTL Result Analysis
* HTML Dashboard Reporting
* Performance Metrics Interpretation
* Software Quality Assurance Practices
* Test Planning and Execution
* Performance Analysis and Reporting

---

## 🚀 Future Enhancements

Planned improvements include:

* Load Testing with Multiple Users
* Stress Testing
* Spike Testing
* Endurance Testing
* Scalability Testing
* Distributed Load Testing
* Jenkins CI/CD Integration
* Automated Performance Regression Testing
* Performance Baseline Comparison
* Real-Time Monitoring Integration

---

## 👩‍💻 Author

**Nur Jahan Smrity**

Software Quality Assurance Learner | API Performance Testing | Apache JMeter | GitHub Project Practice

### Connect With Me

GitHub:
https://github.com/Nur-Jahan-Smrity

---

## ⭐ Support

If you found this project useful, consider giving the repository a Star ⭐.

Your support encourages continuous learning, knowledge sharing, and future contributions in Software Quality Assurance and Performance Engineering.

---

## 🙏 Thank You

Thank you for visiting this project.

**Performance Testing • Quality Engineering • Continuous Improvement**

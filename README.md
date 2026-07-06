# API Performance Testing Using Apache JMeter

## Overview

This repository contains API performance testing scripts created using Apache JMeter. The project is designed to evaluate API performance under different load conditions and measure key performance metrics such as response time, throughput, error rate, and system stability.

Apache JMeter is an open-source load testing tool commonly used to analyze and measure the performance of web applications, APIs, and services. :contentReference[oaicite:0]{index=0}

---

## Objectives

- Validate API performance under load
- Measure response times and throughput
- Identify performance bottlenecks
- Verify application stability during concurrent requests
- Generate detailed performance reports

---

## Tools & Technologies

| Tool | Purpose |
|--------|----------|
| Apache JMeter 5.6.3 | Performance Testing |
| Java JDK 11+ | Runtime Environment |
| macOS | Test Environment |
| HTML Dashboard | Report Generation |

---

## Project Structure

```text
API_performance_testing/
│
├── API_performance_testing_Test_Plan.jmx
├── results.jtl
├── report/
│   └── index.html
└── README.md
```

### File Description

| File | Description |
|--------|-------------|
| API_performance_testing_Test_Plan.jmx | JMeter Test Plan |
| results.jtl | Test execution results |
| report/ | Generated HTML performance reports |
| README.md | Project documentation |

---

## Prerequisites

Install the following before running the tests:

### Java

Verify Java installation:

```bash
java -version
```

### Apache JMeter

Verify JMeter installation:

```bash
jmeter -v
```

Download Apache JMeter:

:contentReference[oaicite:1]{index=1}

---

## Running Tests

### GUI Mode (For Script Development)

Start JMeter GUI:

```bash
jmeter
```

Open:

```text
API_performance_testing_Test_Plan.jmx
```

> GUI mode should only be used for creating and debugging test plans.

---

### Non-GUI Mode (Recommended)

Navigate to the project folder:

```bash
cd API_performance_testing
```

Execute the test:

```bash
jmeter -n \
-t API_performance_testing_Test_Plan.jmx \
-l results.jtl
```

### Parameters

| Parameter | Description |
|------------|------------|
| -n | Run in Non-GUI mode |
| -t | Test plan file |
| -l | Result log file |

---

## Generate HTML Report

Generate report:

```bash
jmeter -g results.jtl -o report
```

Open report:

### macOS

```bash
open report/index.html
```

### Windows

```bash
start report/index.html
```

---

## Metrics Evaluated

The performance report includes:

- Average Response Time
- Median Response Time
- 90th Percentile Response Time
- Throughput
- Error Percentage
- Requests Per Second
- Active Threads
- Response Time Distribution

---

## Sample Workflow

### Execute Test

```bash
jmeter -n \
-t API_performance_testing_Test_Plan.jmx \
-l results.jtl
```

### Generate Dashboard

```bash
jmeter -g results.jtl -o report
```

### View Dashboard

```bash
open report/index.html
```

---

## Best Practices

- Use Non-GUI mode for performance testing.
- Keep GUI mode for script creation and debugging only.
- Increase JVM heap size when running large-scale tests.
- Run tests in a stable environment.
- Monitor CPU and memory usage during execution.
- Store historical reports for comparison and trend analysis.

---

## Performance Testing Concepts

Performance testing focuses on evaluating:

- **Speed** – How quickly the API responds.
- **Scalability** – How the API behaves as user load increases.
- **Stability** – Whether the API remains reliable under sustained load.

Performance testing helps identify system limitations before production deployment. :contentReference[oaicite:2]{index=2}

---

## Author

**Nur Jahan Smrity**

QA Engineer | API Testing | Performance Testing

GitHub Repository:

:contentReference[oaicite:3]{index=3}

---

## License

This project is created for learning and practice purposes.

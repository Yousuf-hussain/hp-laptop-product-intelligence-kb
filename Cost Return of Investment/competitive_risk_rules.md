# Competitive Risk Assessment Framework

## Purpose

This document provides standardized competitive risk analysis rules used to determine the likelihood of HP losing business, customer satisfaction, adoption, or future opportunities to competitors.

The framework helps answer:

* What competitor products can fulfill the requirement?
* How strong is HP's position?
* What competitive gaps exist?
* What is the risk of customer choosing a competitor?
* What is the business impact if HP cannot fulfill the requirement?
* What strategic actions should HP take?

This framework is used by the Cost, Business Value, and ROI Analysis Agent to generate a Competitive Risk Score and Competitive Threat Assessment.

---

# Competitor Categories

## Primary Competitors

### Dell

Products:

* Dell Latitude
* Dell Precision

Primary Strengths:

* Enterprise presence
* Business productivity
* Workstation offerings
* AI-ready workstation portfolio

---

### Lenovo

Products:

* Lenovo ThinkPad
* Lenovo ThinkPad X1 Carbon
* Lenovo ThinkPad P Series

Primary Strengths:

* Enterprise adoption
* Business reliability
* Mobility
* Security

---

### Microsoft

Products:

* Surface Laptop
* Surface Pro

Primary Strengths:

* Premium experience
* Mobility
* Productivity integration

---

# Competitive Risk Formula

Competitive Risk Score =

Feature Gap Risk
+
Performance Gap Risk
+
Price Gap Risk
+
Availability Gap Risk
+
Innovation Gap Risk
+
Customer Preference Risk

Maximum Score = 100

---

# Dell Threat Rules

## Dell Latitude Threat Assessment

### Direct Competitor

HP Products:

* EliteBook
* ProBook

---

### Threat Areas

| Area                  | Threat Level |
| --------------------- | ------------ |
| Business Productivity | Medium       |
| Security              | Medium       |
| Mobility              | Medium       |
| Enterprise Adoption   | Medium       |
| AI Capability         | Low          |

---

### Threat Score Rules

If Dell Latitude offers requested feature and HP equivalent does not:

Add:

10 Points

---

### Example

Requirement:

* 14 Hour Battery
* Enterprise Security

HP Match:

Partial

Dell Match:

Full

Threat Level:

Medium

Threat Score:

15

---

# Dell Precision Threat Rules

## Direct Competitor

HP Products:

* ZBook

---

### Threat Areas

| Area                     | Threat Level |
| ------------------------ | ------------ |
| AI Workloads             | High         |
| Machine Learning         | High         |
| Data Science             | High         |
| Engineering Applications | High         |
| GPU Capability           | High         |

---

### Threat Score Rules

If AI GPU is requested and HP does not have equivalent configuration available:

Add:

25 Points

---

### Example

Requirement:

* AI GPU
* Machine Learning
* Deep Learning

HP Availability:

Not Available

Dell Precision:

Available

Threat Level:

High

Threat Score:

25

---

# Lenovo ThinkPad Threat Rules

## Direct Competitor

HP Products:

* EliteBook
* ProBook

---

### Threat Areas

| Area                | Threat Level |
| ------------------- | ------------ |
| Reliability         | High         |
| Enterprise Adoption | High         |
| Keyboard Experience | Medium       |
| Security            | Medium       |
| Mobility            | Medium       |

---

### Threat Score Rules

If customer prioritizes reliability and enterprise stability:

Add:

15 Points

---

### Example

Requirement:

* Enterprise Operations
* Long Lifecycle
* Stability

Threat Level:

Medium

Threat Score:

15

---

# Lenovo X1 Carbon Threat Rules

## Direct Competitor

HP Products:

* Spectre
* EliteBook

---

### Threat Areas

| Area                    | Threat Level |
| ----------------------- | ------------ |
| Executive Mobility      | High         |
| Premium Design          | High         |
| Lightweight Form Factor | High         |
| Battery Life            | Medium       |

---

### Threat Score Rules

If requirement emphasizes:

* Lightweight
* Executive Use
* Mobility

Add:

15 Points

---

### Example

Requirement:

* Lightweight
* Executive Travel
* Premium Experience

Threat Level:

Medium

Threat Score:

15

---

# Microsoft Surface Threat Rules

## Direct Competitor

HP Products:

* Spectre
* EliteBook

---

### Threat Areas

| Area               | Threat Level |
| ------------------ | ------------ |
| User Experience    | Medium       |
| Mobility           | Medium       |
| Touch Interface    | High         |
| Premium Experience | Medium       |

---

### Threat Score Rules

If customer specifically requests:

* Touchscreen
* Tablet Mode
* Hybrid Device

Add:

10 Points

---

# Feature Gap Risk

## Purpose

Measures whether competitors provide requested features unavailable in HP offerings.

---

### Scoring

| Condition    | Score |
| ------------ | ----: |
| No Gap       |     0 |
| Minor Gap    |    10 |
| Moderate Gap |    20 |
| Major Gap    |    30 |

---

### Examples

Minor Gap:

* Missing accessory

Moderate Gap:

* Missing battery option

Major Gap:

* Missing AI GPU capability

---

# Performance Gap Risk

## Purpose

Measures performance differences.

---

### Scoring

| Condition                    | Score |
| ---------------------------- | ----: |
| Comparable Performance       |     0 |
| Slightly Lower Performance   |    10 |
| Noticeably Lower Performance |    20 |
| Significant Performance Gap  |    30 |

---

# Price Gap Risk

## Purpose

Measures cost competitiveness.

---

### Scoring

| Difference               | Score |
| ------------------------ | ----: |
| HP Cheaper               |     0 |
| Similar Pricing          |     5 |
| HP More Expensive (<10%) |    10 |
| HP More Expensive (>20%) |    20 |

---

# Availability Gap Risk

## Purpose

Measures inventory and procurement advantage of competitors.

---

### Scoring

| Condition               | Score |
| ----------------------- | ----: |
| HP Inventory Available  |     0 |
| Minor Procurement Delay |    10 |
| Significant Delay       |    20 |
| Product Unavailable     |    30 |

---

# Innovation Gap Risk

## Purpose

Measures future-readiness differences.

---

### Areas

* AI readiness
* NPU support
* Advanced GPU support
* Future scalability
* Enterprise innovation

---

### Scoring

| Condition        | Score |
| ---------------- | ----: |
| Equal Innovation |     0 |
| Slight Gap       |    10 |
| Moderate Gap     |    20 |
| Major Gap        |    30 |

---

# Market Loss Risk Rules

## Purpose

Estimate probability of customer selecting a competitor.

---

### Low Risk

Probability:

0-20%

Score:

10

Business Impact:

Minimal

---

### Medium Risk

Probability:

21-50%

Score:

25

Business Impact:

Moderate

---

### High Risk

Probability:

51-80%

Score:

50

Business Impact:

Significant

---

### Critical Risk

Probability:

81-100%

Score:

75

Business Impact:

Severe

---

# Competitive Risk Classification

| Score    | Classification |
| -------- | -------------- |
| 0 - 20   | Low            |
| 21 - 40  | Medium         |
| 41 - 60  | High           |
| 61 - 100 | Critical       |

---

# Competitive Response Recommendations

## Low Risk

Action:

Monitor

---

## Medium Risk

Action:

Review HP alternatives

---

## High Risk

Action:

Prioritize fulfillment

Escalate to Product Team

---

## Critical Risk

Action:

Immediate business review

Executive visibility required

Customer retention strategy required

---

# Example Competitive Assessment

Requirement:

* AI GPU
* 32GB RAM
* Machine Learning
* 1TB SSD

HP Match:

Partial

Competitor Match:

Dell Precision

Analysis:

| Area             | Risk   |
| ---------------- | ------ |
| Feature Gap      | High   |
| Performance Gap  | Medium |
| Availability Gap | Medium |
| Innovation Gap   | High   |

Competitive Risk Score:

72/100

Classification:

Critical

Risk of Customer Moving to Dell:

High

Recommendation:

Prioritize fulfillment and validate HP ZBook AI configuration immediately.

---

# Agent Usage Rules

The Cost & ROI Analysis Agent must:

1. Compare requirement against HP products.
2. Compare requirement against competitor products.
3. Identify feature gaps.
4. Calculate Competitive Risk Score.
5. Determine customer migration risk.
6. Generate competitor threat analysis.
7. Include competitive risk in executive dashboard.
8. Recommend mitigation actions.

---

# Executive Dashboard Output

| Metric                    | Value                          |
| ------------------------- | ------------------------------ |
| Competitive Risk Score    | XX/100                         |
| Classification            | Low / Medium / High / Critical |
| Primary Competitor Threat | Dell / Lenovo / Microsoft      |
| Customer Migration Risk   | Low / Medium / High            |
| Recommended Action        | Monitor / Review / Prioritize  |

---

# Disclaimer

Competitive risk scores are strategic planning estimates based on available product intelligence and market assumptions.

Final competitive decisions should be validated by Product Management, Customer Success Leadership, Sales Teams, and Market Intelligence Teams.

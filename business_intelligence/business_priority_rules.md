# Business Priority Rules Knowledge Base

## Purpose

This knowledge base defines the framework used by HP Executive Leadership, Product Teams, Customer Success Teams, Finance Teams, and Operations Teams to determine how important a request is to the business.

The objective is to answer:

* How important is this requirement?
* Should HP prioritize this request?
* How urgently should this request be fulfilled?
* Does this requirement align with HP's strategic goals?
* Which department should receive priority?
* Is this requirement business-critical or optional?

This framework generates a standardized Business Priority Score used in executive decision-making.

---

# Business Priority Framework

Business Priority Score is calculated using weighted business factors.

Formula:

Business Priority Score =

Customer Impact Score

*

Strategic Importance Score

*

Revenue Impact Score

*

Innovation Impact Score

*

Department Criticality Score

*

Demand Trend Score

---

# Scoring Scale

Each factor is scored from 0 to 100.

The weighted result generates the final Business Priority Score.

Maximum Score = 100

Minimum Score = 0

---

# Priority Classification

| Business Priority Score | Classification |
| ----------------------- | -------------- |
| 85 - 100                | Critical       |
| 70 - 84                 | High           |
| 50 - 69                 | Medium         |
| 30 - 49                 | Low            |
| Below 30                | Very Low       |

---

# Weight Distribution

| Factor                 | Weight |
| ---------------------- | ------ |
| Customer Impact        | 25%    |
| Strategic Importance   | 20%    |
| Revenue Impact         | 15%    |
| Innovation Impact      | 15%    |
| Department Criticality | 15%    |
| Demand Trend           | 10%    |

Total Weight = 100%

---

# 1. Customer Impact Score

## Purpose

Measures how many users, customers, employees, or stakeholders benefit from the requirement.

---

## Customer Impact Levels

| Impact Level | Score |
| ------------ | ----- |
| Minimal      | 10    |
| Low          | 25    |
| Medium       | 50    |
| High         | 75    |
| Critical     | 100   |

---

## Examples

### Minimal

* Individual request
* Single employee impact

### Low

* Small team request
* Less than 10 users

### Medium

* Department-level request
* 10–50 users

### High

* Multiple departments
* 50–500 users

### Critical

* Enterprise-wide impact
* More than 500 users

---

# Customer Impact Weight

25%

Formula:

Customer Impact Contribution

=

Customer Impact Score × 25%

---

# 2. Strategic Importance Score

## Purpose

Measures alignment with HP's long-term strategy.

---

## Strategic Areas

High strategic alignment includes:

* Artificial Intelligence
* Machine Learning
* Digital Transformation
* Automation
* Security
* Customer Experience
* Innovation
* Enterprise Productivity

---

## Strategic Scoring

| Strategic Alignment | Score |
| ------------------- | ----- |
| None                | 0     |
| Low                 | 25    |
| Medium              | 50    |
| High                | 75    |
| Critical            | 100   |

---

## Examples

### Critical

* AI Platform Enablement
* Enterprise AI Workstations
* Security Modernization

### High

* Productivity Improvements
* Automation Programs

### Medium

* Infrastructure Improvements

### Low

* Cosmetic Improvements

---

# Strategic Importance Weight

20%

Formula:

Strategic Contribution

=

Strategic Importance Score × 20%

---

# 3. Revenue Impact Score

## Purpose

Measures direct or indirect effect on revenue generation.

---

## Revenue Impact Levels

| Impact Level | Score |
| ------------ | ----- |
| None         | 0     |
| Low          | 25    |
| Medium       | 50    |
| High         | 75    |
| Critical     | 100   |

---

## Examples

### Critical

* Direct customer-facing services
* Revenue-generating products

### High

* Sales enablement tools
* Customer success productivity

### Medium

* Internal operational tools

### Low

* Administrative requests

---

# Revenue Impact Weight

15%

Formula:

Revenue Contribution

=

Revenue Impact Score × 15%

---

# 4. Innovation Impact Score

## Purpose

Measures how much the requirement supports innovation initiatives.

---

## Innovation Categories

| Innovation Level | Score |
| ---------------- | ----- |
| None             | 0     |
| Low              | 25    |
| Medium           | 50    |
| High             | 75    |
| Transformational | 100   |

---

## Examples

### Transformational

* AI Development
* Machine Learning Platforms
* Predictive Analytics

### High

* Automation Initiatives
* Data Science Programs

### Medium

* Process Improvements

### Low

* Routine Requests

---

# Innovation Weight

15%

Formula:

Innovation Contribution

=

Innovation Impact Score × 15%

---

# 5. Department Criticality Score

## Purpose

Measures the business importance of the requesting department.

---

## Department Classification

| Department           | Score |
| -------------------- | ----- |
| Executive Leadership | 100   |
| Product Engineering  | 95    |
| AI Engineering       | 95    |
| Security Operations  | 95    |
| Customer Success     | 90    |
| Sales                | 90    |
| Product Management   | 85    |
| Operations           | 80    |
| Finance              | 80    |
| HR                   | 70    |
| Administration       | 60    |

---

## Examples

AI Engineering request:

Score = 95

Customer Success request:

Score = 90

HR request:

Score = 70

---

# Department Criticality Weight

15%

Formula:

Department Contribution

=

Department Score × 15%

---

# 6. Demand Trend Score

## Purpose

Measures recurring business demand.

---

## Demand Classification

Based on historical ticket analysis.

---

### Limited Demand

0–2 Similar Tickets

Score = 25

---

### Emerging Demand

3–5 Similar Tickets

Score = 50

---

### Established Demand

6–10 Similar Tickets

Score = 75

---

### Strategic Demand

More than 10 Similar Tickets

Score = 100

---

## Examples

Agent 1 Analysis:

2 Similar Tickets

Demand Score = 25

Classification = Limited Demand

---

# Demand Trend Weight

10%

Formula:

Demand Contribution

=

Demand Score × 10%

---

# Final Business Priority Formula

Business Priority Score =

(Customer Impact × 25%)

*

(Strategic Importance × 20%)

*

(Revenue Impact × 15%)

*

(Innovation Impact × 15%)

*

(Department Criticality × 15%)

*

(Demand Trend × 10%)

---

# Example Calculation

Requirement:

AI Engineering requests HP ZBook for AI Development.

Scores:

| Factor                 | Score |
| ---------------------- | ----- |
| Customer Impact        | 75    |
| Strategic Importance   | 100   |
| Revenue Impact         | 50    |
| Innovation Impact      | 100   |
| Department Criticality | 95    |
| Demand Trend           | 25    |

Calculation:

(75×0.25)

*

(100×0.20)

*

(50×0.15)

*

(100×0.15)

*

(95×0.15)

*

(25×0.10)

=

18.75

*

20

*

7.5

*

15

*

14.25

*

2.5

=

78

---

Final Result:

Business Priority Score = 78

Classification = HIGH

---

# Executive Priority Actions

| Priority Level | Action                    |
| -------------- | ------------------------- |
| Critical       | Immediate Approval Review |
| High           | Fast Track Review         |
| Medium         | Standard Business Review  |
| Low            | Deferred Review           |
| Very Low       | Consider Rejection        |

---

# Escalation Rules

| Priority Score | Escalation             |
| -------------- | ---------------------- |
| Above 85       | VP / Director Review   |
| 70-84          | Department Head Review |
| 50-69          | Manager Review         |
| Below 50       | Standard Processing    |

---

# Confidence Adjustments

Reduce confidence by 5% if:

* Customer impact unknown
* Strategic alignment unclear
* Revenue impact estimated
* Demand trend unavailable
* Department not identified

Maximum Confidence = 100%

Minimum Confidence = 50%

---

# Agent Output Requirements

Every Business Priority Assessment must generate:

* Customer Impact Score
* Strategic Importance Score
* Revenue Impact Score
* Innovation Impact Score
* Department Criticality Score
* Demand Trend Score
* Business Priority Score
* Priority Classification
* Escalation Requirement
* Executive Action Recommendation
* Key Drivers
* Confidence Score
* Executive Summary

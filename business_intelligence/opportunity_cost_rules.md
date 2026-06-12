# Opportunity Cost Rules Knowledge Base

## Purpose

This knowledge base defines the methodology for calculating the business impact, financial loss, operational loss, strategic loss, customer impact, and competitive disadvantage that may occur if HP decides NOT to fulfill a customer, employee, engineering, or business requirement.

The objective is to help HP leadership understand:

* What is the cost of delaying a decision?
* What is the cost of rejecting a request?
* What is the cost of doing nothing?
* Is the opportunity cost higher than the investment cost?
* What business value may be lost if the requirement is not fulfilled?

This analysis is used during executive reviews, investment approvals, business prioritization, and portfolio planning.

---

# Opportunity Cost Definition

Opportunity Cost is the estimated business value lost because HP chooses not to invest in, fulfill, or prioritize a requirement.

Formula:

Opportunity Cost =

Productivity Loss

*

Employee Efficiency Loss

*

Customer Satisfaction Loss

*

Competitive Loss

*

Strategic Delay Cost

*

Innovation Delay Cost

*

Revenue Opportunity Loss

---

# 1. Productivity Loss Rules

## Definition

Loss of employee output due to insufficient tools, delayed technology adoption, poor performance, or inability to complete work efficiently.

## Examples

* Developer waiting for slower laptop
* AI engineer unable to train models efficiently
* Analyst waiting for report generation
* Teams losing time due to performance limitations

## Formula

Productivity Loss =

Hours Lost Per Month

×

Hourly Employee Cost

×

Number of Affected Employees

×

12

---

## Example

Hours Lost Per Month = 10

Hourly Cost = $40

Affected Employees = 25

Productivity Loss

= 10 × 40 × 25 × 12

= $120,000

---

## Classification

| Annual Productivity Loss | Classification |
| ------------------------ | -------------- |
| Less than $25,000        | Low            |
| $25,000 - $100,000       | Medium         |
| $100,000 - $500,000      | High           |
| Above $500,000           | Critical       |

---

# 2. Employee Efficiency Loss Rules

## Definition

Loss caused by inefficient workflows, delays, excessive manual effort, or inability to use modern tools.

## Examples

* AI engineers unable to run workloads
* Developers waiting for hardware resources
* Analysts using outdated systems
* Operations teams spending excessive manual effort

## Formula

Employee Efficiency Loss =

Productivity Reduction %

×

Annual Employee Cost

×

Affected Employees

---

## Classification

| Efficiency Reduction | Severity |
| -------------------- | -------- |
| Less than 5%         | Low      |
| 5% - 10%             | Medium   |
| 10% - 20%            | High     |
| Above 20%            | Critical |

---

# 3. Customer Satisfaction Loss Rules

## Definition

Business impact resulting from lower satisfaction, poor employee experience, slower service delivery, or unmet expectations.

## Examples

* Delayed support
* Slower delivery timelines
* Frustrated internal teams
* Reduced user experience

## Satisfaction Impact Values

| Impact Level | Cost Value |
| ------------ | ---------- |
| Low          | $10,000    |
| Medium       | $50,000    |
| High         | $150,000   |
| Critical     | $500,000   |

---

## Classification

| Satisfaction Score Reduction | Severity |
| ---------------------------- | -------- |
| 1% - 5%                      | Low      |
| 5% - 10%                     | Medium   |
| 10% - 20%                    | High     |
| Above 20%                    | Critical |

---

# 4. Competitive Delay Cost Rules

## Definition

Loss caused when competitors can provide capabilities faster than HP.

## Examples

* Competitor offers AI-ready workstations
* Competitor supports advanced ML workloads
* Competitor improves employee experience faster
* HP loses strategic advantage

## Competitive Impact Values

| Competitive Impact | Annual Loss |
| ------------------ | ----------- |
| Low                | $25,000     |
| Medium             | $100,000    |
| High               | $300,000    |
| Critical           | $1,000,000  |

---

## Competitive Risk Classification

| Risk Score | Classification |
| ---------- | -------------- |
| 0-25       | Low            |
| 26-50      | Medium         |
| 51-75      | High           |
| 76-100     | Critical       |

---

# 5. Strategic Delay Cost Rules

## Definition

Cost incurred when business initiatives, transformation programs, AI adoption, innovation programs, or operational improvements are delayed.

## Examples

* AI program delayed
* Product launch delayed
* Transformation initiative delayed
* Operational modernization delayed

## Strategic Delay Values

| Delay Duration    | Cost Impact |
| ----------------- | ----------- |
| Less than 1 Month | $10,000     |
| 1-3 Months        | $50,000     |
| 3-6 Months        | $150,000    |
| Above 6 Months    | $500,000    |

---

## Strategic Importance Multiplier

| Strategic Importance | Multiplier |
| -------------------- | ---------- |
| Low                  | 1.0        |
| Medium               | 1.5        |
| High                 | 2.0        |
| Critical             | 3.0        |

Final Strategic Delay Cost

=

Delay Cost

×

Strategic Multiplier

---

# 6. Innovation Delay Cost Rules

## Definition

Business value lost when innovation initiatives cannot proceed.

## Examples

* AI development delayed
* Machine learning projects delayed
* Product innovation delayed
* Automation programs delayed

## Innovation Cost Values

| Innovation Impact | Value    |
| ----------------- | -------- |
| Low               | $20,000  |
| Medium            | $75,000  |
| High              | $200,000 |
| Strategic         | $500,000 |

---

## Innovation Classification

| Innovation Impact | Severity  |
| ----------------- | --------- |
| Minor             | Low       |
| Moderate          | Medium    |
| Significant       | High      |
| Transformational  | Strategic |

---

# 7. Revenue Opportunity Loss Rules

## Definition

Potential revenue not realized due to inability to execute business initiatives.

## Examples

* Lost contracts
* Delayed product releases
* Reduced service capability
* Lower productivity affecting delivery

## Revenue Impact Values

| Revenue Impact | Annual Value |
| -------------- | ------------ |
| Low            | $25,000      |
| Medium         | $100,000     |
| High           | $500,000     |
| Strategic      | $2,000,000   |

---

# Total Opportunity Cost Formula

Total Opportunity Cost

=

Productivity Loss

*

Employee Efficiency Loss

*

Customer Satisfaction Loss

*

Competitive Delay Cost

*

Strategic Delay Cost

*

Innovation Delay Cost

*

Revenue Opportunity Loss

---

# Investment vs Opportunity Cost Rules

## Rule 1

If

Opportunity Cost > Investment Cost

Recommendation:

APPROVE

Reason:

Cost of inaction exceeds cost of investment.

---

## Rule 2

If

Opportunity Cost = Investment Cost

Recommendation:

APPROVE WITH REVIEW

Reason:

Financial impact is balanced.

---

## Rule 3

If

Opportunity Cost < Investment Cost

Recommendation:

BUSINESS REVIEW REQUIRED

Reason:

Investment may not be justified.

---

# Opportunity Cost Classification

| Opportunity Cost Value | Classification |
| ---------------------- | -------------- |
| Less than $50,000      | Low            |
| $50,000 - $250,000     | Medium         |
| $250,000 - $1,000,000  | High           |
| Above $1,000,000       | Strategic      |

---

# Executive Decision Guidelines

| Opportunity Cost Level | Recommended Action               |
| ---------------------- | -------------------------------- |
| Low                    | Review                           |
| Medium                 | Review / Conditional Approval    |
| High                   | Approve                          |
| Strategic              | Immediate Approval Consideration |

---

# HP AI Laptop Example

Requirement:

AI Engineering requests HP ZBook with AI GPU.

Investment Cost:

$5,000

Opportunity Cost Calculation:

| Area                       | Cost    |
| -------------------------- | ------- |
| Productivity Loss          | $12,000 |
| Efficiency Loss            | $8,000  |
| Customer Satisfaction Loss | $5,000  |
| Strategic Delay Cost       | $10,000 |
| Innovation Delay Cost      | $15,000 |
| Competitive Loss           | $8,000  |
| Total Opportunity Cost     | $58,000 |

Analysis:

Investment Cost = $5,000

Opportunity Cost = $58,000

Decision:

APPROVE

Reason:

Cost of inaction is more than 11x the investment cost.

---

# Confidence Adjustment Rules

Reduce confidence by 5% if:

* User count is unknown
* Revenue impact is estimated
* Strategic impact is estimated
* Innovation impact is estimated
* Competitor impact is estimated

Maximum Confidence = 100%

Minimum Confidence = 50%

---

# Agent Output Requirements

Every Opportunity Cost Assessment must generate:

* Productivity Loss
* Employee Efficiency Loss
* Customer Satisfaction Loss
* Competitive Loss
* Strategic Delay Cost
* Innovation Delay Cost
* Revenue Opportunity Loss
* Total Opportunity Cost
* Opportunity Cost Classification
* Investment vs Opportunity Cost Comparison
* Recommendation Impact
* Key Assumptions
* Executive Summary

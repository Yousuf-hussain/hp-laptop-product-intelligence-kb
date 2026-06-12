# Competitive Risk Rules Knowledge Base

## Purpose

This knowledge base defines the methodology used by HP Leadership, Product Teams, Customer Success Teams, Strategy Teams, and Executive Decision Agents to evaluate competitive threats and market risks associated with fulfilling or not fulfilling a business requirement.

The objective is to answer:

* Will competitors gain an advantage if HP does not fulfill this requirement?
* Does this requirement address an existing feature gap?
* Is there an innovation risk?
* Could HP lose customers, employees, or market position?
* How severe is the competitive threat?
* Should leadership accelerate investment?

This framework generates a Competitive Risk Score used during executive decision-making and portfolio prioritization.

---

# Competitive Risk Framework

Competitive Risk Score is calculated using weighted competitive factors.

Formula:

Competitive Risk Score =

Feature Gap Risk

*

Innovation Gap Risk

*

Market Position Risk

*

Competitor Threat Risk

*

Migration Risk

*

Talent Retention Risk

---

# Scoring Scale

Each factor is scored from 0 to 100.

Maximum Score = 100

Minimum Score = 0

---

# Competitive Risk Classification

| Score    | Classification |
| -------- | -------------- |
| 85 - 100 | Critical Risk  |
| 70 - 84  | High Risk      |
| 50 - 69  | Medium Risk    |
| 30 - 49  | Low Risk       |
| Below 30 | Minimal Risk   |

---

# Weight Distribution

| Factor                 | Weight |
| ---------------------- | ------ |
| Feature Gap Risk       | 25%    |
| Innovation Gap Risk    | 20%    |
| Market Position Risk   | 20%    |
| Competitor Threat Risk | 15%    |
| Migration Risk         | 10%    |
| Talent Retention Risk  | 10%    |

Total Weight = 100%

---

# 1. Feature Gap Risk

## Purpose

Measures risk caused by missing functionality or capabilities that competitors already offer.

---

## Examples

* Competitor offers AI-ready laptops
* Competitor offers longer battery life
* Competitor provides better security features
* Competitor offers better GPU performance

---

## Feature Gap Scoring

| Gap Severity    | Score |
| --------------- | ----- |
| No Gap          | 0     |
| Minor Gap       | 25    |
| Moderate Gap    | 50    |
| Significant Gap | 75    |
| Critical Gap    | 100   |

---

## Examples

### Minor Gap

Small performance difference

### Moderate Gap

Some missing capabilities

### Significant Gap

Important business features missing

### Critical Gap

Competitor significantly ahead

---

## Weight

25%

Formula:

Feature Gap Contribution

=

Feature Gap Score × 25%

---

# 2. Innovation Gap Risk

## Purpose

Measures risk associated with lagging behind competitors in innovation and emerging technologies.

---

## Examples

* AI adoption delayed
* Machine learning capability missing
* Lack of automation
* Limited data science support

---

## Innovation Gap Scoring

| Innovation Gap | Score |
| -------------- | ----- |
| None           | 0     |
| Low            | 25    |
| Medium         | 50    |
| High           | 75    |
| Critical       | 100   |

---

## Examples

### Low

Minor innovation delay

### Medium

Competitors investing faster

### High

Innovation roadmap behind competitors

### Critical

HP unable to compete in strategic technology areas

---

## Weight

20%

Formula:

Innovation Contribution

=

Innovation Gap Score × 20%

---

# 3. Market Position Risk

## Purpose

Measures risk of losing market relevance, leadership position, or strategic standing.

---

## Examples

* Losing enterprise customers
* Reduced AI market competitiveness
* Declining perception of innovation
* Reduced customer confidence

---

## Market Position Scoring

| Market Risk | Score |
| ----------- | ----- |
| Minimal     | 10    |
| Low         | 25    |
| Medium      | 50    |
| High        | 75    |
| Critical    | 100   |

---

## Weight

20%

Formula:

Market Position Contribution

=

Market Position Score × 20%

---

# 4. Competitor Threat Matrix

## Purpose

Measures direct threat posed by competitors.

---

## Competitor Categories

### Business Productivity Competitors

* Dell Latitude
* Lenovo ThinkPad
* Microsoft Surface

### Workstation Competitors

* Dell Precision
* Lenovo ThinkPad P Series

### AI & Innovation Competitors

* Apple Silicon Platforms
* Dell AI Workstations
* Lenovo AI Ready Platforms

---

## Threat Levels

| Threat Level | Score |
| ------------ | ----- |
| Minimal      | 10    |
| Low          | 25    |
| Medium       | 50    |
| High         | 75    |
| Critical     | 100   |

---

## Threat Examples

### Medium

Competitor offers similar capabilities

### High

Competitor offers superior capability

### Critical

Competitor significantly ahead in AI, performance, or innovation

---

## Weight

15%

Formula:

Competitor Threat Contribution

=

Threat Score × 15%

---

# 5. Migration Risk

## Purpose

Measures likelihood that customers, users, or departments move to alternative solutions.

---

## Examples

* Business unit selects competitor device
* Employee preference shifts to competitor products
* Customer requests competitor platform

---

## Migration Risk Scoring

| Migration Risk | Score |
| -------------- | ----- |
| None           | 0     |
| Low            | 25    |
| Medium         | 50    |
| High           | 75    |
| Critical       | 100   |

---

## Migration Indicators

### Low

No alternative evaluation

### Medium

Alternatives being considered

### High

Active competitor evaluation

### Critical

Migration decision underway

---

## Weight

10%

Formula:

Migration Contribution

=

Migration Score × 10%

---

# 6. Talent Retention Risk

## Purpose

Measures risk of employee dissatisfaction caused by inadequate tools or technology.

---

## Examples

* AI engineers lack suitable hardware
* Developers unable to run workloads
* Analysts experience poor productivity

---

## Talent Risk Scoring

| Risk Level | Score |
| ---------- | ----- |
| None       | 0     |
| Low        | 25    |
| Medium     | 50    |
| High       | 75    |
| Critical   | 100   |

---

## Weight

10%

Formula:

Talent Contribution

=

Talent Retention Score × 10%

---

# Final Competitive Risk Formula

Competitive Risk Score =

(Feature Gap × 25%)

*

(Innovation Gap × 20%)

*

(Market Position × 20%)

*

(Competitor Threat × 15%)

*

(Migration Risk × 10%)

*

(Talent Retention Risk × 10%)

---

# Example Calculation

Requirement:

AI Engineering requests HP ZBook with AI GPU.

Assessment:

| Factor            | Score |
| ----------------- | ----- |
| Feature Gap       | 75    |
| Innovation Gap    | 90    |
| Market Position   | 70    |
| Competitor Threat | 80    |
| Migration Risk    | 60    |
| Talent Retention  | 85    |

Calculation:

(75×0.25)

*

(90×0.20)

*

(70×0.20)

*

(80×0.15)

*

(60×0.10)

*

(85×0.10)

=

18.75

*

18

*

14

*

12

*

6

*

8.5

=

77.25

---

Final Score:

Competitive Risk Score = 77

Classification = HIGH RISK

---

# Competitive Risk Interpretation

| Score    | Meaning                     |
| -------- | --------------------------- |
| 85-100   | Immediate Strategic Concern |
| 70-84    | High Competitive Risk       |
| 50-69    | Moderate Competitive Risk   |
| 30-49    | Low Competitive Risk        |
| Below 30 | Minimal Competitive Risk    |

---

# Executive Response Matrix

| Competitive Risk | Recommended Action         |
| ---------------- | -------------------------- |
| Critical         | Immediate Executive Review |
| High             | Accelerated Approval       |
| Medium           | Standard Review            |
| Low              | Monitor                    |
| Minimal          | No Action Required         |

---

# HP AI Laptop Example

Requirement:

HP ZBook with AI GPU for AI Engineering

Competitor Analysis:

| Competitor               | Threat |
| ------------------------ | ------ |
| Dell Precision           | High   |
| Lenovo ThinkPad P Series | Medium |
| Apple Silicon            | High   |

Feature Gap:

AI GPU inventory shortage

Innovation Gap:

Delayed AI enablement

Market Risk:

Potential perception of slower AI adoption

Final Competitive Risk Score:

77

Classification:

HIGH RISK

Recommendation:

Accelerate fulfillment to maintain competitive positioning.

---

# Confidence Adjustment Rules

Reduce confidence by 5% if:

* Competitor information unavailable
* Market position unclear
* Feature gap assumptions used
* Migration risk estimated
* Innovation roadmap unknown

Maximum Confidence = 100%

Minimum Confidence = 50%

---

# Agent Output Requirements

Every Competitive Risk Assessment must generate:

* Feature Gap Risk Score
* Innovation Gap Risk Score
* Market Position Risk Score
* Competitor Threat Score
* Migration Risk Score
* Talent Retention Risk Score
* Competitive Risk Score
* Competitive Risk Classification
* Primary Competitor Threat
* Executive Recommendation
* Confidence Score
* Executive Summary

# Data Quality Engagement Model

## Ownership

Business defines:

- Expected Quality
- Thresholds
- Business Impact

Steward defines:

- Rule Implementation
- Monitoring

Technology executes:

- Profiling
- Assessment
- Scoring

---

## Example

Business Rule:

Customer ID must be unique.

Technical Rule:

Duplicate Count = 0

---

## Recommended Pattern

Business users should not require access to:

- Raw Data
- Profiling Results
- Technical Metadata

Business users should review:

- Quality Scores
- Trends
- Exceptions

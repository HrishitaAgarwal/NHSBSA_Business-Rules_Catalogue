# DMN Rule Definition Document

## 1. Document Metadata
- **Document Title:** Business Rules for [Domain]
- **Version:** 1.0
- **Author:** [Author Name]
- **Date:** 2024-08-08
- **Reviewers:** [Reviewer Names]
- **Approval Status:** Draft

## 2. Domain Information
- **Domain Name:** [Domain Name]
- **Domain Description:** [Brief Description]
- **Stakeholders:** [List of Stakeholders]

## 3. Rule Definition Information
- **Rule Definition ID:** P001
- **Rule Definition Name:** [Policy Name]
- **Description:** [Detailed Description]
- **Effective Date:** 2024-08-01
- **Business Owner:** [Rule Definition Business Owner]

## 4. Business Rule Information
- **Rule ID:** R001
- **Rule Name:** [Rule Name]
- **Rule Description:** [Detailed Description]
- **Related Policy ID (if applicable):** P001
- **Rule Conditions:**
  - **Condition 1:** [Condition Description]
  - **Condition 2:** [Condition Description]
- **Rule Actions:**
  - **Action 1:** [Action Description]
  - **Action 2:** [Action Description]
- **Business Impact:** [Description of Impact]
- **Rule Owner:** [Rule Owner Name]

## 5. DMN Rule Definition
### 5.1 DMN Model 
- **DMN Model Name:** [DMN Model Name]
- **DMN Model ID:** DMN001
- **Decision Table Name:** [Decision Table Name]
- **Decision Table ID:** DT001
- **Inputs:**
  - **Input 1:** [Input Description]
  - **Input 2:** [Input Description]
- **Outputs:**
  - **Output 1:** [Output Description]
  - **Output 2:** [Output Description]
- **Decision Logic:**
  - **Condition 1:** [Condition Description]
  - **Condition 2:** [Condition Description]
  - **Action 1:** [Action Description]
  - **Action 2:** [Action Description]
- **<<this section can be repeated if more than 1 DMN models are used>>**

## 6. Dependencies
- **Included Model Name:**
- **Invoked Decision Service**

## 7. Exception Scenario
- **<<Add any exception scenario>>**

## 7. Traceability Matrix

| Rule ID | Policy ID | DMN Model ID | Decision Table ID | Input  | Output  | Stakeholder  | Status |
|---------|-----------|--------------|-------------------|--------|---------|--------------|--------|
| R001    | P001      | DMN001       | DT001             | Input1 | Output1 | Stakeholder1 | Active |

## 8. Change Log

| Version | Date       | Author        | Description of Changes            |
|---------|------------|---------------|-----------------------------------|
| 1.0     | 2024-08-08 | [Author Name] | Initial creation                  |

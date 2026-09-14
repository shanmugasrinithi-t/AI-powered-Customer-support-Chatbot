# AI-Powered Customer Support Chatbot – E-Commerce

## Business Analyst Portfolio Project

**Role:** Business Analyst – AI/ML Product  
**Domain:** E-Commerce  
**Project Type:** AI Customer Support / Business Analysis

---

## 📌 Project Overview

This project focuses on the analysis and requirements definition for an **AI-powered customer support chatbot** for an e-commerce company.

The chatbot is designed to handle common customer enquiries related to:

- Orders
- Returns
- Refunds
- Frequently Asked Questions (FAQs)
- Human agent escalation

As the Business Analyst, I analyzed the business problem, identified stakeholder needs, defined requirements, created user stories and acceptance criteria, mapped the chatbot process, defined AI/data requirements, considered AI risks and ethics, designed test cases, and defined KPIs for measuring chatbot performance.

---

## 🎯 Business Problem

E-commerce customer service teams often spend significant time handling repetitive enquiries such as:

- "Where is my order?"
- "Can I return this product?"
- "When will I receive my refund?"
- "What is the return policy?"

Handling these repetitive enquiries manually can increase response time and customer-service workload.

### Proposed Solution

An AI-powered chatbot that can provide responses to supported customer enquiries and escalate complex or unsupported enquiries to a human customer service agent.

---

## 🎯 Business Objectives

The project aims to:

1. Reduce repetitive customer enquiries handled manually by the customer service team.
2. Improve customer response time.
3. Provide accurate answers to predefined FAQs.
4. Provide authorized customers with order, return, and refund information.
5. Escalate complex or unsupported enquiries to human agents.
6. Monitor chatbot performance using defined KPIs.

---

## 👥 Stakeholders

| Stakeholder | Responsibility / Interest |
|---|---|
| Customer | Uses the chatbot to obtain support |
| Customer Service Team | Handles escalated enquiries |
| Product Owner | Defines product priorities |
| Business Analyst | Analyzes requirements and documents business needs |
| Product Manager | Oversees product objectives |
| Development Team | Builds the chatbot solution |
| AI/ML Team | Develops and evaluates AI capabilities |
| QA Team | Validates functionality and requirements |
| DevOps Team | Supports deployment and availability |

---

# 🔍 Scope

## In Scope

- FAQ support
- Order-related enquiries
- Return-related enquiries
- Refund-related enquiries
- Customer authentication before accessing account-specific information
- Authorized customer account/order information
- Human agent escalation
- Basic chatbot performance monitoring

## Out of Scope

- Regional language support
- Voice-based chatbot
- Autonomous high-risk decisions
- Autonomous refund approval or rejection

---

# 📋 Business Requirements

The major business requirements include:

- Provide timely responses to repetitive customer enquiries.
- Improve customer response time.
- Provide accurate answers to predefined FAQs.
- Escalate complex questions to human customer service agents.
- Protect customer account information.
- Allow customers to obtain order, return, and refund information.
- Reduce repetitive workload for customer service teams.
- Monitor chatbot and customer-support performance.

---

# ⚙️ Functional Requirements

The chatbot should:

- Provide order, return, and refund information.
- Respond to supported enquiries within the defined response-time requirement.
- Answer common FAQ enquiries.
- Provide an option to escalate unsupported or complex enquiries to a human agent.
- Verify customer authentication before providing account-specific information.
- Allow authenticated customers to view authorized order, return, and refund information.
- Provide an admin dashboard for authorized administrators to monitor chatbot performance and support outcomes.

---

# 📏 Non-Functional Requirements

### Performance

The chatbot should provide responses within **2–5 seconds under normal operating conditions**.

### Security & Privacy

The system should:

- Collect only necessary customer information.
- Protect customer information from unauthorized access.
- Provide account-specific information only to authorized customers.

### Availability

The chatbot should be available **24/7**, subject to planned maintenance and service interruptions.

### Usability

The chatbot should provide a simple and intuitive interface.

---

# 👤 User Stories

### US01 – Order Information

> As an authenticated customer, I want to view my order status and estimated delivery information so that I know when my order will arrive.

### US02 – Return Information

> As a customer, I want to know the return window and return details so that I can determine whether I can return my order.

### US03 – Refund Information

> As a customer, I want to view my refund status and expected refund information so that I know when I can expect my refund.

### US04 – Human Agent

> As a customer, I want to contact a human agent when the chatbot cannot resolve my enquiry so that I can receive further assistance.

### US05 – FAQ Support

> As a customer, I want quick answers to common questions so that I do not need to contact a customer service agent for simple enquiries.

### US06 – Conversation Context

> As a customer, I want the human agent to receive the relevant chatbot conversation context so that I do not have to repeat my enquiry.

### US07 – Authorized Account Information

> As an authenticated customer, I want to access my authorized account-related order, return, and refund information so that I can manage my enquiries securely.

### US08 – Chatbot Monitoring

> As an administrator, I want to monitor chatbot performance so that I can identify areas for improvement.

---

# ✅ Acceptance Criteria

Acceptance criteria were created to make the requirements **clear, testable, and measurable**.

### Example – Order Status

**Given** the customer is authenticated and provides a valid order ID  
**When** the customer requests order information  
**Then** the chatbot should display the order status and estimated delivery information.

### Example – Invalid Order

**Given** the customer provides an invalid or nonexistent order ID  
**When** the chatbot searches for the order  
**Then** the chatbot should inform the customer that the order could not be found.

### Example – Human Escalation

**Given** the chatbot cannot reliably answer a supported enquiry  
**When** the customer requests further assistance  
**Then** the chatbot should provide an option to escalate the enquiry to a human agent.

---

# 🤖 AI & Data Requirements

The chatbot requires reliable data to provide accurate responses.

### Data Requirements

The project considers:

- Order data
- Return data
- Refund data
- FAQ data
- Authorized customer account data
- Conversation data

### Data Quality

Required data should be:

- Complete
- Accurate
- Relevant to the chatbot's supported use cases

---

# 📊 AI Performance Criteria

The project defines target performance criteria for the AI system.

| Area | Target |
|---|---:|
| FAQ answer accuracy | ≥ 90% |
| Account-specific information accuracy | ≥ 80% |
| Order/return/refund information accuracy | ≥ 80% |
| Overall supported enquiry accuracy/completeness | ≥ 85% |

The chatbot should also retain relevant conversation context when transferring a conversation to a human agent.

---

# 🔄 AI Fallback & Human Escalation

The chatbot should not provide an answer when it cannot reliably determine the correct response.

### Fallback principles

- Do not generate answers based on insufficient or unsupported information.
- Provide a fallback response when confidence is insufficient.
- Offer escalation to a human agent when required.
- Transfer relevant conversation context to the human agent.
- Do not make autonomous high-risk decisions such as refund approval or rejection.

---

# 🔐 Security, Privacy & Responsible AI

The project considers responsible use of AI and customer data.

### Security & Privacy

- Protect customer personal information.
- Collect and process only necessary information.
- Verify authorization before providing account-specific information.
- Inform customers that they are interacting with an AI chatbot.
- Retain relevant conversation records according to applicable retention requirements.

### AI Risks Considered

The project identifies and addresses risks including:

- AI bias
- Hallucination / incorrect responses
- Low-confidence responses
- Unauthorized exposure of account information
- Lack of transparency
- High-risk autonomous decisions

### Mitigation Approach

The chatbot should:

- Use reliable and validated data.
- Avoid unsupported answers.
- Provide fallback responses when necessary.
- Escalate complex cases to human agents.
- Restrict access to authorized customer information.
- Clearly disclose that the customer is interacting with an AI chatbot.
- Avoid autonomous high-risk decisions.

---

# 🔀 BPMN / Process Flow

The chatbot process was mapped using a **BPMN-style process flow**.

### High-Level Process

```text
Customer Starts Chat
        ↓
Customer Enquiry
        ↓
Identify Enquiry Type
        ↓
Is Authentication Required?
     ↙           ↘
   Yes            No
    ↓              ↓
Authenticate     Process FAQ
    ↓              ↓
Authorized?      Generate Response
  ↙     ↘             ↓
Yes      No       Is Response Reliable?
 ↓        ↓          ↙        ↘
Provide   Deny/      Yes       No
Account   Restrict    ↓         ↓
Info      Access    Respond   Escalate
                         \       /
                          \     /
                       Human Agent

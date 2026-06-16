# Design Rationale

## Project Overview

ClientFlow CRM is a B2B SaaS CRM dashboard designed for a 5-member web design and development agency managing 30–50 clients and leads.

The goal of this project was to centralize agency workflows into one platform and improve operational visibility, lead tracking, task management, and follow-up organization.

The CRM was designed to solve workflow confusion caused by spreadsheets, messaging apps, and disconnected systems.

---

# Problem Statement

Small agencies often struggle with fragmented workflows.

Teams commonly rely on:

- spreadsheets
- WhatsApp communication
- scattered notes
- disconnected tools

This creates several problems:

- missed follow-ups
- poor lead visibility
- delayed communication
- unclear ownership
- task confusion
- operational inefficiency

As agencies grow, these manual systems become difficult to manage.

ClientFlow CRM was designed to centralize agency operations and reduce workflow complexity.

---

# Business Context

### Business Type

Web Design & Development Agency

### Team Size

5 Team Members

### Client Volume

30–50 active leads and clients

### Primary Business Need

A centralized CRM system to manage:

- leads
- clients
- follow-ups
- tasks
- communication
- business visibility

---

# User Roles

## Agency Owner / Admin

### Responsibilities

- monitor agency performance
- review overdue work
- assign tasks
- manage clients
- track business health

### Goals

- reduce missed opportunities
- improve visibility
- improve client satisfaction

---

## Team Member

### Responsibilities

- manage assigned leads
- complete follow-ups
- update task status
- communicate with clients

### Goals

- stay organized
- reduce missed deadlines
- improve workflow clarity

---

# Workflow Logic

The CRM was designed around realistic agency workflows.

### Lead Management

Lead Added  
→ Contacted  
→ Meeting Scheduled  
→ Proposal Sent  
→ Negotiation  
→ Converted

Converted leads become active clients.

---

### Client Management

Client information, engagement, notes, and project visibility are centralized in one profile.

---

### Follow-Up Management

Follow-ups are converted into tasks to reduce missed communication.

---

### Task Workflow

Tasks move through:

Upcoming  
→ In Progress  
→ Completed

This improves accountability and operational tracking.

---

# UX Decisions

Several UX decisions were intentionally made to improve operational clarity.

## Action-First Dashboard

The dashboard prioritizes urgent actions first.

Why?

Agency teams need immediate visibility into overdue tasks and follow-ups.

---

## Kanban Lead Pipeline

A kanban system was used to improve lead visibility and sales tracking.

Why?

Users can quickly understand where opportunities are stuck.

---

## Scalable Tables

Client management uses scalable tables and filters.

Why?

The product must support larger amounts of data as agencies grow.

---

## Client Health Indicators

Status badges help teams understand engagement risk.

Examples:

- Healthy
- At Risk
- Pending Payment
- Waiting Feedback

Why?

This improves decision-making speed.

---

## Task Prioritization

Tasks were visually prioritized.

Why?

Missed follow-ups directly impact agency revenue.

---

## Responsive Product Thinking

Spacing, hierarchy, and layout were designed to scale across different screen sizes.

---

# Edge Cases Considered

Several realistic CRM edge cases were included.

### Duplicate Lead
Prevent repeated lead creation.

### Overdue Follow-Up
Visual alerts for missed communication.

### Stuck Lead
Identify inactive opportunities.

### Overdue Task
Improve accountability.

### Empty States
Clear guidance when no data exists.

### No Search Results
Helpful recovery interaction.

---

# How This Dashboard Improves Agency Efficiency

Compared to spreadsheets and messaging tools, ClientFlow CRM improves:

### Better Visibility
Clear operational overview.

### Better Follow-Ups
Reduced missed communication.

### Better Organization
Centralized client tracking.

### Better Productivity
Improved task visibility.

### Better Scalability
Supports agency growth.

---

# Final Outcome

ClientFlow CRM provides a scalable and realistic SaaS dashboard experience for agencies.

The final solution improves:

- workflow clarity
- operational efficiency
- lead visibility
- task organization
- follow-up management
- client tracking

The dashboard was intentionally designed to feel like a modern B2B SaaS product rather than a collection of isolated screens.

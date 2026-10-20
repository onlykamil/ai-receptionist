# AI-Receptionist — Self-Service AI Agent Creation Platform

An instant AI voice and chat agent creation platform that automatically builds seed knowledge-base from a company's website and available online resources. Built as a pure Progressive Web App (PWA), it includes administrator dashboard, analysis tools and administrator-managed Google Calendar and email integrations, with platform APIs supporting custom enterprise workflow integrations.

**Role:** Platform Developer and AI Solutions Engineer  
**Deployment:** Two business customers  
**Architecture:** Pure Progressive Web App (PWA)  
**Languages:** Four supported languages  
**Core Capabilities:** Voice AI · Chat AI · Automated Knowledge-Base Creation · Enterprise Systems Integration

**Live Product:** [AI-Receptionist Voice/Chat](https://voice.business-folio.com)**
---
Create one for your company and try it

## At a Glance

| Capability | Description |
|---|---|
| Agent creation | Submit company URL, administration email and password |
| Automated knowledge preparation | Automatically seed business information knowledge-base will be prepared |
| Voice and chat Agent | Access to dialer and administration will be provided instantly |
| Call | Agent will be able to respond to based on the discovered knowledge |
| Built-in integrations | Allow administrators to connect Google Calendar and email |
| Enterprise integration | Use platform APIs to develop integrations with customer-specific business systems |
| Real-world deployment | Two businesses created agents through the platform |

## 1. Overview

I designed and developed AI-Receptionist as a reusable platform that enables businesses to create their own AI-powered voice and chat agents without requiring a separate application to be developed for each business.

The process begins with a company website URL. The platform gathers available online business information and automatically prepares a seed knowledge base for the agent. Businesses can then use the generated agent for voice and chat interactions.

The platform also supports integration with existing business systems. I implemented customer-specific integrations for two businesses, connecting their agents with their respective CRM, accounting, and tax management systems.

Additional services, including Google Calendar and email, can be connected directly by business administrators through the administrative interface.

## 2. Platform Architecture

The platform separates reusable agent creation capabilities from customer-specific enterprise integrations.

```mermaid
flowchart TD
    A[Company Website URL] --> B[Online Information Gathering]
    B --> C[Seed Knowledge Base]
    C --> D[Self-Service Agent Creation]
    D --> E[Voice Agent]
    D --> F[Chat Agent]
    E --> G[Business Workflows]
    F --> G
    G --> H[Customer-Specific Integrations]
    H --> I[CRM]
    H --> J[Accounting System]
    H --> K[Tax Management System]
    H --> L[Facility Management]
    G --> L[Administrator-Connected Services]
    L --> M[Google Calendar]
    L --> N[Email]

# Rental Housing Analysis Application

Welcome to the Rental Demand Analysis Application repository!

## Welcome! 👋  
Thanks for checking out my repo.

---

## Table of Contents

- [About the Project](#about-the-project)
  - [Overview](#overview)
  - [Goals](#goals)
- [Technologies Used](#technologies-used)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [The Design](#the-design)
- [Author](#author)
- [Acknowledgements](#acknowledgements)
- [License](#license)

---

## About the Project

### Overview

This project analyzes the relationship between rental housing demand and various property features using data mining techniques and relational database design. It focuses on identifying the most impactful features that affect rental demand and explores how data can be scaled and stored for long-term business intelligence.

### Goals

The main objectives of the project included:

#### Data Preparation & Preprocessing
- Clean and convert flat file data (CSV) to Weka-compatible ARFF format.
- Resolve missing, inconsistent, and invalid values.
- Normalize features for improved model accuracy.

#### Data Mining and Prediction
- Use classification and regression models in Weka to predict **low** and **high** rental demand.
- Identify significant predictors from discrete and continuous features (e.g., `bedrooms`, `rent`, `smoking_allowed`, `sqfeet`, etc.).
- Analyze correlation between rental demand and property type or rent value.

#### Statistical & Visual Insights
- Explore the optimal property size range for generating high demand.
- Provide summary statistics and support model findings with screenshots from Weka.

#### Relational Database Design
- Translate the flat file into a normalized relational schema (3NF).
- Build sample SQL statements to support property insertion and queries based on business use cases.

#### Scalability & Futureproofing
- Propose a scalable infrastructure for international expansion.
- Explore real-time analytics solutions with horizontal scaling, distributed systems, and automated alerting.

#### Privacy Considerations
- Identify and address privacy risks associated with a public-facing app.
- Recommend strategies aligned with data ethics and regulatory compliance.

---

##  Technologies Used

### Tools & Platforms
- **Weka 3.8.5** – for data mining, classification, and regression
- **SQL (MySQL/PostgreSQL)** – for relational database design and queries
- **Draw.io** – to create UML Entity Relationship Diagrams

### Techniques & Approaches
- Classification and regression
- Feature selection
- Correlation analysis
- Normalization and data cleaning
- ER modeling and 3NF normalization

---

###  What I Learned

During this project, I gained valuable experience in:

- **Data Mining with Weka:** Selecting classifiers, tuning models, interpreting decision trees and confusion matrices.
- **Data Cleaning & Preprocessing:** Ensuring datasets were usable in both SQL and machine learning environments.
- **Relational Modeling:** Designing a relational schema that reflects business logic while maintaining normalization.
- **Scalable System Design:** Understanding the importance of distributed systems and streaming analytics.
- **Data Privacy:** Balancing data collection with compliance by identifying privacy risks in public-facing applications.

---

### Continued Development

Future improvements will include:

- Deploying predictive models through an interactive dashboard
- Enhancing the GUI and form-based input for property managers and clients
- Implementing GDPR-style data governance into system design

---

### The Design

The project embraces a **modular design**:

- **Task 1:** Data mining using Weka (.ARFF file preparation + predictive modeling)
- **Task 2:** Database design and SQL query creation for structured storage and retrieval
- **Task 3:** Privacy evaluation for public-facing app development

Each task is implemented independently but contributes to a complete system lifecycle — from raw data to insight generation to ethical system deployment.

---

##  Author

- Website – nicolettewoolery.com
- Instagram – @codingwithnixx

---

## Acknowledgements

Grateful to the open-source community and the academic guidance provided throughout this assignment. Special thanks to the creators of Weka and the resources that helped with SQL normalization, data ethics, and model tuning.

---

## License

This project is licensed under the MIT License.

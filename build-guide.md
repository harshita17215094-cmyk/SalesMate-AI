SalesMate AI — Build Guide
1. Project Overview

SalesMate AI is an AI-powered lead qualification and sales automation project.

The system is designed to collect customer information, analyze potential leads using AI, assign a lead score and category, and recommend a suitable service.

The project uses fictional sample data for demonstration and testing.

2. Technologies Used

The project uses the following tools:

Typebot — for collecting customer information
n8n — for workflow automation and integration
Google Gemini — for AI-based analysis
Google Colab — for data analysis and visualization
Python — for analytics
Pandas — for data processing
Matplotlib — for charts
GitHub — for project files and documentation
Power Automate — for sales automation
3. Customer Data Collection

A Typebot was created to collect information from potential customers.

The Typebot collects information such as:

Customer name
Business name
Business type/industry
Number of employees
Business requirement
Approximate budget
Implementation timeline
Email
Mobile number

The collected information is intended to be used for lead analysis and qualification.

4. AI Analysis

The project uses AI prompts to analyze customer information.

Four main AI modules were prepared:

4.1 Intent Classification

The Intent Classification module identifies the customer's intent.

Possible categories are:

Product Enquiry
Pricing
Recommendation
Sales
Support
Other

The module also provides a confidence level and a short reason.

4.2 Lead Scoring

The Lead Scoring module calculates a score out of 100.

The scoring factors include:

Clear requirement
Budget provided
Urgent requirement
Requested quotation
Business details
Purchase timeline

The lead is classified as:

80–100: HOT
50–79: WARM
0–49: COLD
4.3 Product Recommendation

The Product Recommendation module analyzes the customer's requirement and recommends a suitable service based on the available service information.

4.4 SalesMate AI Analysis

The main AI analysis is designed to return:

Intent
Industry
Requirement
Budget
Timeline
Lead score
Lead category
Recommended service

The AI output is designed to be returned in JSON format for easier processing by the automation workflow.

5. Sample Dataset

A fictional dataset was created for testing and analytics.

The dataset contains 30 sample leads.

The dataset includes:

Lead ID
Customer Name
Business Name
Industry
Employee Count
Requirement
Budget
Timeline
Lead Score
Lead Category
Recommended Service
Conversion Status

The dataset is used for demonstration purposes and does not contain real customer information.

6. Google Colab Analytics

Google Colab was used to analyze the sample lead dataset.

The notebook uses Python and Pandas to calculate:

Total number of leads
HOT/WARM/COLD lead distribution
Most requested services
Average lead score
Conversion rate
Industry-wise enquiries

Matplotlib was used to create visualizations.

The notebook contains charts for:

Lead category distribution
Most requested services
Industry-wise enquiries
Conversion status

The completed notebook is stored in the project's GitHub repository.

7. GitHub Repository

A GitHub repository named SalesMate-AI was created to organize the project.

The repository contains project documentation, the dataset, the Google Colab notebook, workflow files, and screenshots.

The repository structure includes:

SalesMate-AI/
├── README.md
├── project-documentation.md
├── workflows.md
├── colab/
├── data/
├── workflows/
└── screenshots/

The repository is used to keep the project files organized and provide documentation of the work completed by the team.

8. Testing

Fictional sample leads were used to test the analytics and AI logic.

Different industries, requirements, budgets, timelines, lead scores and lead categories were included in the dataset.

Screenshots were also collected from the team members to document the development and testing process.

9. Current Project Status

The following parts have been completed:

Typebot customer information collection
AI prompts for intent classification
AI prompts for lead scoring
AI prompts for service recommendation
AI analysis output structure
30-lead sample dataset
Google Colab analytics
Data visualizations
GitHub repository
Project documentation
Screenshots

The Typebot-to-n8n test webhook connection and final n8n workflow are currently being completed by the team.

10. Overall Project Flow
Customer
   ↓
Typebot
   ↓
n8n
   ↓
Google Gemini AI
   ↓
Intent Classification
   ↓
Lead Scoring
   ↓
Lead Category
   ↓
Service Recommendation
   ↓
Sales Automation / Storage
   ↓
Google Colab Analytics
   ↓
GitHub Documentation
11. Conclusion

SalesMate AI demonstrates how AI can be used to analyze customer enquiries, qualify potential leads, recommend services, and support sales automation.

The project combines Typebot, n8n, Gemini, Google Colab, Python and GitHub to create a complete demonstration of an AI-based sales workflow.
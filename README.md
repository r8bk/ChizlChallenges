# ML Engineer Take-Home Challenge
**Time Allocation: 4 hours**

## Overview
Build an end-to-end machine learning pipeline for predicting customer churn using a provided dataset. This challenge evaluates your ability to handle real-world ML problems from data exploration through model deployment considerations.

## Dataset
**Download the dataset here: [customer_churn_data.csv]**

You'll work with a [telecom customer churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/discussion?sort=hotness)) dataset containing:
- Customer demographics (age, gender, location)
- Account information (tenure, contract type, payment method)  
- Service usage (monthly charges, total charges, services subscribed)
- Target variable: `Churn` (binary: 0/1)

**Note**: The dataset contains some realistic data quality issues you'll need to address, including missing values, inconsistent formatting, and potential duplicates.

## Tasks

### 1. Data Analysis & Preprocessing (60 minutes)
- Perform exploratory data analysis with key insights
- Handle missing values and data quality issues
- Feature engineering (create at least 2 meaningful derived features)
- Data visualization showing churn patterns
- Document your preprocessing decisions

### 2. Model Development (90 minutes)
- Implement and compare at least 3 different algorithms:
  - One tree-based model (Random Forest, XGBoost, etc.)
  - One linear model (Logistic Regression, etc.)
  - One other model of your choice
- Proper train/validation/test splits
- Handle class imbalance appropriately
- Feature selection/importance analysis
- Hyperparameter tuning for your best model

### 3. Model Evaluation & Interpretation (45 minutes)
- Comprehensive evaluation using appropriate metrics
- Business-focused interpretation of results
- Feature importance analysis
- Model limitations and potential improvements
- At least one visualization of model performance

### 4. Production Considerations (45 minutes)
- Create a simple inference function/API endpoint
- **Performance Analysis**: Estimate latency and throughput requirements
- **Edge Case Handling**: How would you handle out-of-distribution inputs?
- Address potential data drift concerns with specific metrics
- Outline A/B testing approach for model updates
- Simple deployment architecture diagram
- **Cost Analysis**: Rough estimate of computational costs and optimization strategies

## Deliverables

### Code
- Well-structured Jupyter notebook OR modular Python scripts
- Clean, documented code with clear comments
- Requirements.txt with dependencies

### Documentation
- README.md with:
  - Problem summary and approach
  - Key findings from EDA
  - Model performance comparison
  - Production recommendations
  - Instructions to run your code

### Critical Thinking Report (NEW)
- **Decision Journal**: Document 3-5 key technical decisions you made and WHY
- **Trade-off Analysis**: Explain at least 2 trade-offs you considered (e.g., model complexity vs interpretability)
- **Failure Analysis**: What didn't work and your hypothesis for why
- **Alternative Approaches**: What other methods could you have tried and when might they be better?

### Presentation
- 2-3 slide summary of your solution
- Focus on business impact and key technical decisions
- **Include**: One technical deep-dive slide explaining a specific choice

## Evaluation Criteria

### Technical Skills (40%)
- Code quality and structure
- Appropriate ML techniques and evaluation
- Feature engineering creativity
- Model selection rationale

### Problem-Solving (30%)
- Data quality handling
- Business understanding
- Creative approaches to challenges
- End-to-end thinking

### Communication (20%)
- Clear documentation
- Insightful visualizations
- Business-relevant insights
- Code readability

### Production Readiness (10%)
- Practical deployment considerations
- Monitoring and maintenance thoughts
- Scalability awareness

## Bonus Points
- Novel feature engineering approaches
- Advanced techniques (ensemble methods, feature selection)
- Thoughtful handling of edge cases
- Creative visualizations or insights
- Working API endpoint or Docker container

## Submission Guidelines
- Submit via GitHub repository (preferred) or ZIP file
- Include all code, documentation, and presentation materials
- Ensure reproducibility with clear setup instructions
- Total submission should demonstrate ~4 hours of focused work

## Questions?
Document any assumptions you make about the business context or data. If you encounter blockers, document your approach and reasoning for any workarounds.

---
*This challenge is designed to assess your ability to work independently on a realistic ML problem while demonstrating both technical skills and business acumen expected at a late junior/early senior level.*

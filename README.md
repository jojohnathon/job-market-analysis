# AI Investment Impact on Software Engineering Job Market

## Overview

This project analyzes the impact of AI investment on the software engineering job market using data from LinkedIn job postings and Forbes AI50 company lists. The analysis examines how AI-related keywords and skills are increasingly prevalent in job postings and correlates this with investment trends in AI companies.

## Data Sources

1. **LinkedIn Job Postings Dataset** - Contains job postings with descriptions, titles, company information, and salary data
2. **Forbes AI50 2023** - List of top 50 AI companies and their funding information for 2023
3. **Forbes AI50 2024** - List of top 50 AI companies and their funding information for 2024

## Analysis Components

### 1. AI Keyword Analysis
- Defines a comprehensive list of AI-related keywords including:
  - artificial intelligence, machine learning, deep learning, neural networks
  - GPT, ChatGPT, LLM, computer vision, NLP, reinforcement learning
  - AutoML, generative AI, transformers, BERT, Copilot, chatbot, speech recognition

### 2. Keyword Density Normalization
- Counts AI keywords in job descriptions
- Normalizes by word count to create AI keyword density metric
- Provides fair comparison across job postings of different lengths

### 3. Data Visualization
- Distribution of AI keyword density across all jobs
- Job titles ranked by AI keyword prevalence
- Comparison of jobs with vs without AI keywords
- Analysis of AI company funding trends and founding years

### 4. Investment Analysis
- Analysis of Forbes AI50 companies funding levels
- Trends in AI company founding years
- Correlation between investment and job market changes

## Key Findings

1. **AI Keyword Prevalence**: A significant portion of job postings now include AI-related keywords
2. **Job Title Evolution**: Traditional software engineering roles are increasingly incorporating AI components
3. **Investment Impact**: Substantial investment in AI companies correlates with changing skill requirements
4. **Market Transformation**: The software engineering job market is evolving toward AI integration

## Technical Implementation

- **Language**: Python
- **Libraries**: pandas, numpy, matplotlib, seaborn
- **Environment**: Jupyter Notebook
- **Data Processing**: Pandas for data manipulation and analysis
- **Visualization**: Matplotlib and Seaborn for creating charts and graphs

## Usage

1. Open the Jupyter notebook `ai_investment_impact_on_swe_market.ipynb`
2. Run all cells in sequence to perform the complete analysis
3. Review the generated visualizations and conclusions

## Files

- `ai_investment_impact_on_swe_market.ipynb` - Main analysis notebook
- `Copy_of_ai_investment_impact_on_swe_market.ipynb` - Backup copy
- `notebook` - Additional notebook format
- `README.md` - This documentation file

## Results

The analysis demonstrates clear trends showing:
- Increasing AI skill requirements across software engineering roles
- Strong correlation between AI investment and job market evolution
- Need for software engineers to develop AI/ML competencies
- Growth in AI-specific job categories and requirements

## Recommendations for Software Engineers

1. Develop familiarity with machine learning concepts and tools
2. Consider specializing in AI-adjacent fields (MLOps, AI infrastructure, AI product development)
3. Stay updated with emerging AI technologies and their practical applications
4. Build portfolio projects that demonstrate AI/ML capabilities

## License

This project is for educational and research purposes.
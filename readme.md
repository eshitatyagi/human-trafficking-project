# Human Trafficking Dataset & Analysis

**Author:** Eshita Tyagi  
**Contact:** Eshitatyagi52@gmail.com  
**GitHub:** https://github.com/eshitatyagi/human-trafficking-project  
**Last Updated:** August 29, 2025

## Project Overview

This project focuses on creating and analyzing a Human Trafficking dataset from reliable sources such as news articles and government agencies. The goal is to identify and analyze pain points in this critical area.

## Background

Human trafficking involves recruitment, harboring, or transporting people into exploitation through violence, deception, or coercion. In 2015 alone, human trafficking generated $150 billion in revenue.

### Key Statistics (ILO & Walk Free Foundation, 2017):
- **24.9 million** victims trapped in modern-day slavery
- **71%** of victims are women and girls
- **25%** are children under 18 years old

## Dataset Creation

### Methodology
- Manually reviewed over 2000 news articles
- Used Alexa.com to verify source reliability (country ranking ≤ 100)
- Collected 302 authentic rows from 2014-2019

### Dataset Features (10 columns):
1. URL of the news source
2. Origin country/location of the crime
3. Destination country/location of the crime
4. Number of people involved in trafficking
5. Ages of people involved
6. Number of male victims
7. Number of female victims
8. Category/type of trafficking crime
9. Date when the crime occurred
10. City where the crime took place

## Key Findings

### Geographic Patterns
- **USA and Malaysia** show highest female victim rates
- **USA** appears as both source and destination hotspot
- **Thailand and Indonesia** are primary destination countries
- **High trafficking volume** from India to other countries

### Demographics
- **Women (≥18 years)** are most frequent victims
- **Age group 9-17 years** most targeted among children
- **Ages 30-38** also highly affected (primarily labor trafficking)

### Crime Categories
- **Sexual Exploitation & Labor**: 46.9% of total cases
  - Sex trafficking: 22.7%
  - Forced labor: 16.7%
  - Sexual exploitation: 7.5%

### Victim-Perpetrator Relationships
- **59.4%** of victims knew their trafficker
  - Friends: 19.8%
  - Family members: 19.8%
  - Intimate partners: 19.8%
- Only **18.4%** involved unknown perpetrators

## Technologies Used

- **Python** for data analysis and processing
- **Pandas & NumPy** for data manipulation
- **Matplotlib & Seaborn** for data visualization
- **Web scraping tools** for data collection
- **Statistical analysis** methods for insights

## Installation & Usage

```bash
# Clone the repository
git clone https://github.com/eshitatyagi/human-trafficking-project.git

# Navigate to project directory
cd human-trafficking-project

# Install required dependencies
pip install -r requirements.txt

# Run the main analysis
python analysis.py
```

## File Structure

```
human-trafficking-project/
├── README.md
├── requirements.txt
├── .gitignore
├── LICENSE
├── data/
│   ├── raw/
│   └── processed/
├── analysis.py
├── visualization.py
└── results/
```

## Data Sources

1. **Primary Dataset**: Manually curated from verified news sources (2014-2019)
2. **Secondary Dataset**: Counter Trafficking Data Collaborative (CTDC) - 2004-2018
3. **Verification**: Used Alexa.com rankings to ensure source reliability

## Contributing

This project addresses a critical global issue. Contributions are welcome to:
- Expand the dataset with more recent data
- Improve analysis methodologies
- Add new visualization techniques
- Enhance data collection processes

## License

MIT License - See LICENSE file for details

## Acknowledgments

Originally developed as part of the Big Data & Policing course (S19CSE583) at IIIT Hyderabad.
Further developed and maintained by **Eshita Tyagi**.

**Data Sources:**
- Counter Trafficking Data Collaborative (CTDC)
- Manually curated news articles from verified sources
- Government agencies and NGO reports

---

## Contact

For questions, suggestions, or collaborations:
- **Email**: Eshitatyagi52@gmail.com
- **GitHub**: https://github.com/eshitatyagi

---

*This project aims to contribute to the fight against human trafficking through data-driven insights and public awareness.*

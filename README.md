# Correlation Mapping of Sanitation Access and Public Health Outcomes in Tamil Nadu

## Overview

This project investigates the relationship between sanitation access and public health outcomes across districts of Tamil Nadu using statistical analysis and Geographic Information Systems (GIS). The study aims to identify how sanitation infrastructure influences key health indicators and to provide evidence-based insights for policymakers and public health planners.

## Authors

- Dr. Deepalakshmi Rajendran
- Mrs. M. Surya
- Annie Darling Kanmani A
- Dharun R
- Isac Reegan G
- Danish Sugarstan S

## Objectives

- Analyze sanitation accessibility across districts in Tamil Nadu.
- Evaluate the relationship between sanitation access and public health outcomes.
- Identify spatial and statistical patterns using correlation analysis and GIS mapping.
- Support data-driven sanitation and public health policy decisions.

## Problem Statement

Despite significant improvements in sanitation infrastructure through initiatives such as the Swachh Bharat Mission, several regions continue to experience poor health outcomes. Unequal sanitation access, inconsistent sanitation usage, and socio-economic disparities contribute to ongoing public health challenges.

## Key Features

- District-level sanitation analysis
- Public health indicator assessment
- Pearson correlation analysis
- Multiple linear regression modeling
- GIS-based spatial visualization
- Trend analysis and district comparison
- Policy recommendation framework

## Methodology

### 1. Data Collection
Data was collected from official government and public health sources related to sanitation, health, demographic, and spatial indicators.

### 2. Data Preprocessing
- Data cleaning
- Missing value handling
- Standardization of indicators
- Data integration across sources

### 3. Statistical Analysis

#### Pearson Correlation Analysis
Used to measure the strength and direction of relationships between sanitation indicators and health outcomes.

#### Multiple Linear Regression
A regression model was developed to evaluate the influence of sanitation coverage, literacy, and income on infant mortality rates.

### 4. Spatial Analysis

GIS tools were used to:
- Visualize district-level sanitation coverage
- Identify high-risk regions
- Detect spatial patterns and disparities
- Support targeted intervention planning

## Tools and Technologies

- Python
- GIS Mapping Tools
- Statistical Analysis Techniques
- Data Visualization Libraries

## Analytical Components

### Correlation Analysis
Examines relationships between:
- Sanitation coverage
- Open defecation rates
- Infant mortality rates
- Waterborne disease prevalence
- Socio-demographic indicators

### Regression Analysis
Evaluates the impact of:
- Sanitation coverage
- Literacy rate
- Per-capita income

on public health outcomes.

### GIS Mapping
Spatial visualization helps identify:
- High-risk districts
- Disease clusters
- Sanitation vulnerability zones
- Regional disparities

## Key Findings

- Improved sanitation coverage is associated with better public health outcomes.
- Districts with higher sanitation access generally report lower infant mortality rates.
- Open defecation remains a challenge despite high reported sanitation coverage.
- Literacy and income significantly influence sanitation adoption and health outcomes.
- GIS mapping reveals geographic clusters requiring targeted interventions.

## Policy Recommendations

- Focus on sanitation usage rather than infrastructure creation alone.
- Strengthen hygiene awareness and behavior-change programs.
- Integrate sanitation initiatives with healthcare and education programs.
- Utilize GIS-based monitoring for targeted resource allocation.
- Promote gender-sensitive sanitation planning.

## Limitations

- District-level aggregation may hide local variations.
- Reliance on some self-reported survey data.
- Cross-sectional analysis limits causal interpretation.
- Temporal differences across datasets.
- Potential spatial inaccuracies in public GIS datasets.

## Future Work

- Extend analysis to other Indian states.
- Incorporate longitudinal sanitation studies.
- Develop AI-driven predictive sanitation models.
- Integrate climate and environmental factors.
- Conduct village-level GIS investigations.

## Project Structure

```text
Correlation-Mapping-Sanitation-TN/
│
├── README.md
├── DATASET.md
├── requirements.txt
│
├── datasets/
│   ├── TamilNadu_38District_Dataset.xlsx
│   ├── Expanded_Sanitation_Dataset.xlsx
│   ├── TamilNadu_GIS_Ready.csv
│   └── TamilNadu_ML_1000Records.csv
│
├── paper/
│   ├── MPCON_FINAL_IEEE.pdf
│   └── IEEE_Correlation_Mapping_of_Sanitation_Access.pdf
│
├── presentation/
│   ├── Research_Paper_Presentation.pptx
│   └── MPCON_FINAL_SCRIPT.pdf
│
├── code/
│   └── codes.docx
│
├── visualizations/
│   ├── Correlation_Matrix.png
│   ├── District_Wise_Toilet_Coverage.png
│   ├── GIS_Correlation_Mapping.png
│   ├── Toilet_Coverage_vs_IMR.png
│   ├── TamilNadu_Toilet_Coverage_Trend.png
│   ├── Data_Analysis.png
│   └── Table.png
│
├── results/
│   ├── Correlation_Analysis.md
│   ├── GIS_Insights.md
│   └── Findings.md
│
└── docs/
    ├── Methodology.md
    ├── Future_Work.md
    └── References.md
```

## Conclusion

The study demonstrates a strong relationship between sanitation access and public health outcomes in Tamil Nadu. Combining statistical modeling with GIS-based analysis provides actionable insights for policymakers and supports the development of more effective sanitation and healthcare strategies.

## Citation

If you use this work, please cite the corresponding research paper and authors.

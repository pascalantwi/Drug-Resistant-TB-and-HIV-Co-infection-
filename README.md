
# HIV/TB Co-infection Analysis in Ghana

![Research Study](https://img.shields.io/badge/Research-Study-blue)
![Python](https://img.shields.io/badge/Python-3.x-green)
![Data Analysis](https://img.shields.io/badge/Data-Analysis-orange)
![Public Health](https://img.shields.io/badge/Public-Health-red)

## 📋 Overview

This repository contains a comprehensive analysis of diagnostic gaps and systemic barriers in managing Drug-Resistant Tuberculosis (DR-TB) and HIV co-infection in Ghana. The study utilizes national programmatic data from Ghana's District Health Information Management System 2 (DHIMS 2) to evaluate treatment outcomes, diagnostic efficiency, and healthcare delivery disparities.

## 🔬 Key Findings

### Diagnostic Gaps
- **Significant variation in screening-to-diagnosis rates**: Ranging from 0.05% in Reproductive Health clinics to 2.1% in Male Wards
- **Low DR-TB detection**: Only 170 confirmed cases from 6,800 new TB cases tested by GeneXpert
- **Under-diagnosis in vulnerable populations**: Particularly concerning in ANC clinics and among PLWH

### Treatment Disparities
- **Gender parity in HIV-positive TB cases**: 1,000 males vs. 1,000 females, despite overall male predominance in TB
- **Reduced second-line treatment enrollment**: 79.31% for HIV-co-infected patients vs. 96.84% for all eligible patients
- **Pre-treatment mortality**: Primary barrier to enrollment (7 patients died before treatment initiation)

### Outcomes Analysis
- **Lower cure rates**: 36.0% for HIV-positive TB patients vs. 50.0% for general TB cohort
- **Elevated mortality**: 11.0% for HIV-co-infected vs. 5.0% for general TB patients
- **Children vulnerability**: 68% treatment completion but only 17% cure rate

### Prevention Efforts
- **High contact tracing rates**: 98% screening for child contacts
- **TPT enrollment gaps**: 80% screening vs. 75% enrollment for PLWH ≥15 years

## 📊 Visualizations

The analysis includes 6 main figures:

1. **Figure 1**: Treatment Outcomes in DR-TB Patients
2. **Figure 2**: TB Case Registration and HIV Co-infection Diagnostics
3. **Figure 3**: TB Screening and DR-TB Detection Pathway
4. **Figure 4**: Second-Line Treatment Enrollment & Systemic Barriers
5. **Figure 5**: Comprehensive TB Treatment Outcomes
6. **Figure 6**: Contact Tracing and TB Prevention Therapy (TPT) Enrollment

## 🛠️ Methodology

### Data Source
- **Platform**: Ghana District Health Information Management System 2 (DHIMS 2)
- **Timeframe**: Patient cohorts enrolled over 24-36 months; treatment outcomes from preceding 12 months
- **Population**: All reported cases including confirmed and presumptive DR-TB cases

### Statistical Analysis
- **Tools**: Python (pandas, matplotlib.pyplot, seaborn)
- **Approach**: Descriptive statistics, comparative analyses
- **Key metrics**: Diagnostic yields, DR-TB detection rates, treatment enrollment rates, outcome distributions

### Ethical Considerations
- Used only aggregated, de-identified programmatic data
- No patient interaction or individual health information access
- Compliant with Ghana Health Service guidelines

## 📈 Key Visualizations Code

The repository includes Python code for generating all visualizations:

```python
# Example: Gender Distribution Analysis
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Figure 2a: Gender Distribution
categories = ['Total TB Cases', 'HIV+ TB Cases']
male_counts = [13900, 1000]
female_counts = [6000, 1000]

# Visualization code available in appendix
```

## 💡 Recommendations

1. **Streamline diagnostic-to-treatment pathways** for HIV/TB co-infected patients
2. **Implement robust integrated care models** addressing both conditions simultaneously
3. **Develop targeted interventions** for older PLWH and other vulnerable populations
4. **Strengthen pre-treatment support** to reduce mortality before treatment initiation
5. **Enhance TPT enrollment** through improved counseling and optimized adherence protocols

## 📚 Citation

If you use this data or code in your research, please cite:

```bibtex
@article{pascal2025hivtb,
    title={Diagnostic Gaps and Systemic Barriers in DR-TB/HIV Co-infection Management in Ghana},
    author={Pascal, Antwi},
    journal={Institute of Mathematical Science, Strathmore University},
    year={2025}
}
```

## 🔧 Dependencies

- Python 3.x
- pandas
- matplotlib
- seaborn
- numpy

## 📁 Repository Structure

```
├── data/
│   └── (programmatic data files)
├── notebooks/
│   ├── 01_diagnostic_analysis.ipynb
│   ├── 02_treatment_outcomes.ipynb
│   └── 03_prevention_analysis.ipynb
├── figures/
│   ├── figure1_treatment_outcomes.png
│   ├── figure2_gender_distribution.png
│   ├── figure3_screening_diagnosis.png
│   ├── figure4_enrollment_barriers.png
│   ├── figure5_treatment_outcomes.png
│   └── figure6_contact_tracing.png
├── src/
│   ├── data_processing.py
│   ├── visualization.py
│   └── analysis.py
├── requirements.txt
├── LICENSE
└── README.md
```


## 📧 Contact

**Antwi Pascal**  
Institute of Mathematical Science, Strathmore University, Nairobi, Kenya  
Email: pascalantwi246@gmail.com

## 🙏 Acknowledgments

- Ghana Health Service for providing access to DHIMS 2 data
- Institute of Mathematical Science, Strathmore University
- All healthcare workers fighting TB/HIV co-infection in Ghana

## 📖 References

Key references from the study:
- Adeiza, M.A., et al. (2014). HIV-Associated Tuberculosis: A sub-Saharan African Perspective
- Hosu, M.C., et al. (2024). Predicting Treatment Outcomes in Drug-Resistant Tuberculosis and HIV Coinfection
- Kapata, N., et al. (2025). Undiagnosed Burden of Latent Tuberculosis, Active TB and TB-HIV Co-Infections in Africa
- Torpey, K., et al. (2020). Management of TB/HIV co-infection: the state of the evidence

---


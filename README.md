# global-covid-yll
Global years lost of life lost to COVID-19

This is the data repository for the project "Global years of life lost to COVID-19".

- Héctor Pifarré i Arolas, Centre for Research in Health Economics, Universitat Pompeu Fabra. For questions regarding the repo, please email hector.pifarre@upf.edu.
- Enrique Acosta, Max Planck Institute for Demographic Research. 
- Guillem López Casasnovas, Centre for Research in Health Economics, Universitat Pompeu Fabra. 
- Adeline Lo, University of Wisconsin-Madison.
- Catia Nicodemo: Centre of Organisation, Department of Primary Economics, University of Oxford. E
- Tim Riffe, Max Planck Institute for Demographic Research. 
- Mikko Myrskylä, Center for Social Data Science, University of Helsinki and Max Planck Institute for Demographic Research. 

All code is included in the `Code` folder and data in `Data` folder, which reproduce analysis in the project.

# References
Data are drawn from several resources.
- Global Burden of Disease Collaborative Network. Global Burden of Disease Study 2017 (GBD 2017) Results.
Seattle, United States: Institute for Health Metrics and Evaluation (IHME), 2018. Available from http://ghdx.healthdata.org/gbd-results-tool.
- T. Riffe, E. Acosta. et. al. “COVerAGE-DB: A database of COVID-19 Cases and Deaths by Age.” OSF, 15 June 2020. doi:10.17605/OSF.IO/MPWJQ.



# Code file descriptions
- `B - Excess YLL.R`: calculations of YLL for excess mortality.
- `B - Other Causes YLL.R`: calculations of YLL for other causes of mortality.
- `B - Projected YLL.R`: calculations of YLL for projected scenarios.
- `C - Compilation final measures.R`: creates measures cited throughout manuscript.
- `C - Final tables.R`: creates tables in manuscript, and a few extra.
- `C - Figures.R`: creates plots, some used in manuscript.

# Data file descriptions

### Total number of deaths, both genders combined
total_deaths_country_b.rds

### Age distribution of deaths per country -- both
deaths_age_country_b.rds

### Age distribution of deaths per country and YLLs per age
YLL_covid19_age_cummulative.rds

### Age distribution of deaths per country and YLLs per age ++ cut offs
YLL_covid19_age_cummulative_countries.rds

### YLL losts per death, rates, absolutes both gendered at not
YLL_covid19_complete.rds

### YLL lost per age all countries combined, then at cut offs
YLL_lost_by_age_global.rds
YLL_lost_by_age_global_cut_offs.rds

### Average age at which people die from covid gendered and not
Age_death_descriptives_all.rds

### Comparisons to other causes
YLL_other_causes_comparison.rds

### Projections vs current
YLL_projections.rds

### Excess 
YLL.comparison_excess.rds

### Average age at death, age distribution at death
ages_at_death_global.rds
avgsd_age_death_both_global.rds

### Gender totals
results.gender.total.rds


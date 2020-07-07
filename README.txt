WHO-COVID-19-global-data.csv
Source: https://covid19.who.int/
Variables: 
-Date_reported
-Country_code (WHO country code)
-Country
-WHO_region
-New_cases (new covid cases for reporting day)
-Cumulative_cases (cumulative number of covid cases as of reporting date)
-New_deaths (new covid deaths for reporting day)
-Cumulative_deaths (cumulative number of covid deaths as of reporting date)

UN_PopulationData.csv
Source: https://population.un.org/wpp/Download/Standard/CSV/
Variables:
-Country
-Population (reported in thousands for 2019)
-Population_Density

WHO_HealthcareSpending_PercentGDP.csv
Source (database): https://apps.who.int/nha/database/Select/Indicators/en
Variables:
-Country
-2017_Health_Spend_%GDP (amount each country's government spent on healthcare in 2017; reported as a % of GDP)

WHO_Respiratory_Deaths.csv
Source (database): https://apps.who.int/healthinfo/statistics/mortality/whodpms/
Source (explanation of variables): https://icd.codes/icd10cm/chapter10, 
Variables:
-Country
-LastAvailableDate (last year data reported)
-Overall_Respiratory_Disease_Deaths (total yearly influenza, pneumonia, chronic lower respiratory, and other deaths)
-Influenza_Deaths (total yearly deaths for influenza)
-Pneumonia_Deaths (total yearly deaths for pneumonia)
-ChronicLowerRespiratory_Deaths (total yearly deaths for chronic respiratory conditions; not influenza or pneumonia)
**see explanation source for more variable info**

WHO_InternationalHealthRegulations_CoreCapacityScores_SPARv.csv
Source: https://www.who.int/ihr/about/en/, https://www.who.int/data/gho/data/indicators/indicator-details/GHO/-average-of-13-international-health-regulations-core-capacity-scores-1st-version-of-the-questionnaire
Variables:
-Country
-2019_IHR_Compliance_Score (average score for International Health Reguations compliance questionnaire
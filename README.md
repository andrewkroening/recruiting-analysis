<img src="./imagery/banner.png" alt="Banner" width="400"/>

# Understanding Application Pipelines

***2023-2024 Capstone Project with the United States Army***

## Team Members

MIDS Students :

- [Andrew Kroening](https://github.com/andrewkroening)
- [Nick Caroll](https://github.com/nick-carroll1)
- [Suzannah Thompson](https://github.com/srt3264)
- [Eric Rios](https://github.com/EricR401S)

Faculty Mentor: [Nick Eubank, PhD](https://github.com/nickeubank)

## Stakeholders

- United States Army

## Abstract

The United States Army faces challenges in recruiting highly specialized personnel to fill certain enabler and support positions. Due to the high organizational risk of hiring the wrong person, the process is very time-consuming. Recruitment data from 2011 to 2021, encompassing over 30,000 records, revealed significant issues primarily in the initial step of recruitment, where only a third of interested applicants submitted applications. Further analysis showed substantial missing data and inconsistent formatting, limiting the analytical deductions. To address these issues, three recommendations were proposed: enforcing data validity and optimizing collection to reduce missingness, implementing logging mechanisms to track application progress, and conducting A/B tests, including email nudges and shorter application versions, to increase submission rates by motivating applicants and reducing perceived barriers.

## Prior Work

While there is currently a well-developed process for identifying and recruiting talent, this process has not been primarily data-driven in the past. Determining the feasibility of implementing data-driven practices now will allow the military to understand the investments needed as they continually optimize their hiring processes in the future. This is particularly important due to recent recruiting shortfalls across the Armed Services. This means there is a substantial risk for future shortfalls if improvements are not identified.  

## Contents

- [`ABtest_Power_Calculations.ipynb`](ABtest_Power_Calculations.ipynb) by [Eric Rios](https://github.com/EricR401S): The purpose of this notebook is to allow the users to adjust parameters for the A/B Test's experimental design. The most challenging aspect of an A/B test is settling on a feasible sample size for the entire experiment, where each arm (control and treatment) will be equal in size. In the notebook, we walk through the tradeoffs incurred by increasing/decreasing statistical power, statistical significance, and the minimum detectable effect.   To customize the experiment to your data, we added the option to load it and configure the experiment using your data.



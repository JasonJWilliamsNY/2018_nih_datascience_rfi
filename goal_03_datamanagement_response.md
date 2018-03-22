# Goal 3: "Support the Development and Dissemination of Advanced Data Management, Analytics, and Visualization Tools"



##  The appropriateness of the goals of the plan and of the strategies and implementation tactics proposed to achieve them

The strategy to leverage and support existing tool-sharing systems to encourage "marketplaces" for tools developers, and to separate funding of tool development and data generation is very important, and we support this direction of the NIH. This is a proven strategy to elavate high quality tools, for example, in the world of high-throughput genomics, one can consider the NHGRI funded Bioconductor Project as a decade-long successful use case in providing a unified interface for more than 1,000 "high-quality, open-source data management, analytics, and visualization tools".

## Opportunities for NIH to partner in achieving these goals



##  Additional concepts that should be included in the plan

The proposal as currently mentioned does not mention (1) computational reproducibility, or (2) exploratory data analysis for data quality control. These two topics are critical for the high-level goal of "extracting understanding from large-scale or complex biomedical research data". 

Computational reproducibility can be defined as the ability to produce identical results from identical data input or "raw data", and relies on biomedical researchers keeping track of metadata regarding the versions of tools that were used, the way in which tools were run, and the provenance and version of publicly available annotation files if these were used. This is very important for data science: if two groups observe discrepencies between their results, they absolutely must be able to identify the source, whether it be methodological or due to different versions of software or annotation data. 

Exploratory data analysis (EDA) needs to be a key component of the data science plan, as this should be the first step of any data analysis involving complex biological data. EDA is often how a data scientist will identify data artifacts, technical biases, batch effects, outliers, unaccounted for or unexpected heterogeneity, need for data transformation, or other various data quality issues that will cause serious problems for downstream methods, whether they be statistical methods, machine learning, deep learning, artificial intelligence or otherwise. Downstream methods may either fail to detect the relevant signal (loosely categorized as "false negatives") or may produce many spurious results which are purely associations with technical aspects of the data ("false positives"). Furthermore, Basic EDA can uncover biological signal that may be missed, such as biologically relevant heterogeneity, e.g. subtypes of disease with signal present in molecular data.

Computational reproducibilty and supporting EDA should be components of both NIH funded tool development, as well as the plan to "Enhance Workforce Development for Biomedical Data Science" (Goal 4).

## Performance measures and milestones that could be used to gauge the success of elements of the plan and inform course corrections



## Any other topic the respondent feels is relevant for NIH to consider in developing this strategic plan

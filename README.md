## Capstone Faculty-Sponsored Project (FS#5)-- Fall 2019

### Faculty Sponsor(s):
Jeffrey Shaman, Professor, Environmental Health SciencesMailman School of Public
Health;Email:jls106@cumc.columbia.edu; Lab: https://www.columbia.edu/~jls106/
Sasikiran Kandula, Senior Staff Associate, Environmental Health Sciences; Email:
sk3542@cumc.columbia.edu

### Project Description: 
The proposed project would estimate and disseminate situational awareness of deaths
resulting from suicides and drug overdoses in the US using publicly available, near real-time data from the
National Emergency Medical Services Information System (NEMSIS) (1), a national database of EMS patient
care information collected in response to emergency 911 calls.
Although mortality data in the US are available through systems such as CDC’s WONDER (2), due to
established reporting protocols and quality checks, it can take 6-18 months for information to be publicly
available. While the need for such robust processes and checks are indisputable, more timely, albeit less
accurate, data could aid public health action and is particularly relevant in the context of the increasing
mortality from suicides and drug poisonings in the US. As events resulting from these two causes are very
likely to result in EMS calls, the NEMSIS system which records, standardizes, aggregates and makes
accessible EMS data (3) in a shorter time frame (estimated to be less than a week) is worth exploring as a
secondary source to track trends in mortality from these two causes.
The initial aim of the project would be to build a web interface for geographically resolved (census region level)
mortality data from suicides and drug poisonings, with potential additional stratification by age, race/ethnicity
and gender. We envision an interface with basic functionality - visual components that effectively communicate
trends, allow for comparison across different subject groups, support for data/chart downloads etc.
More importantly, while some of the EMS events would be explicitly tagged with ICD codes specific to
suicides/drug poisoning in NEMSIS, we hypothesize that better estimates are possible through supervised
learning models that utilize other elements in the dataset (for example, medications given, procedures
performed during EMS response, etc.). An additional extension could be to develop methods for short-term
forecasts of mortality trends, of which our group has considerable experience in the context of infectious
diseases.
Taken together, we believe these objectives would allow DSI students to translate data-science techniques
from classroom to more applied settings and yield a demonstrable application that would be of value as they
pursue employment opportunities, while creating a resource with significant public health utility.
References 1. National Emergency Medical Services Information System. https://nemsis.org/what-is-nemsis/
2. Centers for Disease Control and Prevention, National Center for Health Statistics (2017) Underlying Cause
of Death 1999-2016 on CDC WONDER Online Database. http://wonder.cdc.gov/ucd-icd10.html. 3.
https://nemsis.org/view-reports/public-reports/ems-data-cube/

### Dataset Description: 
The National Emergency Medical Services Information System (NEMSIS), a national
database of EMS patient care information collected in response to emergency 911 calls. The data is hosted
online by a federal agency and is open to the general public. It contains information on most EMS calls
reported to the NEMSIS system from 2017 onwards which can be filtered to events of interest. We do not
anticipate students would be required to gather additional data or perform complex cleaning/processing.
Similarly, we do not believe extensive computing resources would be required. A server to host the application
would be provided.

### Data format: 
Downloadable as CSV/XLS.

### Project Deliverables: 
The initial aim of the project would be to build a web interface for geographically
resolved (census region level) mortality data from suicides and drug poisonings, with potential additional
stratification by age, race/ethnicity and gender. We envision an interface with basic functionality - visual
components that effectively communicate trends, allow for comparison across different subject groups, support
for data/chart downloads etc.
While some of the EMS events would be explicitly tagged with ICD codes specific to suicides/drug poisoning in
NEMSIS, we hypothesize that better estimates are possible through supervised learning models that utilize
other elements in the dataset (for example, medications given, procedures performed during EMS response,
etc.). An additional extension could be to develop methods for short-term forecasts of mortality trends, of which
our group has considerable experience in the context of infectious diseases.

### Possible deliverables:
Model, Report, Software

### Required background and skill sets: 
CSOR W4246 Algorithms for Data Science, STAT GR5702 Exploratory
Data Analysis & Visualization COMS W4721 Machine Learning for Data Science

### Learning opportunities: 
Project planning and scoping, Combining data sources, Exploratory data analysis
and visualization, Supervised modeling, Establishing evaluation metrics, Working with time series data,
Working with tabular data, Working with geospatial data

## Working with Nemsis Data Cube

### How to access the Nemsis Data cube:
- Website: https://nemsis.org/view-reports/public-reports/ems-data-cube/
  - Username and password provided there
- Watch intro video here - https://www.youtube.com/watch?reload=9&v=UaCvsFVG-JI&feature=youtu.be
- **Nemsis cube versions**:
  - Nemsis v2 Public cube: Data from 2014 - 2016
  - Nemsis v3 Public cube: Data from 2017 - today(updated frequently)
  
### Generating simple reports:
- Get started with data exploration - https://www.youtube.com/watch?v=LjwuQiDwMnM&feature=youtu.be
- Steps:
  - Select a measure. *"Count of Events"* (only one visibile to me)
  - Select Rows / Add filters: https://www.youtube.com/watch?v=_uGlGdwWa00&feature=youtu.be
  - Some useful rows/sub rows:
    - Alcohol-Drug Use Indicator
    - Complaint Reported By Dispatch
      - Overdose/Poisoning/Ingestion
    - Injury Information - Injury Cause ICDs.ICD Name
      - Suicide related ICD Names:
        - Intentional collision of ...
        - Intentional fall from one ...
        - Intentional self-harm by ...
        - Poisoning by ..., intentional self-harm
      - Opioid related ICD Names:
        - Poisoning by, adverse effect of and underdosing of methadone/opium/cocaine/acetylsalicyclic acid/other opiods/synthetic narcotics etc
        - Adverse effect of other opioids
        - Poisoning by other opioids
    - Injury Information - Injury Cause ICDs.ICD 10
      - Opioid related ICD 10s:
        - https://www.unboundmedicine.com/icd/view/ICD-10-CM/949644/all/F11_10___Opioid_abuse__uncomplicated
        - https://www.icd10data.com/ICD10CM/Codes/F01-F99/F10-F19/F11-/F11.982
        - **However, I couldn't find these codes in the system**
    - Age Category
    - Race
    - Gender (etc)
    - Year - Week - Day (Granularity)
    
### Downloading Data:
- Export to Excel (Options: Excel, Csv, ODC, PDF, HTML, Excel Pivot)
  

# SEER Breast Cancer
========

    This dataset of breast cancer patients was obtained from the 2017 November
    update of the SEER Program of the NCI, which provides information on
    population-based cancer statistics. The dataset involved female patients with
    infiltrating duct and lobular carcinoma breast cancer (SEER primary cites
    recode NOS histology codes 8522/3) diagnosed in 2006-2010. Patients with
    unknown tumour size, examined regional LNs, positive regional LNs, and patients
    whose survival months were less than 1 month were excluded; thus, 4024 patients
    were ultimately included.


## Columns
========

### AGE

Age at diagnosis Field Description: 

    This data item represents the age of the patient at diagnosis for this cancer.
    The code represents the patient’s actual age in years.

--- 

### RACE

Race recode (White, Black, Other) Field Description: 

    Race recode is based on the race variables and the American Indian/Native
    American IHS link variable. This recode should be used to link to the
    populations for white, black and other. It is independent of Hispanic
    ethnicity. For more information, see :
    http://seer.cancer.gov/seerstat/variables/seer/race_ethnicity.

    - White
    - Black
    - Other (American Indian/AK Native, Asian/Pacific Islander)
    - Other unspecified (1991+)
    - Unknown
 

--- 

### MARITAL STATUS

Marital status at diagnosis:

    This data item identifies the patient’s marital status at the time of diagnosis
    for the reportable tumor.

    - Single (never married)
    - Married (including common law)
    - Separated
    - Divorced
    - Widowed


--- 

### T STAGE

    Created from merged EOD 3rd Edition and Collaborative Stage disease
    information. Currently only available for Breast schema. For more
    information see http://seer.cancer.gov/seerstat/variables/seer/ajcc-stage/6th.

    - T1
    - T2
    - T3
    - T4

--- 

### N STAGE

    Created from merged EOD 3rd Edition and Collaborative Stage disease
    information. Currently only available for Breast schema. For more information
    see http://seer.cancer.gov/seerstat/variables/seer/ajcc-stage/6th.

    - N1
    - N2
    - N3

---

### 6TH STAGE

    Created from merged EOD 3rd Edition and Collaborative Stage disease
    information. Currently only available for Breast schema. For more information
    see http://seer.cancer.gov/seerstat/variables/seer/ajcc-stage/6th.

    - IIA
    - IIB
    - IIIA
    - IIIB
    - IIIC

--- 

### Grade 

    Grading and differentiation codes of 1-4, 9 are defined in ICD-O-2; 1992.
    Grade information may be incomplete for cases diagnosed before 1977. In the
    early 1980’s, additional codes specifying T-cell, B-cell, or null cell
    involvement in lymphomas and leukemias (histologies M9590-9940) were
    introduced by SEER. Because the reporting requirements and medical
    terminology have changed over time, care should be exercised when analyzing
    this information.

    - Grade I; grade i; grade 1; well differentiated; differentiated, NOS
    - Grade II; grade ii; grade 2; moderately differentiated; moderately differentiated; intermediate differentiation
    - Grade III; grade iii; grade 3; poorly differentiated; differentiated
    - Grade IV; grade iv; grade 4; undifferentiated; anaplastic

--- 

### A STAGE

    Derived from Collaborative Stage (CS) for 2004+ and Extent of Disease (EOD)
    from 1973-2003. It is a simplified version of stage: in situ, localized,
    regional, distant, & unknown. Over time several different EOD schemes have
    been used. Thus caution should be used when doing trend analysis. For more
    information including sites and years for which it isn't calculated, see
    http://seer.cancer.gov/seerstat/variables/seer/lrd-stage.

    - Regional — A neoplasm that has extended 1) beyond the limits of the organ
      of origin directly into surrounding organs or tissues; 2) into regional
      lymph nodes by way of the lymphatic system; or 3) by a combination of
      extension and regional lymph nodes.

    - Distant — A neoplasm that has spread to parts of the body remote from the
      primary tumor either by direct extension or by discontinuous metastasis
      (e.g., implantation or seeding) to distant organs, issues, or via the
      lymphatic system to distant lymph nodes.

--- 

### TUMOR SIZE

    Information on tumor size. Available for 2004+. Earlier cases may be converted
    and new codes added which weren't available for use prior to the current
    version of CS. Each indicates exact size in millimeters. For more information,
    see http://seer.cancer.gov/seerstat/variables/seer/ajcc-stage.

--- 

### ESTROGEN STATUS

    Created by combining information from Tumor marker 1 (1990-2003) (NAACCR Item #=1150), 
    with information from CS site-specific factor 1 (2004+) (NAACCR Item#=2880). 
    This field is blank for non-breast cases and cases diagnosed before 1990.

    - Positive
    - Negative

--- 

### PROGESTERONE STATUS

    Created by combining information from Tumor marker 2 (1990-2003) (NAACCR
    Item #=1150), with information from CS site-specific factor 2 (2004+)
    (NAACCR Item #=2880). This field is blank for non-breast cases and cases
    diagnosed before 1990.

    - Positive
    - Negative

--- 

### REGIONAL NODES EXAMINED

    Records the total number of regional lymph nodes that were removed and
    examined by the pathologist.

--- 

### REGIONAL NODES POSITIVE

    Records the exact number of regional lymph nodes examined by the
    pathologist that were found to contain metastases.

--- 

### SURVIVAL MONTHS

    Created using complete dates, including days, therefore may differ from
    survival time calculated from year and month only. For more information,
    see http://seer.cancer.gov/survivaltime.

--- 

### STATUS

    Any patient that dies after the follow-up cut-off date is recoded to alive
    as of the cut-off date.

    - Alive
    - Dead

---

## Referencese
Source: https://ieee-dataport.org/open-access/seer-breast-cancer-data

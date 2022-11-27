# SEER Breast Cancer

---

    This dataset of breast cancer patients was obtained from the 2017 November
    update of the SEER Program of the NCI, which provides information on
    population-based cancer statistics. The dataset involved female patients with
    infiltrating duct and lobular carcinoma breast cancer (SEER primary cites
    recode NOS histology codes 8522/3) diagnosed in 2006-2010. Patients with
    unknown tumour size, examined regional LNs, positive regional LNs, and patients
    whose survival months were less than 1 month were excluded; thus, 4024 patients
    were ultimately included.

---

# NUMBER OF ROWS: 4024

# COLUMNS:

### AGE
    This data item represents the age of the patient at diagnosis for this cancer.
    The code represents the patient’s actual age in years.

--- 

### RACE
    In this dataset the accuracy of the race is quiet questionable, because only listed the followings:
    - White
    - Black
    - Other (American Indian/AK Native, Asian...)

    We will pass through this, because even genetically it is relevant, not
    affecting the information what the data set provides us.

--- 

### MARITAL STATUS

    Marital status at diagnosis:

    This data item identifies the patient’s marital status at the time of diagnosis
    for the reportable tumor.

--- 

### T STAGE

    Tumour describes the size of the tumour (area of cancer). This is a simplified description of the T stage.

- T1 means that the tumour is 2 centimetres (cm) across or less.

- T2 means that the tumour is more than 2 centimetres but no more than 5 centimetres across.

- T3 means the tumour is bigger than 5 centimetres across.

- T4 is divided into 4 groups ( T4a, T4b, T4c, T4d), which can mean to where
  the cancer has spread, and what are the typical effects of each.

--- 

### N STAGE

    N categories for breast cancer. N followed by a number from 0 to 3
    indicates whether the cancer has spread to lymph nodes near the breast and,
    if so, how many lymph nodes are involved.

- N1: Cancer has spread to 1 to 3 axillary (underarm) lymph node(s), and/or
  cancer is found in internal mammary lymph nodes (those near the breast bone)
  on sentinel lymph node biopsy.

- N2: Cancer has spread to 4 to 9 lymph nodes under the arm, or cancer has
  enlarged the internal mammary lymph nodes.

- N3: Either cancer is found in at least one axillary lymph node (with at least
  one area of cancer spread greater than 2 mm) and has enlarged the internal
  mammary lymph nodes, or cancer has spread to 4 or more axillary lymph nodes
  (with at least one area of cancer spread greater than 2 mm), and to the
  internal mammary lymph nodes on sentinel lymph node biopsy.

---

### 6TH STAGE

    Doctors assign the stage of the cancer by combining the T, N, and M classifications (see above), the tumor grade, and the results of ER/PR and HER2 testing.

##### Stage 0: 
    Stage zero (0) describes disease that is only in the ducts of the breast tissue and has not spread to the surrounding tissue of the breast. It is also called non-invasive or in situ cancer (Tis, N0, M0).

##### Stage IA: 
    The tumor is small, invasive, and has not spread to the lymph nodes (T1, N0, M0).

##### Stage IB: 
    Cancer has spread to the lymph nodes and the cancer in the lymph node is larger than 0.2 mm but less than 2 mm in size. There is either no evidence of a tumor in the breast or the tumor in the breast is 20 mm or smaller (T0 or T1, N1mi, M0).

##### Stage IIA: Any 1 of these conditions:

    - There is no evidence of a tumor in the breast, but the cancer has spread to 1 to 3 axillary lymph nodes. It has not spread to distant parts of the body (T0, N1, M0). 
    
    - The tumor is 20 mm or smaller and has spread to 1 to 3 axillary lymph nodes (T1, N1, M0).
    
    - The tumor is larger than 20 mm but not larger than 50 mm and has not spread to the axillary lymph nodes (T2, N0, M0).

##### Stage IIB: 

Either of these conditions:

    - The tumor is larger than 20 mm but not larger than 50 mm and has spread to 1 to 3 axillary lymph nodes (T2, N1, M0).

    - The tumor is larger than 50 mm but has not spread to the axillary lymph nodes (T3, N0, M0).

##### Stage IIIA: 
    - The tumor of any size has spread to 4 to 9 axillary lymph nodes or to internal mammary lymph nodes. It has not spread to other parts of the body (T0, T1, T2, or T3; N2; M0). Stage IIIA may also be a tumor larger than 50 mm that has spread to 1 to 3 axillary lymph nodes (T3, N1, M0).

##### Stage IIIB: 
    - The tumor has spread to the chest wall or caused swelling or ulceration of the breast, or it is diagnosed as inflammatory breast cancer. It may or may not have spread to up to 9 axillary or internal mammary lymph nodes. It has not spread to other parts of the body (T4; N0, N1, or N2; M0).

##### Stage IIIC: 
    - A tumor of any size that has spread to 10 or more axillary lymph nodes, the internal mammary lymph nodes, and/or the lymph nodes under the collarbone. It has not spread to other parts of the body (any T, N3, M0).

##### Stage IV (metastatic): 
    - The tumor can be any size and has spread to other organs, such as the bones, lungs, brain, liver, distant lymph nodes, or chest wall (any T, any N, M1). Metastatic cancer found when the cancer is first diagnosed occurs about 6% of the time. This may be called de novo metastatic breast cancer. Most commonly, metastatic breast cancer is found after a previous diagnosis of early stage breast cancer. Learn more about metastatic breast cancer.

--- 

### Grade 

    In general, a lower grade indicates a slower-growing cancer and a higher grade indicates a faster-growing one. The grading system that's usually used is as follows:

##### Grade I: 
    - Cancer cells that resemble normal cells and aren't growing rapidly.

##### Grade II: 
    - Cancer cells that don't look like normal cells and are growing faster than normal cells.

##### Grade III:
    - Cancer cells that look abnormal and may grow or spread more aggressively.

--- 

A STAGE

    The positioning and spreading direction of the cancer.

Regional:
    - Cancer has spread to nearby lymph nodes, tissues, or organs.

Distant:
    - A distant (metastatic) recurrence means the cancer has traveled to
      distant parts of the body, most commonly the bones, liver and lungs.

--- 

TUMOR SIZE

    Information on tumor size. Each indicates exact size in millimeters.

--- 

ESTROGEN STATUS

    Describes cells that have a protein that binds to the hormone estrogen.
    Cancer cells that are estrogen receptor positive may need estrogen to grow.
    These cells may stop growing or die when treated with substances that block
    the binding and actions of estrogen.

--- 

PROGESTERONE STATUS

    If the value is positive, then this type of breast cancer is sensitive to
    progesterone, and the cells have receptors that allow them to use this
    hormone to grow. Treatment with endocrine therapy blocks the growth of the
    cancer cells.

--- 

REGIONAL NODES EXAMINED

    Records the total number of regional lymph nodes that were removed and
    examined by the pathologist.

--- 

REGIONAL NODES POSITIVE

    Records the exact number of regional lymph nodes examined by the
    pathologist that were found to contain metastases.

--- 

SURVIVAL MONTHS

    The number of months the patient has endured until recovery or death.
    The counter of the months has been started in each patient from the moment of diagnosis positive.

--- 

STATUS

    Any patient that dies after the follow-up cut-off date is recoded to alive
    as of the cut-off date.

---

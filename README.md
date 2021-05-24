#### Project Overview

In this project, you are required to build useful insights from the given data. The data is a modified version of the pseudodata obtained from this repo: https://github.com/aisinai/rad-report-annotator/tree/master/pseudodata. The data consists of ten columns namely:

    1. ACCESSION_ID  (numbers representing examination's call or serial number)
    2. DATE OF BIRTH
    3. DATE OF EXAMINATION
    4. GENDER
    5. EXAMINATION REPORT  (report of the medical examination performed on the patient)
    6. NORMAL (1 means no pathology/disease was found in the medical image, 0 means otherwise)
    7. OPACITY (1 means the examination returned a pathology named "opacity")
    8. CARDIOMEGALY (1 means the examination returned a pathology named "cardiomegaly")
    9. NODULE (1 means the examination returned a pathology named "nodule")
    10. FIBROSIS (1 means the examination returned a pathology named "fibrosis")

Note that columns (6 - 10) were based on the findings in the examination report.


#### Your task

1. Make a histogram of the patients' ages at the time of the examination.
2. How many of the patients were adults (> 18 years) at the time of the examination?
3. How many of the adult patients had "abnormal" reports?
4. Make a stacked bar plot showing the number of normal vs abnormal examinations conducted in each year?
5. Make a bar plot of the daily count of examinations conducted in the month of April 2010 compared to those conducted in April 2005.

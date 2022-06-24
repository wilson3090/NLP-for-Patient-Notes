# NLP-for-Patient-Notes

Edited between May 2021 and April 2022 as part of The Johns Hopkins Wilmer Eye Institute.

The two main tasks of the follow-wup natural language processing project are: 

1. Identify whether each patient note is related to diabetic retinopathy. This is done since the ICD code of notes could be uncoded or coded incorrectly. <br /><img src = "/Followup Code Flowchart Task 1.jpg" width = 800>
2.  Scan through patient notes using regular expressions to detect the soonest follow-up time that each patient should return for a diabetic retinopathy concern. This is a numeric value followed by a date type e.g. 4-6 weeks. This is useful since many physicians code their notes in very different ways so it takes time to manually identiy the return-to-clinic time. <br /> <img src = "/Followup Code Flowchart Task 2.jpg" width = 800>

Instructions for running the scripts are contained in the summary word document and the code is contained in `FollowUp Task 1 and Task 2.ipynb`. 

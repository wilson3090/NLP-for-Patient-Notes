# NLP-for-Patient-Notes

Edited between May 2021 and April 2022 as part of The Johns Hopkins Wilmer Eye Institute.

The two main natural language processing projects are the follow-up script and the address standardization script. 

1. The follow-up script scans through patient notes using regular expressions to detect the soonest follow-up time that each patient should return for a diabetic retinopathy concern. This is useful since many physicians code their notes in very different ways so it takes time to manually identiy the return-to-clinic time.
2. The address standardization script takes the physician-inputted address data from each patient note and manipulates the addresses so that they can be geocoded to a street level. This is relavent since often times there are typos in inputted data or address components could be rearranged in a way that prevents them from being properly geocoded.

Instructions for running the scripts are contained in the respective summary word documents

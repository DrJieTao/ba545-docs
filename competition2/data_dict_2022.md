# Data Dictionary for Project 2
Spring 2022
## Featues:
### bank client data:
1. **age**: (continuous)
2. **job**: type of job (categorical: `'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown'`)
3. **marital**: marital status (categorical: `'divorced','married','single','unknown'`; _note_: `'divorced'` means divorced or widowed)
4. **education**: (categorical (ordinal?): `'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown'`)
5. **default**: has credit in default? (categorical: `'no','yes','unknown'`)
6. **housing**: has housing loan? (categorical: `'no','yes','unknown'`)
7. **loan**: has personal loan? (categorical: `'no','yes','unknown'`)

### related with the last contact of the current campaign:
8. **contact**: contact communication type (categorical: `'cellular','telephone'`)
9. **month**: last contact month of year (categorical: `'jan', 'feb', 'mar', ..., 'nov', 'dec'`)
10. **day_of_week**: last contact day of the week (categorical: `'mon','tue','wed','thu','fri'`)
11. **duration**: last contact duration, in seconds (continuous). Important note: this attribute **highly affects** the output target (e.g., if duration=0 then y=`'no'`). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be **DISCARDED** if the intention is to have a realistic predictive model.
12. **campaign**: number of contacts performed during this campaign and for this client (continuous?, includes last contact)
13. **pdays**: number of days that passed by after the client was last contacted from a previous campaign (continuous; `999` means client was not previously contacted)
14. **previous**: number of contacts performed before this campaign and for this client (continuous)
15. **poutcome**: outcome of the previous marketing campaign (categorical: `'failure','nonexistent','success'`)

### socioeconomical features (in Portugal/Europe)
16. **emp.var.rate**: employment variation rate - quarterly indicator (continuous)
17. **cons.price.idx**: consumer price index - monthly indicator (continuous)
18. **cons.conf.idx**: consumer confidence index - monthly indicator (continuous)
19. **euribor3m**: euribor 3 month rolling average - daily indicator (continuous)
20. **nr.employed**: number of employees - quarterly indicator (continuous)

### additional features
21. **total_assets**: total assets self reported by the customer (continuous, in `1,000` Euros)
22. **customer_ratings**: customer rating of the current campaign (categorical, `1 - 5` stars)
23. **customer_language**: language used by the customer in the current campaign (categorical, `'Portuguese', 'English', 'Spanish', 'Other'`)
24. **rep_avg_rating**: average rating of the representative prior to the current campaign (continuous, within `[0, 5]` range)
25. **customer_length**: number of months customer doing business with the bank, from internal record (continuous, within `[0, 72]` range)
26. **other_banks**: if the customer is doing business with other banks, self-reported (categorical, `'yes', 'no', 'unknown'`)

## Target:
27. y - has the client subscribed a term deposit? (binary: `'yes','no'`)

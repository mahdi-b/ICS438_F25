---
title: "Reading Parquet Files"
published: true
morea_id: experience-reading-parquet-files
morea_type: experience
morea_summary: "Reading Parquet using Python"
morea_sort_order: 1
morea_labels:
---

### E03 Working Reading and Interacting with Parquet Files

You and your team need to work offline to answer the following questions. All teams will be asked to highlight their work during the next class session.


The NYC.gov website offers a variety of data, including records for yellow and green taxi trips. This data set includes details such as pick-up and drop-off times and locations, trip distances, itemized fares, rate types, payment methods, and the number of passengers as reported by drivers.


Use the pyarrow library and answer the following questions:

* How many observations does this dataset contain?
* What is the average transaction amount between 2:00-2:59 PM?

Recall that we used the following to read in the data.
```
pythonCopydataset = ds.dataset("s3://ursa-labs-taxi-data/", partitioning=["year", "month"])
```



Note that you have to properly import ds. Do you remember which library it's imported from?




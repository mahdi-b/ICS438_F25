---
title: "Introduction Big Data Analytics"
published: true
morea_id: experience-in-class-intro-bda
morea_type: experience
morea_summary: "Imagining Big Data"
morea_sort_order: 1
morea_start_date: "2024-07-29T23:00"
morea_labels: 
---


### E01 In-Class Activity Instructions: Exploring Big Data

**Objective:**  
In this activity, you'll explore the concept of big data by working through a real-world scenario. You’ll estimate how much data is generated, prototype how long it would take to read and process this data on your computer, and gain an understanding of the challenges involved.

---

**Step 1: Define the Data Source**  
First, think about a scenario that generates big data. For example, imagine you're working for a company that operates a fleet of drivers, like Uber or Lyft. Each driver’s car is equipped with GPS, and the system collects the car’s position every second. Here’s what you need to consider:

- **Fleet Size:** 1,000 drivers
- **Trips per Driver:** Each driver makes about 50 trips a day.
- **Trip Duration:** Each trip lasts about 30 minutes.
- **Data Collection Rate:** GPS data is collected every second during the trip.


**Your Task:** Calculate the total number of data points collected in one week.

**Step 2: Prototype Reading the Data**  
Next, you’ll simulate reading this data to understand how long it might take. You don’t need to actually collect the data—just imagine it’s there and simulate reading it with a Python script.

- Use Python to create a script that simulates reading data
  * Make sure your data si realistic; e.g., the file contain 4 columns, driver_id, lat, log and timestamp.
- Measure the time it takes to read a small portion of the data.
- Estimate how long it would take to read the entire dataset.

**Step 3: Estimate Processing Time**  
Now that you’ve read the data, think about processing it. For instance, you might want to calculate the number of trips less then k miles form a given location. You’ll write a Python script to simulate this and estimate the processing time.

**Your Task:**
- Write a Python script that performs a basic operation on the data.
  * You can compute the distance (Euclidean, for simplicity) to a given lat-lon
- Measure the time it takes to process a portion of the data.
- Estimate how long it would take to process the entire dataset.

**Step 4: Reflect and Discuss**  
After you’ve completed the tasks, consider these questions:

- How does the scale of the data impact the time required for reading and processing?
- What strategies could you use to handle such large datasets more efficiently?
- How could this type of data be useful in real-world applications?

Remember, this exercise doesn’t need to be complicated. The goal is to help you understand the scale and challenges of working with big data by prototyping with time on your own computer.

**Additional Ideas:**  
Feel free to think about other industries or types of data. For example, you might consider text data from customer reviews, image data from security cameras, or sensor data from smart city projects. The key is to understand the scale of data and how to approach handling it.


#### Python for Profiling and Benchmarking
You can find common methods and functions for profiling Python code and benchmarking programs [here](resources/respython_profiling_benchmarking.ipynb).



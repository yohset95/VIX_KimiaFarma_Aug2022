# VIX_KimiaFarma_Aug2022
* Created by: Yohanes Setiawan
* This project is an output of Virtual Internship Experience (VIX) as a Big Data Analyst in Kimia Farma from Rakamin Academy
![](https://drive.google.com/uc?export=view&id=1YBogKlZy3aFD2uO8e1fBqGNqbiMYDCA6) </br>
![](https://drive.google.com/uc?export=view&id=1uTDQOzDRCErExQeJsna3kVYtl_MxUeYj) </br>

# **Business Understanding**
* Problem: How is the progress of salicyl sales in Kimia Farma in 2022?
* Goal: Evaluating salicyl sales in 2022
* Objective: Creating data visualization using interactive dashboard from brand salicyl dataset in Kimia Farma

# **Analytical Approach**
* Graph analysis: analyzing sales trend through interactive dashboard

# **Data Requirement and Collection**
* Brand salicyl dataset from Kimia Farma

# **Data Understanding**
Given 1 (one) excel file contains 3 (three) tables:
* penjualan_ds : detail sales table
* pelanggan_ds : customer table from penjualan_ds (similar with "pelanggan")
* barang_ds : product table from penjualan_ds (similar with "barang")

# **Data Preparation**
I designed datamart tables using SQL (MySQL Workbench 8.0 CE) from given dataset, contains:
* table_base: joining "penjualan_ds", "pelanggan_ds", and "barang_ds"
![](https://drive.google.com/uc?export=view&id=1Ki0fPt70vOaKucjJQMN2UBD645rew-I4) </br>
![](https://drive.google.com/uc?export=view&id=19rIKIjBtSY9VIF-nfXFjPfZPBPsd0TUs) </br>
![](https://drive.google.com/uc?export=view&id=1FjUwZpA0pEdbySmshqcIpAUE0mccLH6p) </br>
* table_aggregate: aggregation columns from 3 (three) tables in dataset
![](https://drive.google.com/uc?export=view&id=1LMOVnKQyR9sY5cmomjBdp_WLSnqbiQ1G) </br>
![](https://drive.google.com/uc?export=view&id=1YSK8c4fDzEh4H3pOD7q7ZfeBs5jroWMt) </br>

# **Dashboard Modeling**
* I created an interactive dashboard using Google Data Studio and gave explanation for each visualization
* For accessing dashboard, please click on this [link](https://datastudio.google.com/reporting/df102b0f-0a62-4f90-84a0-095c536450d1)
![](https://drive.google.com/uc?export=view&id=1LmdkmrmdamYbwTQgxTBXIaSJaodTqraY) </br>
![](https://drive.google.com/uc?export=view&id=1fRqFZfL7xDE3Mt0SXqg0xOqLFa2F4Icc) </br>

# **Business Recommendation**
* Distribution of Apotek in Jakarta, Tangerang, and Lampung
* Evaluation for the low sold product quantity in Lampung and Padang

Thank you for reading!
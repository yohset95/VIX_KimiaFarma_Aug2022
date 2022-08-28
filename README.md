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
Given 1 (one) excel file contains 6 tables:
* penjualan: sales table
* pelanggan: customer table
* barang: product table from penjualan
* penjualan_ds : detail sales table
* pelanggan_ds : customer table from penjualan_ds (similar with "pelanggan")
* barang_ds : product table from penjualan_ds (similar with "barang")

# **Data Preparation**
I designed datamart tables using SQL (MySQL Workbench 8.0 CE) from given dataset, contains:
* table_base_1: joining "penjualan", "pelanggan", and "barang"
![](https://drive.google.com/uc?export=view&id=1QnbvmPtuAbYAGYK0yRX6u8u3BH_mUsA1) </br>
![](https://drive.google.com/uc?export=view&id=1VllbixfT4za0ynIHG1VTfMQ6NptA0vJ7) </br>
![](https://drive.google.com/uc?export=view&id=1t_euQLdO-dl6GIWXdvUZMp1MxRM873Bp) </br>
* table_base_2: "penjualan_ds", "pelanggan_ds", and "barang_ds"
![](https://drive.google.com/uc?export=view&id=1e58_Iolbtc4zGnztxR7YFhVZ2MYsEtq4) </br>
![](https://drive.google.com/uc?export=view&id=1HuCN2ayD8VypU836D0QqOBtettwR-ZDz) </br>
![](https://drive.google.com/uc?export=view&id=1BC9OqG82AtoZZOVSxuV_6pMeWHTOjG-y) </br>
* table_aggregate: aggregation columns from 6 tables in dataset
![](https://drive.google.com/uc?export=view&id=1hby_FFpXtABPfpyZxC6nY0F3pvhEe1L4) </br>
![](https://drive.google.com/uc?export=view&id=1t5hylZfgin54pVlnr2A9qf51yt7wPYQ6) </br>

# **Dashboard Modeling**
* I created an interactive dashboard using Google Data Studio and gave explanation for each visualization
* For accessing dashboard, please click on this [link](https://datastudio.google.com/reporting/df102b0f-0a62-4f90-84a0-095c536450d1)
![](https://drive.google.com/uc?export=view&id=1FEKMySmoInIpy4Dq8A5dbf0s0OSwR-qs) </br>
![](https://drive.google.com/uc?export=view&id=1trMEUU6nk_4z98q-APuu_pGN20aS1xHK) </br>

# **Business Recommendation**
* Adding detail sales from March until June 2022 to evaluate the revenue
* Distribution of SLCYL (Salicyl) product lines through Apotek (from dataset, I discovered that SLCYL product lines only available on Klinik/Clinics)
* Evaluation for the lowest sold product quantity in Lampung

Thank you for reading!
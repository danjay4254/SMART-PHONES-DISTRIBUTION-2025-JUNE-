# SMART PHONE ANALYSIS

## TABLE OF CONTENT

 - [Project overview](#project-overview)
 - [Exploratory data analysis](#exploratory-data-analysis)
 - [Recommendation](#recommendation)
   
### PROJECT OVERVIEW

The aim of this data analysis is to show the distribution level of smart phone in the market for the year 2025(June).its show the trend of types of phone brands that are sold more, brands with high storage space ,that support 5G and NFC etc and how its determines the prices.
---

<img width="902" height="498" alt="Screenshot 2025-10-28 140053" src="https://github.com/user-attachments/assets/64215f8c-0c9d-4d54-baf0-433763eb4096" />

### DATA SOURCE

The primary dataset used for this analysis is the "smart phone_dataset.csv" flie, containing detailed information about student depression rate by kaggle.com

### TOOLS

- 	Excel (data cleaning)
- 	SQL (extracting data )
-   Power bi (data visualiazation & report)

### DATA CLEANING/PREPARATION

In the initial data preparation phase, i performed the following:

1.	data loading and inspection
2.	data cleaning and formatting
3.	handling missing values
4.	data extraction

### EXPLORATORY DATA ANALYSIS

EDA involved expoloring the sale data to answer key questions, such as:

-	What is the distribution of storage options (64GB, 128GB, 256GB, etc.), and how does it vary by price range?
-	Which processor brands (Snapdragon, Exynos, MediaTek, Apple A-series) dominate the dataset?
-	How does refresh rate (60Hz, 90Hz, 120Hz, 144Hz) impact user experience and device pricing?
-	How prevalent is 5G support in the dataset, and does it significantly affect device pricing?
-	What percentage of devices have NFC support, and does it effect the price?

  ### DATA EXTRACTION

```SQL
SELECT price,has_5g,has_nfc,processor_brand,internal_memory,refresh_rate,brand_name,ram_capacity FROM danjay.`smart phone analysis.xlsx`;
```
### RESULTS/FINDINGS

-	Phone brand a categorized by storage spaces, some are 64G,128G,228G etc the higher the storage space the higher the price ,the prices varys according to the storages. Phones with larger storage space can take more documents, pictures ,video etc
- Snapdragon is the most dominated brands processor with total sum price of 12 million. Its been used by most brands in the data set.
- The re-fresh rate are categorized by (60Hz, 90Hz, 120Hz, 144Hz)It also has a huge impact on the user in such a way that the higher the re-fresh rate the smoother it runs, phones with re-fresh rate of 64hz tent to run the phones slower with lagging, compared to phomes with 90hz and the rest but don’t actually determine higher phone prices eg the brand with the higher re-fresh rate is xiaomi but Samsung is the highest pricing value phone .
- The 5G network has a huge relevant in the data set , due to the fact that most phone brands are 5G supported with provides better network for communication and brands with 5G network have higher prices compared to 4G and below, making phones that are 5G supported sold more.
- The percentage of smart phones with NFC are over 59.65% in the data set, and this effect the price of the smart phones due to the fact that smart phones with NFC chip have faster connection and paring speed , which makes it more desirable and sold more, despite the price.

### RECOMMENDATION

-	Smart phone brands should produce phones with higher storage space in order to accommodate more material in phones
-	Smart phones brands should produce phones with higher re-fresh rate for smoother running of phones
-	Smart phones brands should produce phones which are 5G supported for easier connection and networking
-	Smart phones brands should produce phones with NFC chips for easier paring speed
-	All the above mention suggestion are aimed are making more profit to the company.

### LIMITATION

i had to fill in the blank ceils with XXXX for accuracy in my analysis

### REFERENCES

- DEEPSEEK AI

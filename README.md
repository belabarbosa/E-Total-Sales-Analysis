# E-Total E-commerce Sales Analysis

![image](https://github.com/user-attachments/assets/7ad07094-9574-443b-a51c-a5059c4bf9e1)


## Overview

This project analyzes historical sales data from **E-Total**, a fictitious e-commerce company located in **Brazil** that has been operating for the past decade. The company is facing a crucial decision regarding its future growth and market positioning. As part of the analysis, we aim to provide insights on the past order numbers, including trends, seasonality, and category performance, to aid the decision-making process.

**This is a follow-along study project from [Comunidade DS](https://comunidadeds.com/)**, where the goal is to learn and apply data analysis techniques to a real-world-like scenario using data analysis tools and methodologies.


### Business Context

**E-Total** was founded 10 years ago by entrepreneur **John**, who saw a significant opportunity to create an online platform offering a wide range of products. Initially, the company faced significant challenges in establishing its online presence and building relationships with suppliers across diverse product categories.

Now, after 10 years of operation, **E-Total** is experiencing a growing competitive environment in the e-commerce industry in **Brazil** and is considering the next steps for expanding its market share. To help with this decision, the company is focused on understanding its historical order trends and product performance.

### Problem Statement

The leadership team at **E-Total** needs to evaluate the performance of past orders to make informed decisions about the company's growth strategy. The key questions include:
- How has the number of orders changed over time?
- Is there seasonality in the orders?
- Which product categories are performing well, and which are not?

The analysis will focus on providing a descriptive, diagnostic, prescriptive, and predictive understanding of the company's sales.

## Descriptive Analysis

### Trend Analysis

![image](https://github.com/user-attachments/assets/424d62ad-c52e-40e0-9d6d-45c71b9ef6cd)


From **January to August 2017**, there was an **upward trend** in the number of orders. However, the same period in **2018** showed a **downward trend**, which is a red flag that warrants further investigation. Despite the dip in 2018, the overall trend remains **upward** over the long term, indicating growth potential for the business.

### Seasonality

A **13-month seasonal cycle** was identified in the order data, with seasonality typically beginning in **February**. This information is crucial for understanding the patterns in demand throughout the year.

### Category Performance

![image](https://github.com/user-attachments/assets/da780dc1-2056-4f66-b3ac-a64e616f9d4d)

The following categories contributed the most to the total number of orders:

#### Categories with over 300 orders:
- **Bedding, Linens, and Bath (Cama, Mesa e Banho)**: 400 orders
- **Beauty and Health (Beleza e Saúde)**: 358 orders
- **Sports and Leisure (Esporte e Lazer)**: 307 orders
- **Furniture and Decoration (Móveis e Decoração)**: 302 orders

#### Categories with 200-300 orders:
- **Computers and Accessories (Informática e Acessórios)**: 282 orders
- **Household Items (Utilidade Doméstica)**: 264 orders
- **Watches and Gifts (Relógios e Presentes)**: 200 orders

#### Categories with very few orders (1 order each):
- **Party Supplies (Artigos de Festa)**
- **Home and Comfort (Casa e Conforto)**
- **Blu-ray DVDs (DVDs Blu-ray)**
- **Sports Fashion (Fashion Esporte)**
- **Le Cuisine**

### Category Share Over Time

![image](https://github.com/user-attachments/assets/00127769-e3a3-4607-a544-c74f00352d9a)

#### Categories that increased their share over the months:
- **Beauty and Health (Beleza e Saúde)**: Increased from 8% in 2017 to 15% in 2018.

#### Categories that maintained a constant share:
- **Bedding, Linens, and Bath (Cama, Mesa e Banho)**: 20% average share
- **Computers and Accessories (Informática e Acessórios)**: 10% average share

#### Categories that decreased their share over time:
- **Furniture and Decoration (Móveis e Decoração)**: Decreased from 35% share in early 2017 to 5% by the end of the year and remained steady in 2018.

### Pareto Principle

![image](https://github.com/user-attachments/assets/d880fb3e-cb18-44f3-b464-ca384dc45daa)


The **top 15 categories** represent **80%** of the total number of orders, and they are:
1. Bedding, Linens, and Bath (Cama, Mesa e Banho)
2. Beauty and Health (Beleza e Saúde)
3. Sports and Leisure (Esporte e Lazer)
4. Furniture and Decoration (Móveis e Decoração)
5. Computers and Accessories (Informática e Acessórios)
6. Household Items (Utilidade Doméstica)
7. Watches and Gifts (Relógios e Presentes)
8. Automotive (Automotivo)
9. Telephony (Telefonia)
10. Garden Tools (Ferramentas de Jardim)
11. Cool Stuff (Cool Stuff)
12. Toys (Brinquedos)
13. Electronics (Eletrônicos)
14. Babies (Bebês)
15. Perfume (Perfumaria)

Additionally, the following breakdown reflects the **Pareto principle** in terms of **orders** and **categories portfolio**:

| Categories | % Orders | % Portfolio |
|------------|----------|-------------|
| 68         | 100%     | 100%        |
| 32         | 95%      | 47%         |
| 21         | 90%      | 31%         |
| 17         | 85%      | 25%         |
| 15         | 81%      | 22%         |


### Regional Insights

![image](https://github.com/user-attachments/assets/ed9bc8ea-1f8f-463b-ac0a-6406e665c578)

- **Customers** are spread across all regions of **Brazil**, with a significant concentration in the **Southeast region**, specifically in **São Paulo**, **Rio de Janeiro**, and **Minas Gerais**.

![image](https://github.com/user-attachments/assets/34bc4699-609f-4305-a5a0-293fcfbaab06)

- **Vendors** are primarily concentrated in the **North region**, especially in the city of **São Paulo**.


## Diagnostic Analysis

### Customers
- In 2017, the number of customers grew by nearly **300%** in the first 8 months.
- In 2018, customer growth declined by **-9%**, and the number of orders also dropped by **-9%**.
- There is a **strong positive correlation (~1.00)** between the number of customers and the number of orders, indicating that a change in customer count directly impacts order volume.

![image](https://github.com/user-attachments/assets/063eb33a-0ffb-4e36-b1a4-540ea81c68cd)


### Sellers
- In 2017, the number of sellers increased by **290%** in the first 8 months.
- In 2018, seller growth declined by **-2%**, while the number of orders dropped by **-9%**.
- In 2017, there was a **strong correlation (0.98)** between orders and sellers. However, in 2018, this correlation weakened to **0.43**, suggesting that the decline in orders was sharper than the decline in sellers.

![image](https://github.com/user-attachments/assets/88d9e2f5-72f9-4f29-8258-ac1fcaf35eaf)


### Unique Products
- In 2017, the number of unique products purchased grew by **300%** in the first 8 months.
- In 2018, the number of unique products purchased declined by **-8%**, while order volume decreased by **-9%**.
- In 2017, there was a **strong correlation (0.98)** between unique products and orders. In 2018, this correlation weakened to **0.90**, indicating that fewer unique products were being sold as orders declined.

![image](https://github.com/user-attachments/assets/479eb6d1-0876-4ec9-96a7-e32ea2eeb8a7)


### Categories
- In 2017, the number of product categories grew by **118%** in the first 8 months.
- In 2018, the number of categories declined by **-14%**, while order volume decreased by **-9%**.
- In 2017, there was a strong correlation between the number of categories and orders. However, in 2018, this correlation dropped significantly (**0.22**), suggesting that customers did not diversify their purchases across different categories as orders declined.

![image](https://github.com/user-attachments/assets/64ffca8c-2e14-481e-985c-4a05712e79ac)


### Average Price
- In 2017, the average price grew by **22%** in the first 8 months.
- In 2018, the average price grew by **17%**, even as the number of orders declined by **-9%**.
- In 2017, there was a **strong correlation (0.99)** between unique products and average price. However, in 2018, this correlation dropped to **0.55**, indicating weaker alignment between product diversity and pricing.

![image](https://github.com/user-attachments/assets/2c8011f4-a6e7-48a5-81ac-763e5db92a8e)


### Correlation Table

|        | 2017 Orders | 2018 Orders |
|--------|------------|------------|
| Customers  | 1.00  | 1.00  |
| Sellers  | 1.00  | 0.43  |
| Products  | 1.00  | 0.90  |
| Categories  | 1.00  | 0.22  |
| Avg Price  | 0.99  | 0.55  |


## Future Analysis

Moving forward, we will use **prescriptive** analysis to suggest actionable steps for improving performance. Finally, a **predictive analysis** will help forecast future sales and order trends.

## Conclusion

This analysis provides a foundational understanding of **E-Total's** past sales performance, identifying key trends, seasonal patterns, and category contributions. This insight will guide the company as it navigates future decisions about growth, product assortment, and regional focus.

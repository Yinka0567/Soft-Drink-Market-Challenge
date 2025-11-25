# Soft-Drink-Market-Challenge
A data analytics project focused on understanding soft-drink availability, stocking trends, and outlet distribution using Power BI.

## Project Overview
This project analyzes soft drink distribution across various outlet types. Using Power BI, the dataset was cleaned, transformed, and visualized through an interactive dashboard to reveal:
- Brand performance
- Outlet stocking patterns
- Stock condition insights
The goal is to provide actionable insights for stakeholders to optimize distribution and inventory management.

## Data Cleaning & Preparation (Power BI)
To begin the analysis, I cleaned and transformed the dataset using Power BI’s Power Query Editor. The following steps were carried out:
1. Data Type Standardization
I reviewed the dataset and updated several columns to the correct data types to ensure consistency and accuracy during analysis.
2. Header Adjustment
The dataset contained an extra top row, which was removed.
After this, I promoted the correct top row to become the column headers.
3. Cleaning the Product Display Field
The Product Display column contained multiple values combined with slashes and brackets.
To make the data uniform and analyzable, I:
- Used Split Column by Delimiter
- Split by slashes (/) and brackets ( )
- Ensured the resulting fields were clean and properly structured
4. Applying Transformations
After completing all transformation steps, I selected Close & Apply to load the cleaned data into Power BI.

## Dashboard Insights

![Soft-Drink-Dashboard](https://github.com/user-attachments/assets/9c2e04f2-cb03-4e56-a3ba-94ee332a072f)

I calculated the totals for all major soft drink brands, including Teem, La Casera, RC Cola, Pepsi, American Cola, Fayrouz, Sprite, Coca-Cola, Bigi, Schweppes, 7Up, and Fanta.
From the dashboard:
- **Coca-Cola** has the highest count at 1,000
- **Pepsi** follows with 977
- **Fanta** comes next with 925
- **Fayrouz** is the lowest with 30
Insight: Coca-Cola, Pepsi, and Fanta dominate the market, while Fayrouz has the lowest presence.

### Outlet Distribution
I used a bar chart to analyze which outlet types distribute more soft drinks:
- **Shops** have the highest count with 1,289 
- **Hawking** follows with 48
- **Restaurants** have the lowest count with 12
Conclusion: Shops are the dominant distribution point for soft drinks

### Slicer Analyses
I created two slicers in the dashboard. The first slicer focuses on Stock Condition.

#### Stock Condition Slicer
The Stock Condition slicer reveals how well different soft drink brands are stocked across outlets.
Overall insights:

1. **Almost Empty**

![Almost Empty](https://github.com/user-attachments/assets/c8e8ab37-8376-4c24-8df3-bbe042b64049)

- Popular brands like Pepsi (121), Coca-Cola (117), and Fanta (111) appear frequently in the “Almost Empty” category.
- Shops (192) have the highest number of almost-empty products.
- **Insight**: High demand could be causing frequent low stock levels for major brands.

2. **Not Applicable**

![Not Applicable](https://github.com/user-attachments/assets/fe804fb3-9f04-466e-8685-e5ca386f5382)

- Very few products fall here, mostly Pepsi, Fanta, 7Up, American Cola.
- Others (16) is the most represented outlet.
- **Insight**: These items may not be displayed or tracked in certain outlets.

3. **Out of Stock**

![Out of Stock](https://github.com/user-attachments/assets/9c49cd24-ded5-4007-9309-afbacb211b46)

- Out-of-stock numbers are low but still significant for Coca-Cola, Pepsi, and 7Up.
- Shops (12) show the most frequent stockouts.
- **Insight**: Shops face stock pressure due to high foot traffic and product turnover.

4. **Partially Stocked**

![Partially Stocked](https://github.com/user-attachments/assets/488c1ce7-7927-485a-a4d6-572ece745339)

This is the most common category across all products.
- Pepsi (404) and Coca-Cola (429) have the highest partially stocked counts.
- Shops (579) dominate this category.
- **Insight**: Many outlets are able to keep products available, but not fully stocked, showing inconsistent supply.

5. **Well Stocked**

![Well Stocked](https://github.com/user-attachments/assets/67b396dc-a7c1-466c-8cad-49d55dbfba88)

- Nearly all major brands have strong representation in this category.
- Highest counts include Coca-Cola (473), Pepsi (443), and Fanta (422).
- Again, Shops (506) lead in well-stocked items.
- **Insight**: Shops maintain the most stable stock levels when compared to other outlets.

##### **Overall Stock Condition Conclusion**
Shops are consistently the highest across all stock categories (almost empty, partially stocked, and well stocked).
This confirms that shops are the primary distribution hubs and handle the highest product volume. Coca-Cola, Pepsi, and Fanta maintain strong availability but also experience demand-driven stock fluctuations.

#### Slicer 2: Outlet Count Analysis
The Outlet Count slicer highlights which products are most common in each outlet type.

1. **Hawking**

![Hawking](https://github.com/user-attachments/assets/80782afe-e3ab-4992-8182-096a58085ec0)

- Fanta, Coca-Cola, and American Cola are heavily sold by hawkers.
- Fayrouz is the least hawked.
- Conclusion: Hawkers focus on fast-moving, popular brands.

2. **Kiosk**

![Kiosk](https://github.com/user-attachments/assets/915eec7c-34f7-4caa-91ec-f9a4cf4be6fd)

- Pepsi (44) and Fanta (44) are the top products.
- Fayrouz (1) appears minimally.
- Conclusion: Kiosks favor high-demand, affordable brands.

3. **Open Market Stall**

![Open  Market](https://github.com/user-attachments/assets/941c0360-9413-4362-bc37-d3615fad118e)

- Coca-Cola (22) leads.
- Conclusion: Open markets sell many top mainstream brands but in lower volume compared to shops.

4. **Others**

![Others](https://github.com/user-attachments/assets/ce35a712-f3a3-4986-9f3c-a89ce3cc6874)

- American Cola (15) is highest.
- Conclusion: These outlets may have less structured beverage inventories.

5. **Restaurant/Bar**

![Restaurant](https://github.com/user-attachments/assets/53e391fb-9d29-4663-8b4d-eae428bcb8a2)

- Fanta (11) is surprisingly the most popular.
- Conclusion: Restaurants/bar consumption patterns differ from general retail trends.

6. **Shop**

![Shop](https://github.com/user-attachments/assets/d50f8d97-41b4-46c3-911d-47ea0043fec0)

- Dominant product counts:
  - Coca-Cola: 892
  - Pepsi: 842
  - Fanta: 787
- Conclusion: Shops are the primary retail channel for soft drinks and carry the highest

7. **Supermarket**

![Supermarket](https://github.com/user-attachments/assets/26b3baa4-96c8-46a1-91b8-dc55d8f25301)

- Coca-Cola leads again with 23.
- Conclusion: Supermarkets stock soft drinks but at lower volumes compared to shops.

##### Overall Outlet Count Conclusion
Shops are the major contributors to soft drink distribution, with the highest counts for every major brand. Hawking and kiosks also play important roles in informal distribution, especially for high-demand products. Fayrouz consistently appears as the least stocked product across most outlet types.

#### Conclusion
- Shops are the dominant outlet type and carry the largest volumes for every major soft drink brand.
- Popular brands like Coca-Cola, Pepsi, and Fanta maintain high availability but are subject to demand-driven stock fluctuations.
- Informal distribution channels (hawking, kiosks) complement the formal retail sector, especially for fast-moving products.
- Fayrouz and other niche brands have minimal presence and require targeted distribution strategies.



# Energy Drink & Cognitive Performance Analysis

This project analyses how different quantities of an energy drink called Red Berry boost had an  affect
students’ cognitive performance using a memory-based test.

The analysis is based on original IB Mathematics SL research and was expanded
into a full data analytics workflow using SQL, Excel, and Tableau.

## Tools Used
- PostgreSQL (SQL)
- Excel
- Tableau

## Key Finding
Moderate consumption (≈200 ml) resulted in the highest cognitive improvement,
while higher intake (300 ml) reduced performance.
<img width="1169" height="753" alt="image" src="https://github.com/user-attachments/assets/610fbf4d-3be8-42f7-94b8-535f0bc16ef9" />
When I first started working on my Red Berry Boost project , I mirrored numerous complications
due to DBeaver not showing any of my tables and my queries were simply returning the
database name. After looking into it, I discovered that the problem was that I wasn't connected
to the right datasource for my project and had several open PostgreSQL connections. I
discovered that I was in the incorrect database when I used SELECT current_database(); to
verify this. After that, I changed my session to the redberry_project database and updated the
schema. All of my tables displayed once the connection was made correctly, allowing me to finish the SQL analysis both accurately and effectively.
View full project here: : https://drive.google.com/file/d/1miiZrIOIhwuWJ2KJeRC1f-nfCN0u9eRh/view?usp=share_link



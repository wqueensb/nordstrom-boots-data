# nordstrom-boots-data
Obtained data from Kaggle.com on the boots sold by Nordstrom. Being a lover of fashion I decided to explore this dataset by using SQL to obtain the information I was interested in. 

[ Boots over a $100](https://github.com/wqueensb/nordstrom-boots-data/blob/main/boots_over_%24100)

Wanted to find out how many boots sold by Nordstrom are over a $100. The information I found was interesting because it affirmed Nordstrom's position in the shoe luxury space. 

[ SQL query to arrange Nordstrom boot table in descending order. ](https://github.com/wqueensb/nordstrom-boots-data/blob/b45bc5cf0760f1dfa334d6f052a883be25c1d256/descending_order_by%20retail%20price%20query)

I needed to quickly find the most expensive boot brand sold by Nordstrom so I organized the table in descending order. Also, I wanted my integers converted to a currency format.  

[ Doc Martens ](https://github.com/wqueensb/nordstrom-boots-data/blob/main/dr_martens_styles)[Untitled spreadsheet - Dr_Martens_Styles .csv](https://github.com/wqueensb/nordstrom-boots-data/files/8924136/Untitled.spreadsheet.-.Dr_Martens_Styles.csv)


One of my favorite styles is the iconic Dr. Martens created in 1947. So I decided to create a query that would let me know the different Dr. Marten styles sold by Nordstrom.

[Boots with a review rating greater than 4.0](https://github.com/wqueensb/nordstrom-boots-data/commit/ecd7e9ac16b10fb7e2e53e9f33d7b05745a40728)

Nordstrom sells a lot of boots so I was interested in the ones that were appreciated by their customers. I selected the boots that had a rating of 4 or more and arranged the table in descending order. 

[Boots with a retail price higher than the average cost](https://github.com/wqueensb/nordstrom-boots-data/commit/718ed5d33aa582779dcd50ac3b3599fba99b4fe1)

To get this answer I created a CTE(Common Table Expression) to find out the average cost and compared this cost to the retail price of every boot in the table. I decided to create a CTE instead of using a subquery because it would be much easier to read and to be used again. The average retail cost is $312.77 ea.



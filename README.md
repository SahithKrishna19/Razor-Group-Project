# Razor-Group-Project


The task is to sanitize and analyze the data to profile the sellers present and develop selection criteria to identify the best or most promising sellers in this dataset.

Worked with pandas and regex.

Used pandas to parse and sanitize the data. from the excel file.
Used regex to find the patterns in the task

Task Hints:
I	The column sellerproductcount gives you the count of products in the form '1-16 of over 100,000 results' , and you can parse out the product count 100,000 .
II	sellerratings - this columns gives you the % and count of positive ratings (e.g. 88% positive in the last 12 months (118 ratings) ) if parsed correctly
III sellerdetails - you can use this text to parse out phone numbers, and email IDs of merchants, where available, so our team can reach out to them.
IV businessaddress - this will give you the business locations of the sellers. You can parse them to identify if a seller is registered in the US , Germany (DE), or        China (CN). Note that Razor does not acquire Chinese sellers at this point, so you can use this data to exclude sellers in China from your analysis.
V Hero Product 1 #ratings and Hero Product 2 #ratings - these 2 columns give you the number of ratings of the 2 'hero products' or best selling products of this seller.

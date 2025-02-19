# H&M Sales Analysis - Tableau Dashboard

## 📊 Overview
This Tableau dashboard provides insights into **H&M sales data**, focusing on various dimensions such as monthly sales trends, product types, customer demographics, and pricing patterns. The dashboard helps in understanding:
- Sales trends over time 📈
- Customer purchasing behavior 🛍️
- Product performance across different categories 🏷️
- Pricing impact on sales 💰

## 🔍 Key Features
The dashboard consists of several key visualizations:

1️⃣ **Month-wise Sales Trends** 
   - Analyzes total sales per month to identify seasonal trends.  

2️⃣ **Month-wise Average Price Analysis**   
   - Compares the average price of articles sold each month.  

3️⃣ **Product Type-wise Sales Distribution** 
   - Highlights which product types generate the most sales.  

4️⃣ **Customer Age-wise Sales Trends** 
   - Examines purchasing behavior across different age groups.  

5️⃣ **Appearance-wise Sales Analysis** 
   - Analyzes sales by `article_graphical_appearance_name`, `article_colour_group_name`, etc.  

6️⃣ **Price-wise Sales Distribution**   
   - Shows how different price ranges contribute to total sales.  

## 📂 Dataset Used
The dataset contains:
- **Transactional records** (`t_dat`, `article_id`, `customer_id`, `price`)**  
- **Article details** (`article_id`,`product_type_name`,`colour_group_name`,`garment_group_name`, etc.)  
- **Customer demographics** (`customer_id`, `customer_age`, etc.)

## 📷 Dashboard Preview

<div class='tableauPlaceholder' id='viz1739944803092' style='position: relative'> <noscript> <a href='#'><img alt='H&amp;M 2018-20 Sales Report ' src='https://public.tableau.com/static/images/HM/HM2018-20SalesReport/Dashboard1/1_rss.png' style='border: none' /></a> </noscript> <object class='tableauViz' style='display:none;'> <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /> <param name='name' value='HM2018-20SalesReport/Dashboard1' /> <param name='tabs' value='no' /> <param name='toolbar' value='yes' /> <param name='static_image' value='https://public.tableau.com/static/images/HM/HM2018-20SalesReport/Dashboard1/1.png' /> <param name='animate_transition' value='yes' /> <param name='display_static_image' value='yes' /> <param name='display_spinner' value='yes' /> <param name='display_overlay' value='yes' /> <param name='display_count' value='yes' /> <param name='language' value='en-US' /> </object> </div> <script type='text/javascript'> var divElement = document.getElementById('viz1739944803092'); var vizElement = divElement.getElementsByTagName('object')[0]; vizElement.style.minWidth='420px'; vizElement.style.maxWidth='100%'; vizElement.style.minHeight='587px'; vizElement.style.maxHeight=(divElement.offsetWidth*0.75)+'px'; var scriptElement = document.createElement('script'); scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; vizElement.parentNode.insertBefore(scriptElement, vizElement); </script>

## 📌 Conclusion
This dashboard provides **actionable insights** into H&M’s sales patterns, helping in decision-making for marketing strategies, product placements, and pricing optimizations.

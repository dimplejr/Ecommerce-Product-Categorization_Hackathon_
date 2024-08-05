# Ecommerce-Product-Categorization_Hackathon_
Develop a multi-class text classifier that categorizes products with maximum accuracy based on the given description.
Steps taken:
1. Data Exploration and Preparation:
2. Perform descriptive analysis to identify data patterns, category distributions, and inconsistencies, especially for text data
3. Feature Engineering/Text to Features
4. Design and develop machine learning models using text data for accurate product categorization.
5. Evaluate and compare models using metrics such as accuracy, F1 score, precision, and recall.
6. Develop models that support scalable, real-time categorization.


Here's a detailed description for each column name:

1. uniq_id: 
   - Description: A unique identifier for each product.
   - Purpose: Acts as the primary key to distinguish each product record uniquely.

2. crawl_timestamp: 
   - Description: The timestamp when the product data was last scraped or collected.
   - Purpose: Helps identify the data's recency and track changes over time.

3. product_url: 
   - Description: The URL linking directly to the product's page on the eCommerce platform.
   - Purpose: Allows direct access to the product's information and purchasing page.

4. product_name: 
   - Description: The name or title of the product as displayed on the eCommerce platform.
   - Purpose: Provides a searchable and readable identification of the product.

5. product_category_tree: 
   - Description: The hierarchical structure representing the product's category on the platform.
   - Purpose: Useful for categorization, analysis, and filtering of products.

6. pid: 
   - Description: A unique identifier specific to the eCommerce platform for each product.
   - Purpose: Used to reference products internally on the platform.

7. retail_price: 
   - Description: The original or retail price of the product before any discounts.
   - Purpose: Helps understand the product's standard market value.

8. discounted_price: 
   - Description: The price of the product after applying any discounts or offers.
   - Purpose: Reflects the final price a customer would pay.

g if the product is part of Advantage program.
    - Purpose: Denotes if the product has additional benefits like faster delivery or special quality checks.

11. description: 
    - Description: Detailed information about the product, including features, specifications, and usage.
    - Purpose: Helps customers understand the product's value proposition and unique selling points.

12. product_rating: 
    - Description: The product's overall rating on the platform, based on customer reviews.
    - Purpose: Indicates customer satisfaction and product quality.

13. overall_rating: 
    - Description: The aggregate rating of the product across different platforms or periods.
    - Purpose: Offers a comprehensive view of the product's reception.

14. brand: 
    - Description: The name of the brand or manufacturer of the product.
    - Purpose: Assists in brand-based analysis and filtering.

15. product_specifications: 
    - Description: Detailed specifications of the product, often in JSON or structured format.
    - Purpose: Provides technical and functional details to aid customer decision-making

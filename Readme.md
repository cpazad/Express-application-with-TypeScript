**Objective:** Develop a Express application with TypeScript as the programming language, integrating MongoDB with Mongoose for effective data management. Ensure data integrity through validation using Joi/Zod.

## Set up the Project
    Create a new Express project.
    Set up a MongoDB database using Mongoose for storing product and order data.

## Define Data Models
Create Mongoose models for Product data based on the provided data structure. (You can follow sample-data.json file for ideas).
Define appropriate data types, validations.

## E-commerce Product Data Types
- name (string):
  - The name of the product.
- description (string):
 - A brief description of the product.
- price (number):
  - The price of the product.
- category (string):
  - The category to which the product belongs.
- tags (array of strings):
  - An array of tags or keywords associated with the product.
- variants (array of objects):
  - An array containing different variants or options of the product, such as size, color, or style.
- type (string): The type of variant (e.g., size, color).
  - value (string): The specific value of the variant (e.g., "Small", "Red").
- inventory (object):
  - An object representing the product's inventory details.
- quantity (number): The available quantity of the product in stock.
  - inStock (boolean): Indicates whether the product is currently in stock.
# MRM Brand .Net excercise

MRM deals with many companies and handles a lot of product data.

Your job will be to build a very simple product database API.

In this repository you will find a JSON file: `product.json` with some product data. Each product will have the following fields:

```js
{
  "name": "XXXXX",
  "description": "XXXX",
  "category": "XXXX"
}
```

You will need to perform the following tasks:

1. Create an ASP.Net application that uses the Entity Framework with code first migrations and a seed method that loads the products. 
2. Create API endpoints that support the following operations:
   1. Retrieve all products
   2. Retrieve a list of categories
   3. Retrieve the products for a category
   4. Creation of a new product (and if necessary the category for that product)
   5. Deletion of a product
  
This guide can be used for troubleshooting: https://docs.microsoft.com/en-us/aspnet/web-api/overview/data/using-web-api-with-entity-framework/part-1

You should be looking to demonstrate the following:

* an understanding of the entity framework
* code first migrations
* seeding the database
* API design
* application architecture and best practices
* unit testing

This project is intended to be a creative exercise so the structure of the data stored in the database and the organisation of the APIs is left as a design decision for you. **Timebox yourself to just a few hours at most** - it's alright if you don't finish everything 100%. The main purpose of the project is to talk about it afterwards!

# e-Commerce Back End
## Description
The purpose of this application is to access a retailers inventory and update it if necessary. This app gives the user the ability to look at all tags, categories, and products. When looking at the tags you see the product_id and ta_id which connects the tag item to the associated product and category. The user will see the same thing when clicking on the GET products. This connects all of the items in inventory so that their price, stock, and category can be viewed. The user can also search for a product, tag, or category by ID for a more condensed search result. The user can slo create a new tag, product or category if new items are added to the inventory. There is also a update function so that if prices change or an item changes, they can update the inventory to reflect that. There is also the delete functionality so if the company deides not to stock an item anymore they can delete, the product, tag, or category. This program utilizes mysql, inquirer, express, sequelize, and dotenv.
## Installation
To run this application you will need to first clone the code from this repository, then navigate to the correct directory, and then run `npm install` in your terminal. You must then run mysql -uroot to get access to the database with the information. Once there run `source db/schema.sql` and then `exit`. After that run npm run seed and then the information will be accessible on your server.
## Usage
Once the npm package has been installed, type `node server` in the terminal and you will be presented with a home menu of options to view, add, or update the database.

[Click here](./images/walkthrough.mp4) for a video walkthrough.

### Resources
[Github Repo](https://github.com/cdgonzo23/e-commerce-back-end)
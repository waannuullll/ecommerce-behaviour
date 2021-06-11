# ecommerce-behaviour
Exploratory data analysis using big data (~14 GB data) about e-commerce activity and predict if user will buy the item using XGBoost.

## About
This file contaisn behavior data for 7 months (from October 2019 to April 2020) from a large multi-category online store.

Each row in the file represents an event. All events are related to products and users. Each event is like many-to-many relation between products and users.

Data collected by [Open CDP project](https://rees46.com/en/open-cdp). Feel free to use open source customer data platform. Source: [kaggle](https://www.kaggle.com/mkechinov/ecommerce-behavior-data-from-multi-category-store).

## How to Read It
User <code>userid</code> during session <code>usersession</code> added to shopping cart (property eventtype is equal cart) product <code>productid</code> of brand brand of category <code>categorycode</code> (categorycode) with price price at <code>event_time</code>.

## Event Types
* <code>view</code> - a user viewed a product
* <code>cart</code> - a user added a product to shopping cart
* <code>remove_from_cart</code> - a user removed a product from shopping cart
* <code>purchase</code> - a user purchased a product

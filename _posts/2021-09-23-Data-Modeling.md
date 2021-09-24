---
layout: post
title: "Data Modeling"
date: 2021-09-23 2:33:13 -0500
author: Rhett Booher
---
For Lab 5, I had to make several assumptions to convert the scenario into a data model.

<img src="{{site.baseurl}}/assets/Grocery Store.png" alt="drawing" width="500"/>

For the ER Diagram, I set the owner/store, the customers, and the store's items as entities. I made the assumptions that there should be one owner and at least one customer. The owner lists multiple items for sale. The customer could select multiple, or none, of these items.
<img src="{{site.baseurl}}/assets/Grocery_Store-2021-09-23_11-36.png" alt="drawing" width="500"/>

For the SQL schema, I created tables for all the entities and relationships adding the attributes as columns and creating primary keys for each table. To the selection table I added reservation information: date/time of pickup, desired quantity, and special instructions.


I'm mostly satisfied with these data models. However, there could be some complications. Specifically with item substitutions and in the event that an item is out of stock.

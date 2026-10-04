Entity Relationship Diagram-ERD:
This repository has the Entity Relationship Diagram (ERD) I designed for the WitleShop Online Retail System. The diagram was drawn in draw.io.

The diagram is in the file Witle ER Diagram.drawio.pdf OR CLICK THE LINK https://drive.google.com/file/d/15lcqV9LOO6-Ml5PcnxvjV5MWBs0mF_SV/view?usp=drive_link

The entities are Customer, Address, Order, Product, Category, Supplier, Payment and Delivery.

Each entity has a primary key (PK). I used foreign keys (FK) to link the entities. For example, Order has Customer_ID so you can see which customer placed the order.

Relationships:

- A customer can have many addresses (1:M)
- A customer can place many orders (1:M)
- A category can have many products (1:M)
- A supplier can supply many products (1:M)
- An order has one payment (1:1)
- An order has one delivery (1:1)
- A delivery goes to one of the customer's addresses (1:M)
- An order can have many products and a product can be in many orders (M:N)

In the diagram, a single line means "one" and the small circle with three lines means "many".

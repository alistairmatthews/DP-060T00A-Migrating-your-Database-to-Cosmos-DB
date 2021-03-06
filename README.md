# Migrating your Database to Cosmos DB

This repository contains the lab documents and source code for the exercises for the workshop **Migrating your Database to Cosmos DB**

## Lab 2: Migrate MongoDB to Cosmos DB

In this lab, you'll take an existing MongoDB database and migrate it to Cosmos DB. You'll use the Azure Database Migration Service. You'll also see how to reconfigure existing applications that use the MongoDB database to connect to the Cosmos DB database instead.

The lab is based around an example system that captures temperature data from a series of IoT devices. The temperatures are logged in a MongoDB database, together with a timestamp. Each device has a unique ID. You will run a MongoDB application that simulates these devices and stores the data in the database. You will also use a second application that enables a user to query statistical information about each device. After migrating the database from MongoDB to Cosmos DB, you'll configure both applications to connect to Cosmos DB, and verify that they still function correctly.

## Lab 3: Migrate Cassandra to Cosmos DB

In this lab, you'll migrate two datasets from Cassandra to Cosmos DB. You'll move the data in two ways. First, you'll export the data from Cassandra and use the CQLSH COPY command to import the database into Cosmos DB. Then, you'll migrate the data using Spark. You'll verify that migration was successful by running an application that queries data held in the original Cassandra database, and then reconfiguring the application to connect to Cosmos DB. The results of running the reconfigured application should remain the same.

The scenario for this lab concerns an ecommerce system. Customers can place orders for goods. The customer and order details are recorded in a Cassandra database. You have an application that generates summaries, such as the list of orders for a customer, the orders for a specific product, and various aggregations, such as the number of orders placed, and so on.

Both labs run using the Azure Cloud shell and the Azure portal.

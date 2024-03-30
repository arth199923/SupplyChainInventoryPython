# SupplyChainInventoryPython

# Sales Shipment and Inventory Management Case Study

## Introduction

This repository contains a case study related to sales shipment and inventory management. The dataset includes two main components: sales shipment data and inventory stock data. The objective of this case study is to analyze the provided data, perform data preparation, conduct various analyses, create visualizations, and build predictive models to derive insights for effective supply chain and inventory management.

## Dataset Description

### Sales Shipment Data

#### Fields:
- **Product Category Id**: Product category code
- **Category Name**: Description of the product category
- **Class**: Product Segment or Class or Cluster
- **Customer City**: City where the customer made the purchase
- **Customer Country**: Country where the customer made the purchase
- **Customer Fname**: Customer name
- **Customer Id**: Customer ID
- **Customer Lname**: Customer lastname
- **Customer Segment**: Types of Customers: Consumer, Corporate, Home Office
- **Customer State**: State to which the store where the purchase is registered belongs
- **Customer Street**: Customer Street
- **Customer Zipcode**: Customer Zipcode
- **Delivery Status**: Delivery status of orders: Advance shipping, Late delivery, Shipping canceled, Shipping on time
- **Department Id**: Department code of store
- **Department Name**: Department name of store
- **Market**: Market to where the order is delivered: Africa, Europe, LATAM, Pacific Asia, USCA
- **Order City**: Destination city of the order
- **Order Country**: Destination country of the order
- **Order Date**: Date on which the order is made
- **Order Id**: Order code
- **Order Region**: Region of the world where the order is delivered
- **Order State**: State of the region where the order is delivered
- **Order Status**: Order Status
- **Product Id**: Product code
- **Product Name**: Product Name
- **Shipping Date**: Shipping Date
- **Shipping Mode**: Shipping Mode
- **Type**: Type of transaction made
- **Benefit per order**: Earnings per order placed
- **Days for shipment (scheduled)**: Days of scheduled delivery of the purchased product
- **Days for shipping (real)**: Days of actual delivery of the purchased product
- **Latitude**: Latitude corresponding to the location of the store
- **Longitude**: Longitude corresponding to the location of the store
- **Order Customer Id**: Customer order code
- **Order Item Cardprod Id**: Product code generated through the RFID reader
- **Order Item Discount**: Order item discount value
- **Order Item Discount Rate**: Order item discount Rate
- **Order Item Id**: Order item code
- **Order Item Product Price**: Order Item Product Price
- **Order Item Profit Ratio**: Order Item Profit Ratio
- **Order Item Quantity**: Number of products per order
- **Order Item Total**: Total value of order items
- **Order Profit Per Order**: Order Profit Per Order
- **Product Price**: Product Price
- **Sales**: Value in sales
- **Sales per customer**: Total sales per customer made per customer

### Inventory Stock Data

#### Fields:
- **Order-Now**: Flag indicating whether the product needs to be ordered or not
- **Product ID**: Unique Product ID
- **Product Name**: Product Name
- **Avg Lead Time**: Average number of days taken for delivery of items from suppliers
- **Avg Order Qty**: Average number of items ordered each time
- **Current Stock**: Current stock (Inventory)
- **Max Lead Time**: Maximum number of days taken for delivery of items from suppliers
- **Max Order Qty**: Maximum number of items ordered each time
- **MOD**: Manufacturing on demand
- **Reorder Point**: Inventory level at which items should be ordered
- **Safety Stock**: Minimum stock to be maintained to avoid out-of-stock issues

## Business Objective

The main objective of this case study is to analyze the provided data and derive insights for effective supply chain and inventory management. The tasks include data audit, data preparation, various analyses, visualization creation, and predictive modeling.

## List of Tasks or Business Questions (using Python)

### 1. Data Audit
- Calculate various metrics such as the number of rows and columns, numerical and categorical columns, and identify any data-related issues.
- Perform detailed exploratory data analysis (EDA) including univariate and bivariate analysis for each variable.

### 2. Data Preparation
- Create new flag variable for late delivery risk.
- Rename variables as per Python naming conventions.
- Convert variable data types as per descriptions.
- Impute missing values.
- Perform other data preparation steps as required.

### 3. List of Analyses
- Calculate high-level metrics such as total sale value, inventory value, profit value, etc.
- Analyze the status of orders and delivery.
- Analyze late delivery risk and order item quantity by time.
- Analyze sales units/value, profit orders/value, and order count by various dimensions.
- Analyze inventory units and value by class or cluster.
- Perform additional analyses as required.

### 4. Create Visualizations
- Replicate provided sample reports and metrics.
- Create additional visualizations beyond the sample reports.

### 5. Predictive Modeling
- Build predictive models to predict sales at the customer level.
- Prepare end-to-end code with proper comments.
- Derive insights from the models.

## Repository Structure

- **Data**: Contains the provided datasets.
- **Notebooks**: Contains Jupyter notebooks for data analysis, data preparation, analyses, visualizations, and predictive modeling.
- **Reports**: Contains sample reports and metrics.
- **Visualizations**: Contains visualizations created during the analysis.

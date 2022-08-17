# **SAP Product Footprint Management**

## **Introduction**

The SAP Product Footprint Management solution helps you calculate carbon footprints for your purchased and manufactured products at scale. The examples provided on SAP Samples are intended to help you get an overview of the solution by taking you through the data import and calculation processes. The data files and APIs in this GitHub repository are loaded with example data based on the manufacturing of a product called Cookie.

Our actual APIs are provided on [SAP API Business Hub](https://api.sap.com/package/SAPProductFootprintManagement/all). 

---
**Note: Before you start with the process described below, ensure that you clone this repository or download a .zip file of it so you have all the files you need at hand.**

## **Calculating Footprints**

### **Importing Data**
The first step in calculating your footprints through the SAP Product Footprint Management solution is importing your data. View the links below for the Postman collections that will help you do this.
- [Import SAP S4/HANA Data into SAP Product Footprint Management](./import%20data/)
- [Import Emission Factors into SAP Product Footprint Management](./import%20emission%20factors/)

### **Starting a Calculation Run for Purchased Products**

First, you must calculate footprints for your purchased products. To do this, follow the steps described in [Purchased Product Footprints](./purchased%20product%20footprints/). As a part of this, you will also map purchased products with their emission factors.

### **Starting a Calculation Run - Manufactured Products**
You can perform these steps once the footprint calculation for your purchased products are done. After this is done, follow the steps described in [Manufactured Product Footprints](./manufactured%20product%20footprints/).

### **Viewing Footprint Calculation Results**
After you finish calculating your footprints, you can view the results in the **Monitor Footprints** application. For more information, see [View Footprints](./view%20footprints/).

## License
Copyright (c) 2022 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSE) file.

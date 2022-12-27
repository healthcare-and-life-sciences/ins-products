
# A-HLS Payer Sample Product Documentation 



## Overview

Creating health insurance products is a complex and time consuming task. To save developers time, this project provides sample Insurance products can be used in building your own health insurance solution 

**Goal**


* Create a list of Health Insurance products to cover Medicare, Small Group, and Individual insurance needs.
* Keep the JSON property names the same to make mapping easy into Flex-cards.



**Health Insurance Solutions**

The products data pack you import are just data with no functions attached to it. If you want to see how to attach pricing engine or display the data, please look at other projects from the HLS Accelerate Team that shows how to use the products data.

1. [Product Grid](https://github.com/healthcare-and-life-sciences/ins-products-grid)
2. [Small Group Quoting](https://github.com/healthcare-and-life-sciences/small-group-quoting)


**Datapacks Design**

The filename of the data pack will match the product code of the Insurance product

Product code will start with a ##-###-*

The first part is Market Segment.


* SG - Small Group
* LG - Large Group
* IN - Individual
* ME - Medicare


The second part is the Type.


* MED - Medical
* DNT - Dental
* VIS - Vision


Data packs may contain one or more products. If it includes a single product, you will find the full naming (Eg: SG-MED-HMO-25). If it has multiple products in a single data pack, you will find it like SG-VIS ...this contains all Small Group Vision plans



* * *

## Business Objective

Develop a sample set of insurance products

## Business Value and Benefits

* Save time by starting with existing insurance products

* * *

## Industry Focus and Workflow

### Primary Industry:

* Health Insurance

### Primary User Persona:

* Insurance product developer

* * *

## Package Includes:

### **DataPacks **

* A complete list can be found at https://github.com/healthcare-and-life-sciences/ins-products


* * *

## Configuration Requirements

### Pre-Install Configuration Steps:

Make sure vlocity insurance (vlocity_ins) is installed. 


#### Install the Data Pack

1. The Data Pack folder in the following GitHub repository https://github.com/healthcare-and-life-sciences/ins-products contains product Data Pack. Please download the Data Packs you need (See the file naming and how they match products above) and save them to your desktop: 
2. Then, complete the following steps to import them into your Salesforce org.
    1. To Import, in your destination Salesforce org, Click on **App Launcher** → Search for '**OmniStudio DataPacks**' and click on it.
    2. Click on '**Installed**' and on the right side click on '**Import from**'.
    3. Select '**From File**' - When the window opens, select the Data Pack file you downloaded and stored on your machine. Click '**Install**'.
3. More about DataRaptors: https://trailhead.salesforce.com/content/learn/modules/omnistudio-dataraptors



* * *

## Assumptions

1. A customer has licenses for HINS Managed (vlocity_ins) Package with OmniStudio. These solutions have all been installed and are functional.
2. A customer is assuming Salesforce Lightning Experience — not Classic.
3. Data Model elements that are part of the HINS (Vlocity) Managed package are all available.
4. The Accelerator uses the Lightning Design System standards and look. Customers may want to apply their own branding, which can be achieved.
5. Insurance Product modeling is a complex topic. If you are planing on taking these sample datapacks and modfying to suite your own business requriments please read these documents. 

[What is small-group health insurance?](https://www.healthinsurance.org/glossary/small-group-health-insurance/)

[What are metal plans?](https://www.healthinsurance.org/glossary/metal-plans/)

[Salesforce Product Modeling Specification](https://help.salesforce.com/s/articleView?id=ind.insurance_insurance_product_modeling_specifications_603842.htm&type=5)

[Salesforce Product data structure](https://help.salesforce.com/s/articleView?id=ind.insurance_product_json_structure_model_609451.htm&type=5)


* * *

## Revision History

* **Revision Short Description (Dec 23, 2022)**
* Initial deployment for Small Group


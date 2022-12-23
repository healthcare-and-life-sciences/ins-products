# ins-products


# A-HLS Payer Sample Product Documentation 

* * *

## A-HLS Payer Sample Product Documentation

*A list of Health Insurance products* 

## Overview

A list of health insurance products. Each product is in its data packet. They can be found at https://github.com/healthcare-and-life-sciences/ins-products

**Goal**


* Create a list of Health Insurance products to cover Medicare, Small Group, and Individual insurance needs. 
* Keep the JSON property names the same to make mapping easy into Flexcards.
* The returned JSON will be simple compared to how it saved in SF (https://help.salesforce.com/s/articleView?id=ind.insurance_product_json_structure_model_609451.htm&type=5)


**Reference Links - External)**

https://www.healthinsurance.org/glossary/small-group-health-insurance/
https://www.healthinsurance.org/glossary/metal-plans/


Reference Links - Salesforce


https://help.salesforce.com/s/articleView?id=ind.insurance_insurance_product_modeling_specifications_603842.htm&type=5

**Product code**

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


Data packs may contain one or more products. If it includes a single product, you will find the full naming (Eg: SG-MED-HMO-25). If it has multiple products in a single data pack, you will find it like SG-VIS



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

Make sure vlocity insurance is installed. 


#### Install the Data Pack

1. The Data Pack folder in the following GitHub repository contains one (1) DPA Data Pack. Please download the Data Pack and save them to your desktop: https://github.com/healthcare-and-life-sciences/ins-products
2. Then, complete the following steps to import them into your Salesforce org.
    1. To Import, in your destination Salesforce org, Click on **App Launcher** → Search for '**OmniStudio DataPacks**' and click on it.
    2. Click on '**Installed**' and on the right side click on '**Import from**'.
    3. Select '**From File**' - When the window opens, select the Data Pack file you downloaded and stored on your machine. Click '**Install**'.
3. More about DataRaptors: https://trailhead.salesforce.com/content/learn/modules/omnistudio-dataraptors

### Post-Install Configuration Steps:


The pricing part will be empty, and you must add them once you import them.

1. [Image: Pricing.png]

* * *

## Assumptions

1. A customer has licenses for Health Cloud, and the HINS Managed Package with OmniStudio. These solutions have all been installed and are functional.
2. A customer is assuming Salesforce Lightning Experience — not Classic.
3. Data Model elements that are part of the HINS (Vlocity) Managed package and Health Cloud are all available.
4. The Accelerator uses the Lightning Design System standards and look. Customers may want to apply their own branding, which can be achieved.

* * *

## Revision History

* **Revision Short Description (Month Day, Year)**

    * Add
    * Add

* * *

## Internal Only Information

* The QA document can be found at 
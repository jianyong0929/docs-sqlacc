---
sidebar_position: 1
title: First Time Setup
description: Setup financial year and start SST
slug: /usage/first-time-setup
tags: ["SQL Account", "Usage", "Setup"]
---

## Financial Period & System Conversion Date

:::info
Watch tutorial video here : [Youtube](https://www.youtube.com/watch?v=yH8VfNGjEr0&feature=youtu.be)
:::

1. **Tools** | **Options**

    ![2](../../static/img/getting-started/user-guide/2.png)

    :::note
    Once you have set up your Financial Start Period & System Conversion Date, it is not possible to change it again. This configuration can only be set once during the creation of a new database.
    :::

2. Select **General Ledger**

3. Select **Financial Start Period & System Conversion Date**

   ![3](../../static/img/getting-started/user-guide/3.png)

   :::note Scenario 1
   My financial period starts on 1st January every year, I start using SQL from 1/1/2015.

   **Financial Start Period** = 1/1/2015

   **System Conversion Date** = 1/1/2015
   :::

   :::note Scenario 2
   My financial period starts on 1st January every year, I start using SQL from 1/4/2015.

   **Financial Start Period** = 1/1/2015

   **System Conversion Date** = 1/4/2015
   :::

## SST

### Activate SST

1. In SQL Account, click on the menu **SST/GST** -> **Start SST now...**

   ![1](../../static/img/start-sst/1.png)

2. For the country, select **Malaysia**, and click Next

   ![2](../../static/img/start-sst/2.png)

3. Fill in **SST Effective Date**

4. Tick **I have SST registered number** if you have a valid SST registration number from the government (skip to *Step 6* if you don't have one)

   ![3](../../static/img/start-sst/3.png)

5. Fill in your **Sales Tax No** and **Service Tax No** (These details will be auto updated in your company profile)

   ![4](../../static/img/start-sst/4.png)

6. In the next step, click Next to auto generate **SST GL Account**

   ![5](../../static/img/start-sst/5.png)

7. In the following screen, you can preset your tax code for billing (Sales Tax, Service Tax, Sales Tax Exempted, etc.)

   ![6](../../static/img/start-sst/6.png)

8. System will prompt to re-login, and you are good to go

9. After log-in, you will see a new drop down list for SST Functions, the SST setup is now completed.

### Maintain Tariff

Go to **Tools** | **Maintain tariff** | **New**

Insert your product tariff code here, you can also find out your product tariff code from Malaysia Custom [JKDM HS Explorer](https://ezhs.customs.gov.my/)

![11](../../static/img/getting-started/user-guide/11.png)

## Company Profile

1. Go To **File** | **Company Profile**

   Fill in your company particulars and if this company is subject to both sales and service tax, fill in the Sales Tax number / Service Tax number.

   ![12](../../static/img/getting-started/user-guide/12.png)

2. Select **Report Header** & **Set Report Header**

   ![13](../../static/img/getting-started/user-guide/13.png)

---
id: patch-file
title: How to do Patch File using SQL Diagnosis Utility
description: A guide to fix database shutdown error for SQL Account
slug: /troubleshooting/how-to-do-patch-file-using-diagnosis-utility
tags: ["SQL Account", "Troubleshooting"]
---

## Steps & Instruction

:::note SITUATION
After cloning master data, we want to delete a customer (AR) or a supplier (AP).
:::

1. Must be done at the server PC, and all users must log out first

2. [Click Here](http://www.sql.com.my/document) and download the patch file

   ![1](../../static/img/troubleshooting/patch-file/1.png)

3. Open the downloaded patch (For example, if you want to delete a supplier)

   ![2](../../static/img/troubleshooting/patch-file/2.png)

   ![3](../../static/img/troubleshooting/patch-file/3.png)

4. [Click Here](http://www.sql.com.my/utility) and download diagnosis

   ![4](../../static/img/troubleshooting/patch-file/4.png)

   ![5](../../static/img/troubleshooting/patch-file/5.png)

   After download completed, click on the setup:

   ![6](../../static/img/troubleshooting/patch-file/6.png)

   ![7](../../static/img/troubleshooting/patch-file/7.png)

   ![8](../../static/img/troubleshooting/patch-file/8.png)

   ![9](../../static/img/troubleshooting/patch-file/9.png)

   ![10](../../static/img/troubleshooting/patch-file/10.png)

   ![11](../../static/img/troubleshooting/patch-file/11.png)

   ![12](../../static/img/troubleshooting/patch-file/12.png)

5. Open SQL Accounting Diagnosis

   ![13](../../static/img/troubleshooting/patch-file/13.png)

   ![14](../../static/img/troubleshooting/patch-file/14.png)

   ![15](../../static/img/troubleshooting/patch-file/15.png)

   ![16](../../static/img/troubleshooting/patch-file/16.png)

---

## Tips

   :::note Attention
   If you don’t know which database to choose, you may refer here
   :::

   1. Click on `⚙️`

      ![17](../../static/img/troubleshooting/patch-file/17.png)

   2. You can identify the database by checking the Database ID (For example, ACC-003.FDB)

      ![18](../../static/img/troubleshooting/patch-file/18.png)

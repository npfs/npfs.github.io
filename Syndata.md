---
layout: default
title: NPFS Synthetic Data Creation
---

# Synthetic Data Creation Process

## Introduction

This process describes how the Training Lead in the Call Centres can create synthetic data for the new recruits to utilise in the practical session during their training. The aim of using synthetic data is so that when we have people testing the system they have the data they need, without using personal data on the training system.

The Call Centre Training Lead will generate this information by following the process below.


## Step 1

Log on to the internet and go to the following site :

[Mockaroo](https://www.mockaroo.com/)

## Step 2 

The following page opens:

![][Mockaroo_opening_page]

## Step 3

On the far right hand side of each row you will see _**fx**_. Next to this there is a delete function marked with an _**X**_.

Delete the **email** and **IP Address** rows.

## Step 4 

Click on the **Add another field** button and a new row will appear. Delete the word that appears in the field name and replace with Date of Birth.

## Step 5

Select the **Type** field and a box will appear. Scroll down until you see **Date**. Click on **Date** and a date range will appear on that row. 
Choose a date range e.g 6/28/1948-6/28/2017.

> The date should be entered in American format (MM/DD/YYYY).

## Step 6 

Next go to the drop down box at the side of the date range and change this from American format to English format(DD/MM/YYYY).

## Step 7

Check the format field has CSV selected

## Step 8

Choose how many rows that you would like to generate

## Step 9

Press the green **Download Data** button

## Step 10

This will open a CSV file in Excel. Create a new header in column F titled Post code.

## Step 11

Log on to the internet and go to the following site:
[Postcode Site](http://www.postcode.co.uk/random.htm)

This will take you to a site that generates UK random postcodes:

![][UKpostcodes]

## Step 12

In the ‘Refine Search’ field add the number of postcodes you want and tick the ‘Plain Text’ box and press **Update**.

## Step 13

A list of postcodes will appear. Highlight and copy these.

## Step 14 

Return to your Excel file and paste the postcodes into Column F

## Step 15

You will now have your list for the new starters to use on the training environment.

## Step 16

Repeat this process when you have used all of the synthetic data and each time it will generate different post codes. 

**The image below shows an example of the data in the excel file output after following the above steps.**

![][Syndata_format]


Then use the passwords as required.

[Mockaroo_opening_page]: images/Syndata/Mockaroo_opening_page.png "Mockaroo Opening page"
[UKpostcodes]: images/Syndata/UKpostcodes.png "UK postcodes"
[Syndata_format]: images/Syndata/Syndata_format.png "UK postcodes"



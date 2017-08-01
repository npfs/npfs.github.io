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

On the far right hand side of each row you will see **fx**. Next to this there is a delete function marked with an **X**.

Delete the **email** and **IP Address** rows.

## Step 4 

Click on the **Add another field** button and a new row will appear. Delete the word that appears in the field name and replace with Date of Birth.

## Step 5

Select the **Type** field and a box will appear. Scroll down until you see **Date**. Click on **Date** and a date range will appear on that row. 
Choose a date range e.g 6/28/1948-6/28/2017.

> The date should be entered in American format (MM/DD/YYYY).

#Step 6 

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

Open a tab on the internet and enter the following address:- 

http://www.postcode.co.uk/random.htm

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

The file below shows an exmaple of a file output after following the above steps:

|id	|first_name|	last_name	|gender|	Date of Birth	|Post code|
1	Christin	MacDermot	Female	24/03/1959	BN20 9SF
2	Serena	Mepsted	Female	11/11/1971	L13 2BX
3	Darnell	Stubbeley	Male	27/05/1970	DY8 4AY
4	Jana	Sapir	Female	01/05/1949	CV6 5RF
5	Lane	Kissell	Male	24/03/2008	WF7 5WW
6	Odell	Nelligan	Male	04/01/1998	NR15 2XN
7	Padraic	Rumke	Male	05/09/1987	FY1 1RZ
8	Gaby	Floweth	Male	22/04/1997	CB21 5NP
9	Prue	Swansbury	Female	13/02/1981	EX20 4JX
10	Kev	Roeby	Male	09/05/1981	BN16 4JS
11	Bella	Myall	Female	01/10/1986	TA19 9FL
12	Armin	Simenon	Male	15/07/1990	BH14 9JJ
13	Dael	Jeayes	Female	17/08/1956	ST6 5JB




Then use the passwords as required.

[Mockaroo_opening_page]: images/Syndata/Mockaroo_opening_page.png "Mockaroo Opening page"
[UKpostcodes]: images/Syndata/UKpostcodes.png "UK postcodes"




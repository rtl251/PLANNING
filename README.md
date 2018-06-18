# Project Planning

## Problem Statement

### Primary User
Me (student in python programming and software development class)

### User Needs statement

I am looking for a way to save the information of sold listings on ebay.

Currently a user of ebay can manually retrieve records of items
that have been sold on the ebay platform within the last 2 months.

But instances beyond 2 months are deleted from ebay's searchable records. This 2-month period
is rolling: If today is 6/16/2018, you will be able to retrieve sold listings on 4/16/2018, but 
tomorrow you will no longer be able to retrieve that data.

A program that would be able to search for sold listings and save the data in a 
csv file would prove useful to users would wish to track the sales history of a particular item 
for periods beyound 2 months, as this functionality currently isn't available.

## Information Requirements

### Information Inputs

A record of an ebay sold listing  of a particular item and its attributes, including auction end date, ending price, 
shipping cost, ebay seller name, size (if applicable) and descrition. (possibly pictures as well)

### Information Outputs
The same inputs written neatly in a csv file (list of data dictionaries)

## Technology Requirements

### APIs and Web Service Requirements
Ebay API

### Python Package Requirements
Beautiful Soup

ebaysdk

### Hardware Requirements
Personal Machine


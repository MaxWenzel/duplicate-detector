# duplicate-detector
Building AI course project

## Summary

Duplicates in the database or Excel sheet are not only annoying, but can also cost real money. An example is the multiple sending of information brochures to the same address.
Using the latest AI technologies, the tool detects potential duplicates. These can then be removed or merged with other data entries.


## Background

What is a duplicate? How can a duplicate record be identified? "Data is the new oil." Many companies have now understood this wisdom and are now collecting all kinds of data. But collecting is only a first step. The data must be merged, stored, cleaned up (duplicates!) and analyzed. Buzzwords are Big Data, Fast Data and Smart Data.
ust a small example: Are the following two data sets the same? Yes, no or maybe?

| first name      | last name | city | street|
| ----------- | ----------- |----------- |----------- |
| Johannes      | Kayser       | Karlsruhe-Durlach | Hauptstrasse |
| John   | Keiser        | Karlsruhe | Hauptstr. |

## How is it used?

The tool analyzes entries of a database or excel sheet and finds possible duplicates. These are displayed to the user and he can then decide how to use this information. 

## Data sources and AI methods

We use existing databases on which the tool can work and tryy to detect duplicates.
The default way that we can do this is to use what’s called a string similarity. A string similarity is an way of taking two strings and returning a number that is low if the strings are dissimilar and high if they are similar.

## Challenges

We have to precisely define what we mean for two records to be similar. How high is the similarity of two existing (duplicate) entries?

## What next?

The duplicate-detector can be used in many different ways. Finding duplicate addresses, similar products in a catalog or the top-k most similar documents in a document database.


## Acknowledgments

I'd like to thank Reaktor, University of Helsinki and everyone else who have been a part in making both Elements of AI and Building AI a reality.

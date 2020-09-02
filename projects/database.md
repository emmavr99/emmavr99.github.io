---
layout: project
type: project
image: images/database.jpg
title: Building a database
permalink: projects/database
# All dates must be YYYY-MM-DD format!
date: 2019-10-15
labels:
  - c
  - c++
summary: Building a database for the final project of ICS 212.
---

<img class="ui image" src="{{ site.baseurl }}/images/cotton-header.png">

Building a database was the last project I had to do in ICS 212 at UH Manoa. First, we had to build a databause using c, and then later on we had to build that same database using c++.
The database consisted of records of "clients". Each client would have an accountnumber, name and address and a pointer to the next record. The list needed to be sorted in ascending order. The person with the account number needed to be at the front of the list. 

When the program ran, the user was presented with a menu. Records could be added to the list, removed from the list, and addresses could be changed. Records could be searched and found by accountnumber. I had to write several functions and we made use of pointers among other things. I wrote a readfile and a writefile function. I also wrote a function that reversed the list, thus it made the list in descending order. 

The record structure for this project looked like this:

#ifndef RECORD_H
#define RECORD_H

struct record
{
    int                accountno;
    char               name[25];
    char               address[80];
    struct record*     next;
};

#endif










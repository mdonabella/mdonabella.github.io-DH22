---
layout: post
title: Lab 02 - Spreadsheets
subtitle: Understanding Metadata & Basic Visualization 
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [lab report]
comments: true
---

* To get started, here are my links:
	1. [Trans-Atlantic Slave Trade Dataset and Pivot Tables](https://docs.google.com/spreadsheets/d/1S7Qx0P612gnQgRt7em_t_sCeVKTv0OobmoQQ4yzo__k/edit?usp=sharing) 
	2. [Adapted Post45 Hathi Trust Dataset](https://docs.google.com/spreadsheets/d/1ZqSpvK2HPGVJ61b4N66-_MasC1Qru7lbYM0Rrk9RX-o/edit?usp=sharing)
	3. [Post45 HT Data Visualization 1](https://public.tableau.com/app/profile/micaela.donabella/viz/OccurencesofPublisherxDate/Sheet2?publish=yes)
	4. [Post45 HT Data Visualization 2](https://public.tableau.com/app/profile/micaela.donabella/viz/OccurencesofGenre/Sheet4?publish=yes)
  
  * The HathiTrust dataset was harder to work with than the Trans-Atlantic Slave Trade dataset because of its size and the qualitative nature of its most interesting data. As I am an Excel (/spreadsheet) novice, I had to go quite a bit of Googling to make the data readable in the ways that I wanted. Namely, I had to learn how to count the occurrences of values in a given column, and in a way that allowed me to create a visualization in Tableau (this latter step was obviously not *necessary*, but I wanted to defamiliarize myself with the platform). With the help of several YouTube videos, I came to find the best way (or, easiest way for me) to do that for this particular data set. 
	1. Insert blank column next to column containing values to be analyzed. Let column to be analyzed be “A.”
	2. Copy values from “A” into new column, “C,” on the other side of blank column (“B”).
	3. With the column “C” highlighted, go to the “Data”(6th tab to the right  in the top left of the screen), then under the “Data” tab click “Remove duplicates,” only selecting column “C.”
	4. In the first *real* cell in column “B” (that is, under the metadata category), type =COUNTIF(A:A,C1) and hit enter. This should yield the number of occurrences of the first value.  
	5. Finally, double click the bottom right of the cell containing that function and the rest of the column will populate with that function, thus yielding the number of occurrences of each remaining value. 
	
  In learning this particular function, I was able to look at the number of times each genre appears in the collection and the number of books in the collection published by each listed publisher each year. What I still would have liked to do is make clear how the popularity of each (listed) genre did or did not change over time; however, I couldn’t quite nail down the appropriate functions (and visualization tactics) to make that relationship between publication date and genre visible. 

* Insofar as each data visualization (in both datasets) involved counting, I can’t help but think of “What Gets Counted Counts” from *Data Feminism*. Particularly, the act of “counting” in the final pivot table corresponding to the Trans-Atlantic Trade Dataset, “African resistance vs. Year of arrival at port of disembarkation” raises questions about what counting *does*. Counting in this way does on the one hand reduce actualizations of an ongoing resistance to subjugation to particular (past) moments in time. Further, there is possibility that particular moments of resistance might have been unreported due to human failure to report and/or of varying classifications of “resistance” it seems that this sort of counting of resistance acts might downplay networks of resistance and minor attempts at resistance. 

* Beyond this issue of binary (as no resistance/active resistance), though, it seems Jessica M. Johnson and D’Ignazio and Klein would agree that counting might be the first step to acknowledgement of the *being* of resistance in the first place. While D’Ignazio and Klein argue that collective oppression (maybe here, collective resistance) is often more visible through quantitative data), Johnson argues that “the ease with which open-access projects like the Trans-Atlantic Slave Trade Database performed extraordinary acts of simple ‘figuring’ permanently changed perceptions of the slave trade (64). I think “figuring” collective response is where the power in this particular counting instance lies. Where a balance of quantitative and qualitative data is usually ideal, responsible quantitative data is perhaps the best case scenario in the absence of qualitative data, as it is more ethical and more generative to acknowledge *being* than to play with qualitative terms that might foster and erasure of that being. 

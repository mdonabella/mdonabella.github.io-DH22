---
layout: post
title: Lab 03 - From Context to Standard Settings
subtitle: Introductory Practice with Regular Expressions
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [lab report]
comments: true
---

## The Process of Understanding and Final Steps
The steps I ultimately took to reach the desired outcome for Lab 3 are below: 
1. (“) → nothing
2. (;) → (  d) 
3. ([[[:punct:]]](#))→ nothing
4. (ate Boston) → (Boston MA)
5. (amp  d) → nothing 
6. (  d ) → , (look at Excel file to see how spacing works and remove spacing around comma) → “,” 
7. (te Boston) → te,Boston MA
8. Colo. → CO
9. Md → MD
10. Virginia → VA

Final outcome:
1. [Via RegEx101](https://regex101.com/r/6vnjU7/1)
2. Copied over: 
  - Jewish Advocate,Boston MA
  - Washington Informer,Washington DC
  - News from Indian Country,Hayward WI
  - Afro  American 5 Star edition,Baltimore MD
  - Diverse Issues in Higher Education,Fairfax VA
  - The Gay amp Lesbian Review Worldwide,Boston MA
  - The Hispanic Outlook in Higher Education,Paramus NJ
  
  (*No one tell me if there are still errors. Kidding but not really.*)

I did not arrive at those 10 steps, however, without several hours (like, more than one day) of experimentation and failure. Read about that process [here](https://docs.google.com/document/d/1XU2JkEqqJ5mDpM3EtjCLRLEmfPgEle40BtFl-XAZt-4/edit?usp=sharing). 

## Reflections 

As displayed in my lengthy process linked above, working with regular expressions took a lot of experimentation. This experimentation involved not only playing with the different IDs in the RegEx101 platform itself, but revisiting the lab instructions and interpreting/utilizing directions in a new way and seeking out forums that might provide answers to my questions. No particular forum did, in fact, answer any one question directly, but scrolling through different ways of writing expressions did inadvertently teach me new ways of matching characters that I missed in my initial exploration of the RegEx101 glossary. Commonly visited websites included forums hosted on [stackoverflow.com](https://stackoverflow.com/) and [a guide offered by a university in Singapore](https://www3.ntu.edu.sg/home/ehchua/programming/howto/Regexe.html) (Nanyang Technological University, apparently). 

Insofar as I relied heavily on experimentation and reference in order to reach particular data settings, I am thinking a lot about Chapter 5 from *Data Feminism* and the first entry from *Data-Sitters Club* in reflecting on my process. While perhaps the changes to the structure of this dataset can be seen as minor and necessary to make publication information readable in spreadsheet format (and then transferable to a data visualization), I *did* feel like a stranger, as D’Iganzio and Klein proffer we all become when we encounter data outside of the initial collection process. Removing dashes and ampersands from titles, felt, well, intrusive, even if it was in the name of readability. But it really was only through this process of acting-as-stranger that I could fully grasp Loukissas’s concept of data settings: datasets are not information as it always has been, but in its most readable form; they present information as it has been interpreted to fit standardized ways of seeing. Perhaps this was the point of the lab to begin with.

To elaborate on this notion of decontextualization for and/or on the part of strangers, just as *upstate* contained valuable information in the context of South Carolinian geography and social understanding, it seems removing punctuation undid intentional significations. Particularly, the hyphen in “Afro - American 5 Start edition,” the quotation marks in the second and ninth titles in the set, and the question mark after “WI.” in relation to “News from Indian Country” all seem to be integral to understanding context. Removing the hyphen in the first example enacts a separation of a compound word, “Afro-American,” which changes how the title is read. Removing quotation marks limits the potential of the titles of the second and ninth texts to signify *something uttered* or *a writing act belonging to someone*. Finally, it seems the publication location of “News from Indian Country” is actually in question (“WI.?”), meaning that in changing the setting of this data, I have engaged in false affirmation or confirmation. While I understand why this new structure might have been necessary for readability in specific contexts, I also wonder how and when data scientists might decide to reinvent settings so as to avoid erasures. 

In *Data-Sitters Club*, navigating the constraints of setting involved a collaborative bricolage. On a different but related note, then, just as Quinn took to Twitter and relied upon the knowledge of those in related fields in collaboration with her own skills to ultimately work *The Baby-Sitters Club* data, the ability to create even this small .csv-readable dataset was only possible through learning from various sources crafted by people (often) only tangentially related to my field. Despite the work that might need to be done in the larger field of data science (/humanities/analysis) to untangle notions of correctness from what has been normalized or is now embedded in platforms for reading data, it is continually heartening to see that there is a whole world of interpreters of data who willing offer their skills, insights, and best practices for anyone working with data to see and use. 

As an aside and final point, I will also say that a lot of the conversations we’ve now had on the topic of data cleaning, via D’Ignazio and Klein and Rawson and Muñoz, remind me of the frustrations I felt as a sociology major taking methods courses in undergrad. Namely, while there was some emphasis on qualitative research in my program, most of the projects I was assigned required that I use survey data to suggest--by way of statistical equation--either direct correlation or lack thereof between different (social) variables. One of the reasons I did not stay in the social sciences was because I found the expected means of working with social data quite limiting and sometimes apathetic. However, as I read for this class, I find the broadening of approaches via new scholarship and collaborative work really encouraging. I’m excited to build a better understanding of practices that allow for transparency and visibility of nuance. 

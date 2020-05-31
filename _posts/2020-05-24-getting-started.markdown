---
layout: post
title:  "Let's get started?"
date:   2020-05-24 18:00:00 +0530
---

<br/>

<img src="/assets/images/gsoc_openmrs.png" style="width:auto; height:250px; position:relative; left:5%;">

<span style="font-family: medium-content-serif-font, Georgia, Cambria, Times New Roman, Times, serif; font-size:17px; letter-spacing: +0.02em; line-height:1.6;">
It was around 22:30 Hrs (UTC +5:30), on the night of 4th May 2020, I had just had my dinner and went back to my room. There was an hour left for something that had kept me waiting and waiting for more than a month. It was the time when the Google Summer of Code results would be announced, sharp at 23:30 Hrs . I lay on my bed pondering, "<i>what should I do for the next 60 minutes?</i>".


<span style="font-family: medium-content-serif-font, Georgia, Cambria, Times New Roman, Times, serif; font-size:17px; letter-spacing: +0.02em; line-height:1.6">
After a while of skimming through possible ideas, I figured out I was too nervous to do anything. So, I just decided to stay in that position and think of the entire process I had followed to get to this point, being patient while starting to contribute to open source even though most of the things went over my head, being courageous enough to not leave it in between, and finally to be able to press the "<i>Submit Proposal</i>" button on the dashboard. 

<span style="font-family: medium-content-serif-font, Georgia, Cambria, Times New Roman, Times, serif; font-size:17px; letter-spacing: +0.02em; line-height:1.6">
I was going through mixed feelings, what would happen if I don't get in, what would I do if I did and how would the next few months look like. I tried to not get too carried away by all this but I couldn't really stop myself, for I had definitely put in a great amount of effort and I felt I had a great chance as well. I finally agreed to take this as a part of the experience and rejoice it while it lasted...something I've learnt the hard way! 

<span style="font-family: medium-content-serif-font, Georgia, Cambria, Times New Roman, Times, serif; font-size:17px; letter-spacing: +0.02em; line-height:1.6">
So, after managing to get to 23:15 Hrs, I stood up, had some water to relax myself, made a glass of mango shake which happens to be my favourite summer drink. So, it's finally 23:25 Hrs and I opened my laptop, staring at the projects page and my mind ticking like a clock, counting every second that passed by.

<span style="font-family: medium-content-serif-font, Georgia, Cambria, Times New Roman, Times, serif; font-size:17px; letter-spacing: +0.02em; line-height:1.6">
Google, being very punctual with the timeline, announced the results at sharp 23:30 Hrs. I refreshed the page, searched for my name. <b><i>No results found for your search</i></b> is what I got. I refreshed the page again with my heart in my mouth, and searched once more. And then my eyes glowed seeing it there with my preferred org. My happiness knew no bounds, I jumped in excitement, it was the moment I had been dreaming of for 4 months. I got an email from Google, which said: <i><b>“Congratulations, your proposal with OpenMRS has been accepted!”.</b></i>
I was now a member of the OpenMRS community and looked forward to contributing extensively to their code base :)

<br />

## <b>What is OpenMRS?</b>

<span style="font-family: medium-content-serif-font, Georgia, Cambria, Times New Roman, Times, serif; font-size:17px; letter-spacing: +0.02em; line-height:1.6">
<b><a href = "https://www.openmrs.org">OpenMRS</a></b> is a Medical Records System to support the delivery of health care, developed for the underprivileged sections of the society. The OpenMRS community is always ready to assist you with any issues you might be facing. The tag line, <i>"Write Code. Save Lives." </i>, inspires contributing more to this wonderful organization. The community offers a great platform to learn and grow as a developer, with a very systematic and well-defined structure of almost everything from issues to wikis for getting onboarded real quick. 

<br />

## <b> The Project: Improve FHIR Search </b>

<span style="font-family: medium-content-serif-font, Georgia, Cambria, Times New Roman, Times, serif; font-size:17px; letter-spacing: +0.02em; line-height:1.6">
FHIR (or <i>Fast Healthcare Interoperability Resources</i>) is a standard for exchanging electronic health records. It describes elements (called resources) and an API (or application programming interface) for implementation of the same. The project comprises of improving the search of the FHIR module of OpenMRS by adding support for the exhaustive list of search parameters specified by the HAPI FHIR library.

<span style="font-family: medium-content-serif-font, Georgia, Cambria, Times New Roman, Times, serif; font-size:17px; letter-spacing: +0.02em; line-height:1.6">
The objectives of the project are as follows:

- <span style="font-family: medium-content-serif-font, Georgia, Cambria, Times New Roman, Times, serif; font-size:17px; letter-spacing: +0.02em; line-height:1.6">Adding implementation for the remaining search parameters for the most useful resources including Location, Observation, Encounter, DiagnosticReport, Patient, Person etc.
- <span style="font-family: medium-content-serif-font, Georgia, Cambria, Times New Roman, Times, serif; font-size:17px; letter-spacing: +0.02em; line-height:1.6">Adding implementation for common search parameters including _id and _lastUpdated.
- <span style="font-family: medium-content-serif-font, Georgia, Cambria, Times New Roman, Times, serif; font-size:17px; letter-spacing: +0.02em; line-height:1.6"> Adding paging functionality to resources which do not support it currently.
- <span style="font-family: medium-content-serif-font, Georgia, Cambria, Times New Roman, Times, serif; font-size:17px; letter-spacing: +0.02em; line-height:1.6">Implementing the advanced search parameters like _include, _elements and _summary which let you search in a more specific manner.
- <span style="font-family: medium-content-serif-font, Georgia, Cambria, Times New Roman, Times, serif; font-size:17px; letter-spacing: +0.02em; line-height:1.6">Adding support for Lucene indices available for certain resources by implementing LuceneQuery instead of CriteriaQuery.
- <span style="font-family: medium-content-serif-font, Georgia, Cambria, Times New Roman, Times, serif; font-size:17px; letter-spacing: +0.02em; line-height:1.6">Integrating the module with GraphQL as a stretch goal.

<br />

<span style="font-family: medium-content-serif-font, Georgia, Cambria, Times New Roman, Times, serif; font-size:17px; letter-spacing: +0.02em; line-height:1.6">
<u>Primary Mentor</u>: <b><a href="https://talk.openmrs.org/u/ibacher">Ian Bacher</a></b>
<br /><br />

<span style="font-family: medium-content-serif-font, Georgia, Cambria, Times New Roman, Times, serif; font-size:17px; letter-spacing: +0.02em; line-height:1.6">
<u>Backup Mentor</u>: <b><a href="https://talk.openmrs.org/u/reagan">Reagan Patrick</a></b>
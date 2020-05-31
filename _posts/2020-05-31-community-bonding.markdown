---
layout: post
title:  "GSoC 2020 at OpenMRS | Community Bonding Period"
date:   2020-05-31 17:00:00 +0530
---

<br />
<figure>
<img src="/assets/images/community-bonding.jpg" style="width:auto; height:400px; position:relative; left:10%;"><figcaption style="text-align:center">Community Bonding</figcaption>
</figure>

<br />
<div style="font-family: medium-content-serif-font, Georgia, Cambria, Times New Roman, Times, serif; font-size:17px; letter-spacing: +0.02em; line-height:1.6;">

The community bonding period for GSoC 2020 extended from May 4, 2020 to May 31, 2020. Since the four-week long community bonding is now almost complete and the coding period (Phase - I) is on the verge of commencing, I'd like to share my experience working during the same through this blog.
<br /> <br /> <br />


<h2><b> Reading Documentation </b></h2>
The community bonding period gave me an opportunity to go through the code base. This helped me in understanding all the functionality that has been implemented in the FHIR module, particularly the search part of it. Since the paging implementation had already begun by the time projects were announced, I got an overview of what all changes had been made to the code base to support it and what all will be required to be added to the resources that do not support paging currently. 
<br/><br/>
I also read a lot of documentation regarding my project, including the <a href="https://hapifhir.io/hapi-fhir/docs/server_plain/rest_operations_search.html"><b> HAPI FHIR library</b></a> on search and interceptors. Since my project includes implementing Lucene queries and integrating GraphQL with the FHIR module as a stretch goal, I also got a chance to look into those aspects as well.
<br /> <br /><br />

<h2><b> Coding Shouldn't Stop </b></h2>
On the coding side, I got my hands dirty on various issues in the FHIR module. While going through the code for FHIR search, I found some bugs and created JIRA tickets for the same and rectified them. I also worked on implementing search for some resources like DiagnosticReport which didn't have the functionality. The list of issues I worked on in the community bonding period is as follows:
<br/><br/>
<ul style="font-size: 19px;"><u>
<li style="padding: 10px 0px;"><a href="https://issues.openmrs.org/browse/FM2-170" style="color:black">Replace OrList parameters by AndList parameters</a></li>
<li style="padding: 10px 0px;"><a href="https://issues.openmrs.org/browse/FM2-175" style="color:black">Correct handling of empty chains in BaseDao</a></li>
<li style="padding: 10px 0px;"><a href="https://issues.openmrs.org/browse/FM2-179" style="color:black">Restrict chain whitelist for Observation resource</a></li>
<li style="padding: 10px 0px;"><a href="https://issues.openmrs.org/browse/FM2-151" style="color:black">Update DiagnosticReport DAO and Service</a></li>
<li style="padding: 10px 0px;"><a href="https://issues.openmrs.org/browse/FM2-174" style="color:black">Improve Search for DiagnosticReport resource</a></li>
</u></ul>


<br /> <br />

<h2><b> Planning for Phase-I Coding Period</b></h2>
 An important part of the community bonding period is to plan for the work to be done in the coding period and get to know your mentors. I had several conversations with my mentor, Ian Bacher, where we used to discuss the goals and the expectations for the coding period and also got to know each other in a better way. We also talked about any issues that I faced and discussed on ways of resolving them. 
 <br/><br/>
 We decided to create JIRA tickets for issues as and when I start working on them and hence worked out the goals for phase-I of the coding period. The two major things I'll be working on are implementing the common search parameters, including <i><b>_id</b></i> and <b><i>_lastUpdated</i></b>, and implement paging for resources which currently do not support it. The JIRA tickets for the same can be found below:
<br/><br/>
<ul style="font-size: 19px;"><u>
<li style="padding: 10px 0px;"><a href="https://issues.openmrs.org/browse/FM2-169" style="color:black">Add search for _id and _lastUpdated</a></li>
<li style="padding: 10px 0px;"><a href="https://issues.openmrs.org/browse/FM2-134" style="color:black">Add paging support to the following resources:</a>
<ul>
<li style="padding: 10px 0px;"><a href="https://issues.openmrs.org/browse/FM2-166" style="color:black">Encounter</a></li>
<li style="padding: 10px 0px;"><a href="https://issues.openmrs.org/browse/FM2-167" style="color:black">AllergyIntolerance</a></li>
<li style="padding: 10px 0px;"><a href="https://issues.openmrs.org/browse/FM2-168" style="color:black">Location</a></li>
<li style="padding: 10px 0px;"><a href="https://issues.openmrs.org/browse/FM2-203" style="color:black">DiagnosticReport</a></li>
<li style="padding: 10px 0px;"><a href="https://issues.openmrs.org/browse/FM2-204" style="color:black">Practitioner</a></li>
<li style="padding: 10px 0px;"><a href="https://issues.openmrs.org/browse/FM2-205" style="color:black">Medication</a></li>
<li style="padding: 10px 0px;"><a href="https://issues.openmrs.org/browse/FM2-206" style="color:black">Condition</a></li>
</ul></li></u>
</ul>

<br /> 

<h2><b> Project Status</b></h2>
The <i><b>Improve FHIR Search</b></i> project is in progress and I have already started working on the paging tickets. I was supposed to work on implementing the functionality for the common search parameters first, but owing to a lot of non-uniformity in the code base because some resources have paging implemented and some don't, my mentor and I decided to first work on paging and then implement the common search parameters after the code base becomes balanced.
<br /><br /><br/>
<b>Project Discussion Thread:</b> The public discussions related to my project can be found on this <a href="https://talk.openmrs.org/t/gsoc-2020-improve-fhir-search/28416"> OpenMRS Talk thread.</a>
<br /><br /><br/>
<b>Github Repositories:</b>

<br/><br/>

<ul style="font-size: 19px;">
<li style="padding: 10px 0px;"><i>Source:</i>   &nbsp;<a href="https://github.com/openmrs/openmrs-module-fhir2" style="color:black"><u>https://github.com/openmrs/openmrs-module-fhir2</u></a></li>
<li style="padding: 10px 0px;"><i>Dev Fork:</i>   &nbsp;<a href="https://github.com/varung-31/openmrs-module-fhir2" style="color:black"><u>https://github.com/varung-31/openmrs-module-fhir2</u></a></li>
</ul>


</div>
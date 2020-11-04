# Autonomous-Vehicle-Safety-Analysis

This project explores failures and disengagements in Autonomous Vehicles (AVs) being tested on public roads in California.

Autonomous Vehicles are complex systems that use artificial intelligence (AI) and machine learning (ML) to integrate mechanical, electronic and computing technologies to make real-time driving decisions. Several states in the USA (e.g. California, Texas,
Nevada, Pennsylvania, and Florida) and other parts of the world (e.g. China [1]) have
already started field-testing AVs on public roads. As AVs have started interacting more
directly with humans on public roads, the safety and resilience of AVs is a significant
concern (Uber’s [2] fatal accident, Tesla’s [3] autopilot flaw) and must be thoroughly
evaluated through analysis of data obtained during field-testing.

**Dataset description:**

**mp1_av_disengagement.csv**
Month - Month and year when the disengagement happened.<br/>
Car - ID of the AV.<br/>
Location - Where the car was when the disengagement happened.<br/>
Weather- Weather conditions when the disengagement happened.<br/>
TypeOfTrigger - Whether the disengagement was automatic (decision taken by AV) or manual (decision taken by human driver).<br/>
ReactionTime - Time taken, in seconds, by the human driver to take control of the car after an automatic trigger.<br/>
NOTE: ReactionTime is not given for manual disengagements since it does not involve a trigger by the AV.<br/>
Cause - Reason for the disengagement.<br/>

**mp1_av_totalmiles.csv**

Month - Month and year of AV testing.<br/>
Car - ID of the AV.<br/>
Miles driven - Total number of miles driven by the AV during the given month.<br/>
Total number of disengagements - Number of disengagements during the given month.<br/>
Number of automatic disengagements - Number of disengagements where the AV decided to give control to the human driver.<br/>
Number of manual disengagements - Number of times the human driver decided to take control of the AV.<br/>







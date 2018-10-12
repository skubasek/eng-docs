This document contains information regarding operating procedures (SOPs) of 
[system title] - id:[replace with id, no brackets] in production environment. 

<small>The main <strong>objective</strong> of the document is to help a developer/support with a routine production processing (ie, release),
ongoing maintenance, and identified problems and issues.</small>


# Business Description

<small>Instructions: Provide a description of the system, including its purpose and key features and benefits.</small>

# System Overview

## Application Dependency

<small>Instructions: List all external dependencies of the application/system and the impact.</small>

| Dependent Application/System | Function | Impact (if Application is Down) |
--- | --- | --- 
| &lt;Dependent Application/System Name&gt; | &lt;Function&gt; |&lt;Impact if Application is Down&gt; |

## Architecture Overview

<small>Instructions: Provide a brief description of the system architecture and the major system components essential 
to the operation of the system in prod.  Provide any charts, diagrams, and/or graphics as 
necessary to depict system organization.</small>

## Inputs / Outputs

<small>Instructions: List system inputs & outputs and provide description of each.
Include a data flow diagram, if applicable.</small>

# Operation Procedures

## Verification of Normal Operation

<small>Instructions: Provide instructions on how to verify system is functioning properly.</small>

## Release Procedures

<small>Instructions: Provide instructions on which steps to follow to properly release a new version of the
system, and how to properly validate it.

## Restart/Recovery Procedures

<small>Instructions: Provide procedures for restart/recovery in the event of a system failure. </small>

### Failover Procedures

<small>Instructions: discuss Disaster Recovery/Failover procedures, if applicable.</small>

# Monitoring & Error Handling

## Critical Errors

<small>Instructions: Itemize errors in logs that need to be addressed</small>


| Identifying Text | Error/Situation Description | Recommended Action |
--- | --- | ---
| &lt;log text&gt; | &lt;describe potential reasons/impact of this&gt; | &lt;what should this issue be addressed&gt; | 


## Alerts

 Monitoring System | Purpose | Details | Action Required | Verification |
--- | --- | --- | --- | ---
&lt;nagios,...&gt; | &lt;what is the monitor looking for&gt; | &lt;include details, urls, log&gt; | &lt;what should be done to get this issue resolved&gt; | &lt;provide ways to confirm status, both good and bad&gt;

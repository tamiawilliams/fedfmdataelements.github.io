---
published: false
permalink: /DAIMS-v1.2/
layout: article
filename: DAIMS-v1.2.md
title: DATA Act Information Model Schema v1.2
page: DAIMS-v1.2
---
# DATA Act Information Model Schema v1.2

_Released December 22, 2017_ – A core requirement of the DATA Act is the development of government-wide data standards to ensure the reporting of reliable, consistent federal spending data for public use. Office of Management and Budget (OMB) and Treasury finalized the data definition standards and Treasury used the data definition standards to develop the initial draft of the DATA Act data exchange standard, or Schema, in May 2015. Treasury collected public input and feedback from federal agencies and implemented an agile development methodology to create the DATA Act Information Model Schema (DAIMS) v1.0. DAIMS v1.2 is the next minor update and implements policy requirements, promotes additional data standardization, and reduces federal agency reporting burden. DAIMS v1.2 will be implemented with the submission of fiscal year 2018 quarter 3 data.

DAIMS gives an overall view of the hundreds of distinct data elements used to tell the story of how federal dollars are spent. It includes artifacts that provide technical guidance for federal agencies about what data to report to Treasury including the authoritative sources of the data elements and the submission format. The DAIMS also provides clarity on how the public can better understand the inherent complexity of the data.

##### DAIMS includes:
- **Overview and Architecture** – provides an overview of the data standard and its architecture.
- **Information Flow** – provides an overview of the reporting timeframes and sources of the data included in the DAIMS across the federal enterprise. 
- **Reporting Submission Specification (RSS)** – includes a listing of the data elements with specific instructions for federal agencies to submit content in the appropriate format. The RSS is a human-readable version of the data standard. The previously separate Terse Labels (shortened versions of the data element names), Domain Values (permissible values for a sub-set of the DAIMS data elements), and DAIMS Diagrams (visual representations of how the data elements from the RSS fit together in context) have been incorporated to improve usability. 
- **Interface Definition Document (IDD)** – contains a listing of the elements, with supporting metadata to understand what data will be pulled from government-wide systems for procurement and from agency financial assistance systems. The IDD is a human-readable version of the data standard for the award related content. The previously separate Terse Labels (shortened versions of the data element names) and DAIMS Diagrams (visual representations of how the data elements from the IDD fit together in context) have been incorporated to improve usability. 
- **Online Data Dictionary** – contains a comprehensive list of data elements with definitions and some associated metadata. 
- **XBRL Schema Files** – provide a machine-readable version of the data standards that include accounting-related and award-related content.

## Overview and Architecture

The [DAIMS Overview]({{site.baseurl}}/assets/docs/DAIMS_Overview.pdf) describes the scope and value of the data standard. The [DAIMS Architecture]({{site.baseurl}}/assets/docs/DAIMS_Architecture.pdf) details the data standard conceptual model, specifications, and schema management. The DAIMS architecture is designed to meet the needs of the business users and technical systems. It serves as the foundation for the DAIMS data standard. It is extensible through domain, component, element, and metadata. Additional descriptive content on the DAIMS architecture will be released as necessary. Please submit any questions or feedback to [Community](https://usaspending-help.zendesk.com/hc/en-us/community/topics).

## Information Flow

The Information Flow provides an overview of the sources of the data included in the DAIMS and how the data is submitted to the DATA Act Broker. Treasury will maintain the current cadence for reporting federal awards on a daily and twice-monthly basis and added the quarterly reporting of financial data in May 2017. This updated model shows how the data flows from the agency financial and awards systems to the public website.

<img width="800" src="{{ site.baseurl }}/assets/docs/DAIMS_Information_Flow_Diagram_v1.1.png" title="information flow diagram" />

## Reporting Submission Specification (RSS)

The RSS provides details on what data needs to be submitted by an agency. The RSS contains prescriptive guidance to report appropriations account, object class, program activity, and award financial data from an agency's financial system(s). The award financial data contains instructions to link the data between the financial systems and the award systems using the award identification number. In addition, the RSS now contains the details of the Financial Assistance Broker Submission (FABS) file. The File FABS contains the information for an agency’s submission of its financial assistance award and awardee data. The RSS also includes information about optional/required data, field length, and other metadata to ensure data quality. The RSS documents contain the specific instructions a federal agency will need to submit data.

The RSS includes four files that the agencies will submit to Treasury’s Broker:
- File A – Appropriations Account Detail
- File B – Object Class and Program Activity Detail
- File C – Award Financial Detail
- File FABS – Financial Assistance Broker Submission Detail

Download the [RSS v1.2]({{site.baseurl}}/assets/docs/DAIMS_RSS_v1.2.xlsx)

## Interface Definition Document (IDD)

The Interface Definition Document (IDD) provides an overview of the award specific data elements and explains how the data will be reported or collected. Some data elements will be pulled from government-wide intermediary systems for procurement data, recipient attributes and sub award information.  The IDD also includes data elements submitted by agency systems for financial assistance awards.
The IDD features the elements related to:

- File D1 – Award and Awardee Attributes (Procurement)
- File D2 – Award and Awardee Attributes (Financial Assistance)
- File E – Additional Awardee Attributes
- File F – Sub-award Attributes

Download the [IDD v1.2]({{site.baseurl}}/assets/docs/DAIMS_IDD_v1.2.xlsx)

## Online Data Dictionary

The [Data Dictionary v1.2]({{ site.baseurl }}/dictionary-v1.2/) is a comprehensive list of data elements with definitions and some associated metadata.

## XBRL Schema and Data Files

A data standard contains both a human-readable version of the standard and a machine-readable version of the standard. The XBRL Schema files are the machine-readable version of the DATA Act standard.

[Zipped Schema Files with Release Notes (Updated on December 22, 2017)]({{site.baseurl}}/assets/docs/daims_v1.2_2017-12-22.zip)

## Data Definition Standards

The Federal Funding Accountability and Transparency Act (FFATA) and DATA Act outline the required information for federal spending transparency reporting. These requirements were translated into core data definition standards that were standardized with feedback from the federal community and external stakeholders. The finalized definitions and background information for these elements are available on the [Data Elements Page]({{ site.baseurl }}/data-elements/).

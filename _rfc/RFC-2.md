---
layout: post
title:  "RFC #2: The Recommended Structure of an IIFRP Request for Comments"
date:   2021-04-18 13:38:21 -0700
categories: rfc meta
published: true
status: accepted
---

IIFRP Meta Committee<br />
Request for Comments: 2<br />
Category: Standard<br />
Status: **Adopted Standard**<br />

Brian Schrader<br />
April 2021

------

<style>.docinfo { border-bottom: 4px solid var(--adopted-standard); }</style>

Status of this Memo

   This memo contains a proposed standard for the community. It makes no claim to enforce the proposal contained herein. Distribution of this memo is unlimited.

Copyright Notice

   Copyright (C) IIFRP (2021).  All Rights Reserved.

Abstract

   This document describes the proposed standard format of all future IIFRP Requests for Comment (RFCs)

Related RFCs:

   - [RFC #4: Clarifying the Scope of RFC #2](/rfc/RFC-4.html)

<span id="1">1.</span> **INTRODUCTION**

<span id="1.1">1.1.</span> Rationale and Scope

In general, a standards proposal should adopt the form of an RFC (Request for Comments) which seeks to solicit feedback from the IIFRP community at-large and develop a formal standard for a given food-related topic. However, as of yet, no standard exists to provide guidance to IIFRP members as how best to construct their proposals.

This document seeks to clarify this ambiguity and seeks to lay out a structure for future IIFRP members to follow when submitting their own RFCs in the future.

In the spirit of modeling its own recommendations, this document is constructed according to the structure it proposes. Where ambiguities remain, readers and prospective proposal writers are encouraged to follow the standards for RFCs proposed by the IETF.

<span id="1.2">1.2.</span> Terminology

   The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT",
   "SHOULD", "SHOULD NOT", "RECOMMENDED", "NOT RECOMMENDED", "MAY", and
   "OPTIONAL" in this document are to be interpreted as described in
   [IETF RFC2119][RFC2119].

   [RFC2119]: https://tools.ietf.org/html/rfc2119


<span id="2">2.</span> **STANDARD RFC FORMAT**

This section contains the detailed format specifications for an IIFRP RFC.

RFC sections must be numbered in ascending order. Top-level section titles SHOULD be in capital letters and bolded to improve readability. Subsections SHOULD be capitalized according to the [titlecase style guide](https://titlecase.com). Subsections SHOULD prefer numbers over letters.

<span id="2.1">2.1.</span> Document Header and Table of Contents

An RFC MUST contain a document header and table of contents according to the format described in this section.

The document header MUST contain a header containing the RFC number (as given by the IIFRP member proposing the RFC). This number MUST NOT use the number of an already existing RFC and SHOULD simply be the next number after the last published RFC. Administrators may adjust the exact number of an RFC prior to publication in the event that multiple RFCs are accepted with the same number.

The document header SHOULD also contain a publication date containing the year, month, and day that the RFC was published.

The RFC author MAY tag the RFC with categories that are relevant to topics already discussed or that are currently under discussion. These categories are informal and purely informative.

All submitted RFCs SHOULD include a status of either "Draft" or "Pending Comment" depending on whether the author considers the document in a draft stage or ready to accept feedback from the community at large. This designation is similar to the standards color codes explained below.

Proposals MUST include a type corresponding to an accepted color code. These codes are explained both in the table below and on the site's submission guidelines page. For simplicity, these types and colors are the same as the color codes used by the IETF.

Accepted Proposal Types &amp; Color Codes:

<style>
    table td { border: 1px solid #ccc; padding: 2px 6px; text-align: left; }
    table { border-collapse: collapse; }
</style>

|Type|Color|Hex|Description|
|---|---|
|Draft|Red|#F44|Any document that is in the process of being written.|
|Informational|Orange|#FA0|A document that is not considered accepted as standard, but provides additional context about a standards decision or comparisons of different or similar standards.|
|Experimental|Yellow|#EE0|Any document detailing either an experimental recipe or possibly research studies relating.|
|Best Common Practice|Magenta|#F4F|A document detailing a best practice. Normally these are for processes in preparation in general.|
|Proposed Standard|Indigo|#66F|Documents that are undergoing the acceptance process to become official standards.|
|Adopted Standard|Green|#4F4|Accepted community standards. These are the criteria for being an IIFRP Compliant Product.|
|Historic|Gray|#666|Previously accepted standards, or practices documents which are no longer relevant, but preserved for historical context.|
|Obsolete|Brown|#840|Previously accepted standards, or practices documents which are no longer accepted and have been superseded by another standard.|
|Unknown or Misc|White|#fff|Any document that does not fit into these categories or that the committee hasn’t assigned a designation.|

<br />

RFCs SHOULD also contain a list of authors, newline separated, and the submission month and year.

RFCs MUST include a section titled *Status of this Memo* containing one of the following accepted status messages:

Accepted Status Messages:

`This memo contains a proposed standard for the community. It makes no claim to enforce the proposal contained herein. Distribution of this memo is unlimited.`

RFCs MUST include the following copyright notice:

`Copyright (C) IIFRP (<year>). All Rights Reserved.`

It is RECOMMENDED that RFCs include an abstract explaining the goals and function of the proposed standard and how the proposed solution fits the problems described.

RFCs MUST contain an itemized table of contents.

**FORMAT EXAMPLE**:

Below is a sample RFC template.

    RFC #<number>: <RFC Title>
    <publication date>

    <relevant committee>
    Request for Comments: <number>
    Category: <category>
    Status: **<status>**

    <authors>
    <submission month year>

    Status of this Memo

    This memo contains a proposed standard for the community. It makes no claim to enforce the proposal contained herein. Distribution of this memo is unlimited.

    Copyright Notice

    Copyright (C) IIFRP (2021). All Rights Reserved.

    Abstract

    <abstract text>

    Table of Contents


<span id="2.2">2.2.</span> Introduction

An IIFRP RFC MUST contain an introduction describing the goals and rationale behind the proposed standard or draft. It is RECOMMENDED that this section be split into two subsections, one defining the rationale and scope and another detailing any unique or special terminology used by the specification in the RFC. In general, it is RECOMMENDED that standards adhere to the IETF recommended terminology and definitions, however RFCs MAY clarify additional terminology if necessary.

If, in the future, the IIFRP were to adopt its own set of standard terminology, separate from the IETF, then it is RECOMMENDED that standards prefer the former over the latter.

<span id="2.3">2.3.</span> Formal Specification

The RFC MUST include a formal specification, which can be laid out according to the author's preference. There need be no section titled "Formal Specification".

The purpose of these sections is to explain the proposed standard and clarify any ambiguity that may arise. Authors SHOULD strive to be clear and concise. They MAY include any diagrams that would be helpful to the reader. Diagrams should always be ASCII, or be images that are not embedded in the document, but are linked as external resources.

Lists of links to external resources and references are RECOMMENDED if they exist.

Draft RFCs MAY contain placeholders for required materials if they are not yet completed. Sections SHOULD denote incomplete contents with the following text: `[Placeholder]`

<span id="2.4">2.4.</span> Various Considerations

Immediately following the formal specification it is RECOMMENDED that RFCs contain sections detailing the various types of considerations that are relevant to the situations presented in, or arising from, the adoption of the proposed standard. For example, it may be proper to denote the ethical considerations of a standard that requires the extensive use of meat products and therefor the additional cultivation and slaughter of cattle, poultry, or other animal resources. Ethical considerations may also include discussions regarding the relationship between the server and the client as the given RFC may denote.

Authors MAY wish to discuss international considerations, such as how their standard would affect or be affected by cultural and international influences. This may include considerations around the lack of available ingredients in some regions or the various cultural influences of a given food item.

<span id="2.5">2.5.</span> Acknowledgements

An RFC MUST provide an Acknowledgements section containing the contact information of any relevant authors who wish to act as points of contact for the proposal.

The Acknowledgements section must contain at least one point of contact and email address. Additional names are not required to have an email address.

Pseudonyms are acceptable as author names in RFCs assuming they are appropriate for common, decent use in a public setting.


<span id="3">3.</span> **PROPOSAL UPDATES**

Assuming the author wishes to propose updates or changes to their proposal, and assuming the proposal has not yet been accepted as a formal specification, authors may include changes without denoting the nature of the edit directly by resubmitting their RFC in the mailing list or submitting a pull request on the IIFRP repository. A description of edits made should be included in a Changes section before the Acknowledgements.

RFCs that have been accepted as standards may not be amended except by IIFRP staff to include references to newer or additional related resources. Proposed changes to an accepted RFC must be submitted as their own RFC.


<span id="4">4.</span> **EXTENSIBILITY CONSIDERATIONS**

Currently this document describes the format of an RFC, but RFCs are only one type of document that may be submitted. It is RECOMMENDED that the IIFRP continue to document other forms of submissions in the future.

It is also RECOMMENDED that the IIFRP clarify the process for submitting RFCs in another proposal.

It is also RECOMMENDED that the IIFRP clarify the existant committees for RFC authors to refer to.


<span id="5">5.</span> **INTERNATIONAL CONSIDERATIONS**

It is RECOMMENDED that the IIFRP standards body consider translating this RFC into as many languages as possible as it is expected that submissions could arise from all over the world.


<span id="6">6.</span> **ACKNOWLEDGEMENTS**

   Brian Schrader<br />
   email: brian "at" brianschrader "dot" com

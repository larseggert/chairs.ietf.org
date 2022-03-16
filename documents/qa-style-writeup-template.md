---
title: Document Shepherd Writeup Template for Working Group and Individual Submissions
description: As required by RFC 4858, this is the current template for the Document Shepherd Write-Up. Changes are expected over time.
published: true
date: 2022-03-04T21:56:22.746Z
tags: 
editor: markdown
dateCreated: 2021-12-20T22:53:41.098Z
---

*This version is dated 2 March 2022.*

Thank you for your service as a document shepherd. Among the responsibilities is answering the questions in this writeup to give helpful context to Last Call and Internet Engineering Steering Group ([IESG](https://www.ietf.org/about/groups/iesg/)) reviewers, and your diligence in completing it is appreciated. The full role of the shepherd is further described in [RFC 4858](https://www.rfc-editor.org/rfc/rfc4858.html), and informally. You will need the cooperation of authors to complete these checks.

Note that some numbered items contain multiple related questions; please be sure to answer all of them.

## Document History
*Option 1: For documents coming from IETF Working Groups*

(1) Does the working group (WG) consensus represent the strong concurrence of a few individuals, with others being silent, or did it reach broad agreement?

(2) Was there controversy about particular points, or were there decisions where the consensus was particularly rough? 

*Option 2: For individual documents*

(1) Was the document considered in any WG, and if so, why was it not adopted as a work item there?
 
(2) Was there controversy about particular points that caused the WG to not adopt the document?

---
 
(3) Has anyone threatened an appeal or otherwise indicated extreme discontent? If so, please summarize the areas of conflict in separate email messages to the responsible Area Director. (It should be in a separate email because this questionnaire is publicly available.) 

(4) For protocol documents, are there existing implementations of the contents of the document? Have a significant number of potential implementers indicated plans to implement? Are any existing implementations reported somewhere, either in the document itself (as [RFC 7942](https://www.rfc-editor.org/rfc/rfc7942.html) recommends) or elsewhere (where)?

## Additional Reviews

(5) Does this document need review from other IETF working groups or external organizations? Have those reviews occurred?

(6) Describe how the document meets any required formal expert review criteria, such as the MIB Doctor, YANG Doctor, media type, and URI type reviews. 

(7) If the document contains a YANG module, has the final version of the module been checked with any of the recommended validation tools (https://trac.ietf.org/trac/ops/wiki/yang-review-tools) for syntax and formatting validation? If there are any resulting errors or warnings, what is the justification for not fixing them at this time? Does the YANG module comply with the Network Management Datastore Architecture (NMDA) as specified in [RFC 8342](https://www.rfc-editor.org/rfc/rfc8342.html)?

(8) Describe reviews and automated checks performed to validate sections of the final version of the document written in a formal language, such as XML code, BNF rules, MIB definitions, CBOR’s CDDL, etc.

## Document Shepherd Checks
(9) Based on the shepherd’s review of the document, is it their opinion that this document is needed, clearly written, complete, correctly designed, and ready to be handed off to the responsible Area Director?

(10) Several IETF Areas have assembled lists of common issues that their reviewers encounter. These are linked from https://trac.ietf.org/trac/iesg/wiki/ExpertTopics. Do any such issues remain that would merit specific attention from subsequent reviews?

(11) What type of RFC publication is being requested on the IETF stream (Best Current Practice, Proposed Standard, Internet Standard, Informational, Experimental, or Historic)? Why is this the proper type of RFC? Do all datatracker state attributes correctly reflect this intent?

(12) Has the interested community confirmed that any and all appropriate IPR disclosures required by [BCP 78](https://www.rfc-editor.org/info/bcp78) and [BCP 79](https://www.rfc-editor.org/info/bcp79) have been filed? If not, explain why. If yes, summarize any discussion and conclusion regarding the intellectual property rights (IPR) disclosures, including links to relevant emails.

(13) Has each Author or Contributor confirmed their willingness to be listed as such? If the number of Authors/Editors on the front page is greater than 5, please provide a justification.

(14) Identify any remaining I-D nits in this document. (See http://www.ietf.org/tools/idnits/ and the checkbox items found in Guidelines to Authors of Internet-Drafts). Simply running the idnits tool is not enough;  please review the entire guidelines document.

(15) Should any informative references be normative or vice-versa?

(16) List any normative references that are not freely available to anyone. Did the community have sufficient access to review any such normative references?

(17) Are there any normative downward references (see [RFC 3967](https://www.rfc-editor.org/rfc/rfc3967.html), [BCP 97](https://www.rfc-editor.org/info/bcp97))? If so, list them. 

(18) Are there normative references to documents that are not ready for advancement or are otherwise in an unclear state? If they exist, what is the plan for their completion?

(19) Will publication of this document change the status of any existing RFCs? If so, does the Datatracker metadata correctly reflect this and are those RFCs listed on the title page, in the abstract, and discussed in the introduction? If not, explain why and point to the part of the document where the relationship of this document to these other RFCs is discussed.

(20) Describe the document shepherd's review of the IANA considerations section, especially with regard to its consistency with the body of the document. Confirm that all aspects of the document requiring IANA assignments are associated with the appropriate reservations in IANA registries. Confirm that any referenced IANA registries have been clearly identified. Confirm that each newly created IANA registry specifies its initial contents, allocations procedures, and a reasonable name (see [RFC 8126](https://www.rfc-editor.org/rfc/rfc8126.html)). 

(21) List any new IANA registries that require Designated Expert Review for future allocations. Are the instructions to the Designated Expert clear? Please include suggestions of designated experts, if appropriate.

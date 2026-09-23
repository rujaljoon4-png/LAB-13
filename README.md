This repository contains my Lab 13 practical work for the Generative AI for Business course as a BBA Aviation Management student. The lab focuses on document-grounded question answering and the use of Retrieval-Augmented Generation (RAG) to improve the reliability and traceability of AI-generated aviation responses.

The activity compares an ungrounded AI answer with a document-grounded answer based on an instructor-provided fictional airline policy. The ungrounded response is analysed to identify claims related to refund eligibility, processing times, required documents, exceptions and promised actions, and each claim is classified as known, uncertain or unsupported.

After uploading the policy document, a grounded prompt is used to generate an answer based only on the supplied source, with citations for important claims. The lab emphasises manually checking citations and their surrounding context rather than assuming that a citation automatically proves a claim.

A key part of the activity is the **Claim → Source → Match → Context → Action** verification routine. The lab also tests whether the grounded system safely handles missing information, unsupported questions, conditional policies and requests for private information.

Additional work includes creating a document-grounded passenger response, conducting a RAG risk audit, identifying limitations such as outdated documents, retrieval errors and missed exceptions, and completing a reflection and AI-use disclosure. The final activity is documented and uploaded to the GitHub portfolio while protecting confidential policy information.

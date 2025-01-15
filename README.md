# LLOD Quality assessment
Replication package supporting the article 

_Maria Angela Pellegrino, Pasquale Esposito, and Gabriele Tuozzo. 2025. FAIRness of the Linguistic Linked Open Data Cloud: an Empirical Investigation. Submitted to the Special Issue on Data quality dimensions in Data FAIRification design and processes (JDIQ ’25)_

The project contains:
- **LLODsurvey-0_initial.csv** - csv containing all the 1,788 articles returned by Scopus running the query 
_TITLE-ABS-KEY ( ("knowledge graph*" OR "linked data" OR "linked open data" ) AND ( linguistic* )_
and posing January 2014 - March 2024 as timeframe, only considering articles fully written in English.
Articles are attached to codes by two reviewers and their agreement.
- **LLODsurvey-1_eligible.csv** - csv containing the 457 articles considered eligible according to the following _inclusion criteria_:
• Published between January 2014 and March 2024.
• Fully written in English, beyond just the abstract.
• Published in a peer-reviewed venue.
• Freely accessible.
• Focus on the definition or utilization of linguistic data published in accordance with Semantic Web technologies.
- **LLODsurvey-2_included-USE.csv** - csv containing the 92 articles talking about the REUSE of Linguisitc Linked Open Data (LLOD).
- **LLODsurvey-2_included-DEF.csv** - csv containing the 89 articles talking about the DEFINITION of LLOD.
- **LLODsurvey-3_qualityAssessment-LLODResources.csv** - csv containing the quality assessment of the 69 included linguistic resources
- **LLODsurvey-3_usedVocabularies.csv** - csv documenting used vocabularies of resources indexed in the [LLOD Cloud](https://linguistic-lod.org/llod-cloud).
- **LLODsurvey-3_qualityAssessment-workingSPARQLendpoint.csv** - csv documenting the quality assessment of linguistic resources computed via [KGHeartBeat](http://www.isislab.it:12280/kgheartbeat).
- **LLODsurvey-3_mediatypes.csv** - csv documenting mediatypes as reported in the LLOD Cloud.

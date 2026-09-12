# TRACK-Neuro: Transforming Research into Annotated Computable Knowledge in Neuroscience
A workflow for transforming fragmented primary research into structured, computable biological knowledge.

Focusing on Neuroscience, TRACK-Neuro provides an organized workflow for converting experimentally validated findings from primary research articles into structured Scientific Meta Summaries (SMS), enabling quantitative analysis, knowledge integration and network construction.

# Overview

Biological knowledge is dispersed in published literature. Streamlining such knowledge scattered in peer-reviewed primary research articles for knowledge synthesis can be an alarming task with no quality control, weighing in evidence strength. TRACK-Neuro includes a systematic workflow to: evaluate primary literature using hypothesis-driven search strategies, identify experimentally supported functional relationships, curate Scientific Meta Summaries (SMS), preserve experimental context and provenance, compute Functional Interaction Scores (FIS), assemble structured knowledge into directed network graphs, suitable for downstream analysis.

# Repository contents
TRACK-Neuro/

README.md

LICENSE

SMS_Template_Sept2026.xlsx

TRACK-Neuro_SMS_Sept2026.csv

TRACK-Neuro_Node_Table_Sept2026.csv

TRACK-Neuro_Edge_Table_Sept2026.csv

TRACK-Neuro_Cytoscape_Session_Sept2026.cys

Figures/

Documentation/

# Workflow 
1. Literature search and screening Primary Research Articles (PRAs): Apply inclusion/exclusion criteria
2. PRA evaluation
3. Catalog Scientific Meta Summary (SMS)
4. Compute Functional Interaction Score (FIS)
5. Generate node and edge tables
6. Create annotated network graph in Cytoscape version >= 3.10.3


# Input
1. PubMed for article search.
2. 'TRACK-Neuro_SMS_Template_BioProtocol.xlsx' for SMS fields, controlled vocabulary, metadata schema and reference links.
3. Node and Edge Tables for network graph generation using Cytoscape.

# Output
Scientific Meta Summaries (SMS)
Functional Interaction Scores (FIS)
Network/Knowledge Graph: Node tables, Edge tables

# Example application

The current implementation demonstrates the workflow using neuroimmune crosstalk, integrating experimentally supported interactions between neurons and microglia. See example annotated network graphs.

Future implementations may extend the workflow to other biological domains.

# Software

* Required

 - Microsoft Excel or equivalent (e.g., REDCap, Google Sheets)
 - Cytoscape ≥ 3.10.3
 - PubMed

* Optional

 - Google Forms

* Code
None

# Citation

If you follow TRACK-Neuro workflow, please cite:

<upcoming>

# Contact

Sharmila Venugopal (venugopallabcsulb@gmail.com), Department of Chemistry & Biochemistry, California State University Long Beach

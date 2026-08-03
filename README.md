# TRACK-Neuro: Transforming Research into Annotated Computable Knowledge
A workflow for transforming fragmented primary research into structured, computable biological knowledge.

Focusing on Neuroscience, TRACK-Neuro provides an organized workflow for converting experimentally validated findings from primary research articles into structured Scientific Meta Summaries (SMS), enabling quantitative analysis, knowledge integration and network construction.

# Overview

Biological knowledge is dispersed in published literature. Streamlining such knowledge scattered in peer-reviewed primary research articles for knowledge synthesis can be an alarming task with no quality control, weighing in evidence strength. TRACK-Neuro includes a systematic workflow to: evaluate primary literature using hypothesis-driven search strategies, identify experimentally supported functional relationships, curate Scientific Meta Summaries (SMS), preserve experimental context and provenance, compute Functional Interaction Scores (FIS), assemble structured knowledge into directed network graphs, suitable for downstream analysis.

# Repository contents
TRACK-Neuro/

README.md

LICENSE

SMS_Template.xlsx

Example_SMS.csv

Example_Node_Table.csv

Example_Edge_Table.csv

Example_Cytoscape_Session.cys

Figures/

Documentation/

# Workflow 
1. Literature screening
2. Primary research article evaluation
3. Scientific Meta Summary (SMS) curation
4. Functional Interaction Score (FIS) computation
5. Generation of node and edge tables
6. Visualization in Cytoscape

# Input
See TRACK-Neuro-Curation-Template for input fields, controlled vocabulary, metadata schema and reference links

# Output
Scientific Meta Summaries (SMS)
Functional Interaction Scores (FIS)
Network modeling: Node tables, Edge tables

# Example application

The current implementation demonstrates the workflow using neuroimmune crosstalk, integrating experimentally supported interactions between neurons and microglia.

Future implementations may extend the workflow to other biological domains.

# Software

* Required

 - Microsoft Excel or equivalent (e.g., REDCap, Google Sheets)
 - Cytoscape ≥ 3.10
 - PubMed

* Optional

 - Google Forms

# Citation

If you follow TRACK-Neuro workflow, please cite:

<upcoming>

# License

MIT License

# Contact

Sharmila Venugopal (venugopallabcsulb@gmail.com), Department of Chemistry & Biochemistry, California State University Long Beach

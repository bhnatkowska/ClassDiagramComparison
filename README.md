# ClassDiagramComparison
Antr_usage is a tool for class diagram comparison. It parses class diagrams specified in plant uml format, counts and prints comparison metrics.
It was complied for Windows OS.
To run the tool use:
- run path_to_class_diagram_1 path_to_class_diagram2 or
- antr_usage path_to_class_diagram_1 path_to_class_diagram2

Example: run diagrams/ontology.puml diagrams/T1a.puml

It is assumed that the first diagram presents an ontology domain, and the second diagram - its representation (probably of bad quality).
The tool calculates the consistency measures between diagrams at the level of classes and associations as well as the measure for all elements.
The measures take values from 0 (lack of consistency) to 1 (full consistency).

The samples directory consists raw data from which class diagram (T1a, T1b) were generated.
ClassicModels.xls is the orginal source of data from which other samples were generated.
The names of samples correspond to the names of class diagrams the samples represent.

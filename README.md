# Extension of KgExpander
This is a forked repository of the KgExpender tool at https://github.com/4DataShare/AbbExpansion. 
We extended KgExpander to be used by [RENAS](https://github.com/salab/RENAS).
We also prepared Gradle configurations for the ease of building jar files.

### code/ParseCode
This component extracts identifier information from source code and analyzes their relationships using AST.

### code/SemanticExpand
This component finds words before being abbreviated by tracing relationships between identifiers and using dictionaries of abbreviation.

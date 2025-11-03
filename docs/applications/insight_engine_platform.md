# Insight Engine - Data Analysis and Visualization Platform

## Overview

The **Insight Engine** is Science Central's comprehensive platform for data analysis and visualization, designed to help researchers explore, interpret, and communicate research insights effectively.

### Primary Purpose
"Analyze and visualize your data to explore, interpret, and communicate research insights"

### Platform Description
"This platform provides a centralized environment for data analysis and visualization"

### Tagline
"Tell the story"

## Architecture

The Insight Engine consists of two main components:

1. **Explore** - Python-focused analysis environment
2. **MAP (Multi-omics Analysis Portal)** - Specialized multi-omics analysis suite

---

## Component 1: Explore Environment

### Overview
**Tagline**: "Accelerate Your Python Explorations"

**Tooltip Description**: "A JupyterLab environment optimized for creating streamlined plots, conducting analyses, and running scripts in Python."

### Directly Observed Features

#### JupyterLab Interface (Observed)
When accessed, the Explore environment opens a JupyterLab interface with:

- **Launcher Tab**: Shows available options for creating new work
- **Python 3 (ipykernel)**: Available for notebook and console creation
- **File Browser**: Standard JupyterLab file navigation
- **Menu Structure**: File, Edit, View, Run, Kernel, Tabs, Settings, Help

#### Launcher Options (Directly Observed)
The JupyterLab launcher shows these creation options:

**Notebook Section:**
- Python 3 (ipykernel) - for creating notebooks

**Console Section:**
- Python 3 (ipykernel) - for interactive console

**Other Section:**
- Terminal - "Start a new terminal session"
- Text File - "Create a new text file"
- Markdown File - "Create a new markdown file"
- Python File - "Create a new Python file"
- Show Contextual Help - "Live updating code documentation from the active kernel"

#### Interface Elements
- **Status Bar**: Shows kernel connection status
- **Sidebar Tabs**: Property Inspector, Debugger available
- **Simple Interface Toggle**: Available in bottom status bar

---

## Component 2: MAP (Multi-omics Analysis Portal)

### Overview
**Full Name**: Multi-omics Analysis Portal
**Tagline**: "Multi-omics Analysis Portal"

**Description**: "A suite of analysis tools built to filter, analyze, and integrate multi-omics data"

### Core Philosophy
MAP serves as a comprehensive ecosystem for multi-omics research, providing specialized tools for filtering, analyzing, and integrating complex biological datasets.

## MAP Platform Features

### Data Management System

#### Data Upload
- **Multiple Format Support**: Various omics data formats
- **Batch Upload**: Process multiple datasets simultaneously
- **Validation Tools**: Automatic data quality checks
- **Metadata Integration**: Rich annotation and documentation

#### File Management
- **Centralized Storage**: Unified file management system
- **Input/Output Tracking**: Complete data lineage documentation
- **Version Control**: Track data and analysis versions
- **Sharing Capabilities**: Collaborative data access

#### Job Management
- **Status Monitoring**: Real-time analysis job tracking
- **Queue Management**: Efficient resource allocation
- **Error Handling**: Comprehensive error reporting and recovery
- **Notification System**: Updates on job completion and status

### Application Ecosystem

#### MAP Store
The MAP Store serves as a marketplace of specialized analysis applications with comprehensive filtering capabilities:

##### Data Type Support
- **Peptide-level Data**:
  - Label Free proteomics
  - Isobaric proteomics
- **Protein-level Data**:
  - Label Free proteomics
  - Isobaric proteomics
- **Lipidomics Data**:
  - Positive ion mode
  - Negative ion mode
- **Metabolomics Data**:
  - GC/LC-MS based
  - NMR based
- **Transcriptomics Data**:
  - RNA-seq
- **Mass Spectrometry Data**:
  - FT-MS (Fourier Transform Mass Spectrometry)

##### Analysis Goals
- **Quality Control (QC)**: Data validation and quality assessment
- **Exploratory Data Analysis (EDA)**: Initial data investigation
- **Differential Analysis**:
  - Differential abundance analysis
  - Differential expression analysis
- **Statistical Analysis**:
  - Advanced statistical methods
  - ANOVA (Analysis of Variance)
  - G-test statistical testing
- **Data Processing**: Preprocessing and normalization
- **Data Integration**: Multi-omics data combination
- **Database Mapping**: Annotation and pathway mapping
- **Machine Learning**: Statistical learning approaches
- **Visualization**: Interactive and static plotting
- **Clustering**: Unsupervised pattern discovery

##### Experimental Design Support
- **Single Factor Experiments**: One-variable studies
- **Two Factor Experiments**: Multi-variable designs
- **Multi-omics Studies**: Integrated omics approaches
- **Pan-omics Research**: Comprehensive omics integration

##### Smart Filtering
- **Uploaded Data Filtering**: Filter applications based on available datasets
- **Capability Matching**: Match tools to research requirements
- **Workflow Optimization**: Suggest optimal analysis pipelines

### Available Applications

#### 1. PMart
**Description**: Statistical analysis and visualization of proteomics, metabolomics, lipidomics, and transcriptomics data

**Citation**: Stratton, K.G.; Claborne, D.M.; Degnan, D.J.; Richardson, R.E.; White, A.M.; McCue L.A.; Webb-Robertson B.M.; Bramer, L.M. PMart web application: marketplace for interactive analysis of panomics data. *Journal of Proteome Research* 2024, 23(8), 4736-4741. DOI: 10.1021/acs.jproteome.3c00512

**Backend Code Citation**: Degnan D.J.; Stratton, K.G.; Richardson R.E.; Claborne, D.M.; Martin, E.A.; Johnson, N.A.; Leach, D.T; Webb-Robertson B.M.; Bramer, L.M. pmartR 2.0: A quality control, visualization, and statistics pipeline for multiple omics datatypes. *Journal of Proteome Research* 2023, 22(2). DOI: 10.1021/acs.jproteome.2c00610

#### 2. iPMart
**Description**: Statistical analysis, integration, and visualization of multi-omics data

**Integration Code Citation**: Rohart, F.; Gauiter, B.; Singh, A.; Cao, K.L. mixOmics: an R package for omics feature selection and multiple data integration. *PLOS Computational Biology* 2017, 13(11), e1005752. DOI: 10.1371/journal.pcbi.1005752

**Application Citation**: In preparation

#### 3. MODE
**Description**: Create shareable HTML displays of proteomics, metabolomics, lipidomics, and transcriptomic data

**Citation**: Degnan, D.J.; Claborne, D.M.; Richardson, R.E.; Strauch, C.W.; Glasscock, E.C.; Veličković, D.; Burnum-Johnson, K.E.; Webb-Robertson, B.J.; Stratton, K.G; Bramer, L.MMODE: A web application for interactive visualization and exploration of omics data. *Journal of Proteome Research* 2025, 24(2), 911-918. DOI: 10.1021/acs.jproteome.4c00650

#### 4. FREDA
**Description**: Analyze and visualize FT-MS data

**Citation**: Degnan, D.J.; Claborne, D.M; White, A.M.; Akers, S.M.; Winans, N.M.; Corilo, Y.E.; Strauch, C.W.; Bailey, V.L.; McCue, L.A.; Stratton, K.G.; Bramer, L.M. FREDA: A web application for the processing, analysis, and visualization of Fourier-transform mass spectrometry data. *Rapid Communications in Mass Spectrometry* 2024, 39(7), e9880. DOI: 10.1002/rcm.9980

#### 5. SLOPE
**Description**: Machine learning for 'omics and multi-omics datasets

**Citation**: In preparation
**Backend Code Citation**: In preparation

### Workflow Design System

#### Build with Uploaded Data
- **Dataset Selection**: Choose from uploaded datasets
- **Automatic Recommendations**: System-generated workflow suggestions
- **Custom Workflows**: User-defined analysis pipelines
- **Validation Tools**: Workflow testing and verification

#### Build with Scenarios
- **Hypothetical Analysis**: Design workflows for future studies
- **Template Workflows**: Pre-built analysis templates
- **Methodology Planning**: Experimental design optimization
- **Resource Estimation**: Computational requirement planning

### Advanced Features

#### Workflow Management
- **Pipeline Creation**: Visual workflow builder
- **Dependency Management**: Automatic handling of analysis dependencies
- **Parallel Processing**: Optimize computational efficiency
- **Error Recovery**: Robust error handling and recovery mechanisms

#### Integration Capabilities
- **Cross-Application Data Flow**: Seamless data transfer between tools
- **Format Conversion**: Automatic data format handling
- **Metadata Preservation**: Maintain data provenance and annotations
- **Version Tracking**: Complete analysis history documentation

## Getting Started with Insight Engine

### Choosing the Right Component

#### Use Explore When:
- Conducting Python-focused analysis
- Creating custom visualizations
- Developing analysis scripts
- Performing exploratory data analysis
- Need flexible, general-purpose analysis environment

#### Use MAP When:
- Working with multi-omics datasets
- Need specialized omics analysis tools
- Require integrated analysis workflows
- Want to use established analysis pipelines
- Need comprehensive data management features

### Initial Setup

#### For Explore:
1. Access Insight Engine from Science Central main page
2. Select "Explore" environment
3. Create new notebook or console session
4. Begin Python-based analysis

#### For MAP:
1. Navigate to Multi-omics Analysis Portal
2. Upload your datasets through Data Upload
3. Explore applications in MAP Store
4. Design workflow or select pre-built analysis
5. Monitor progress through Job Status

## Best Practices

### Data Analysis Workflow
1. **Data Quality Assessment**: Begin with quality control checks
2. **Exploratory Analysis**: Understand data characteristics
3. **Method Selection**: Choose appropriate analysis methods
4. **Validation**: Validate results with independent approaches
5. **Documentation**: Maintain thorough analysis documentation
6. **Sharing**: Use appropriate sharing and collaboration tools

### Visualization Guidelines
- **Clear Communication**: Focus on story-telling with data
- **Appropriate Chart Types**: Match visualization to data type
- **Color Accessibility**: Consider colorblind-friendly palettes
- **Interactive Elements**: Leverage interactive capabilities when appropriate
- **Export Quality**: Ensure publication-ready output quality

## Training and Support

### Educational Resources
- **Tutorial Videos**: Step-by-step instructional content
- **Documentation**: Comprehensive user guides
- **Example Workflows**: Pre-built analysis examples
- **Best Practices Guides**: Methodology recommendations

### Community Support
- **User Forums**: Peer-to-peer assistance
- **Expert Consultations**: Access to domain specialists
- **Webinar Series**: Regular training sessions
- **Case Studies**: Real-world application examples

### Technical Support
- **Help Desk**: Direct support via sc.support@pnnl.gov
- **Bug Reporting**: Issue tracking and resolution
- **Feature Requests**: User-driven development priorities
- **System Status**: Platform health and maintenance updates

## Future Development

### Planned Enhancements
- **Additional Omics Types**: Expanded data type support
- **Enhanced Machine Learning**: Advanced AI/ML capabilities
- **Cloud Integration**: Hybrid cloud computing options
- **Mobile Access**: Tablet and mobile device support

### Community Contributions
- **User-Contributed Applications**: Community-developed tools
- **Workflow Sharing**: Public workflow repository
- **Method Development**: Collaborative method development
- **Open Source Components**: Community-maintained tools

For comprehensive support and detailed documentation, contact sc.support@pnnl.gov
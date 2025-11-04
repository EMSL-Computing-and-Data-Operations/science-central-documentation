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

#### JupyterLab Interface
The Explore environment opens a JupyterLab interface with:

- **Launcher Tab**: Shows available options for creating new work
- **Python 3 (ipykernel)**: Available for notebook and console creation
- **File Browser**: Standard JupyterLab file navigation
- **Menu Structure**: File, Edit, View, Run, Kernel, Tabs, Settings, Help

#### Launcher Options
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



#### 2. iPMart
**Description**: Statistical analysis, integration, and visualization of multi-omics data



#### 3. MODE
**Description**: Create shareable HTML displays of proteomics, metabolomics, lipidomics, and transcriptomic data



#### 4. FREDA
**Description**: Analyze and visualize FT-MS data



#### 5. SLOPE
**Description**: Machine learning for 'omics and multi-omics datasets



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
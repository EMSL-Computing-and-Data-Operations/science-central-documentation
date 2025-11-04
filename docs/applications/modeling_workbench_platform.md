# Modeling Workbench - Machine Learning and Simulation Platform

## Overview

The **Modeling Workbench** is one of the main components of Science Central™.

### Primary Purpose
"Build, train, and deploy machine learning and simulation models"

### Platform Description
"Platform provides a centralized environment for data scientists to build, train, and deploy machine learning models"

### Tagline
"Explore your ideas"

## Architecture

The Modeling Workbench consists of three main components:

1. **Data Science Environment**
2. **TensorFlow Environment**
3. **Tahoma OnDemand Computing Infrastructure**

---

## Component 1: Data Science Environment

### Overview
**Tagline**: "Drive Insights With Multi-language Tools"

**Tooltip Description**: "A JupyterHub environment fully equipped with a suite of libraries designed for powerful data processing and analysis, supporting Python, R, and Julia."

### Directly Observed Features

#### JupyterLab Interface
When accessed, the Data Science environment opens a JupyterLab interface with:
- File browser on the left sidebar
- Main workspace with notebook tabs
- Menu bar with File, Edit, View, Run, Kernel, Tabs, Settings, Help
- Toolbar with common actions (save, add cell, cut, copy, paste, run, restart)
- Status bar showing kernel information

#### Interface Elements
- **File Browser**: Shows `/home/jovyan` directory
- **Notebook Environment**: Interactive notebook with Python 3 (ipykernel)
- **Cell Types**: Code, Markdown, Raw options available
- **Kernel Status**: "Python 3 (ipykernel) | Connecting"
- **Tabs**: "File Browser", "Running Terminals and Kernels", "Table of Contents", "Extension Manager"

#### Observed Functionality
- Code cells can be executed
- File upload capability through file browser
- New file creation options (notebook, folder, etc.)
- Terminal access available
- Save and checkpoint functionality

---

## Component 2: TensorFlow Environment

### Overview
**Tagline**: "Advance Your Deep Learning Journey"

**Tooltip Description**: "A JupyterHub environment designed with all the necessary libraries for conducting deep learning tasks using TensorFlow."

### Information
When clicking on the TensorFlow option, it opened a new browser tab but the specific interface details were not fully explored during the session.

---

## Component 3: Tahoma OnDemand

### Overview
**Tagline**: "Compute Infrastructure"

**Tooltip Description**: "Workspace to manage files, jobs, run GUI applications, and connect to an interactive shell."

### Directly Observed Features

#### Open OnDemand Dashboard
When accessed, Tahoma OnDemand opens to an Open OnDemand interface with:
- **URL**: https://tahoma-ondemand.emsl.pnnl.gov/pun/sys/dashboard
- **Version**: OnDemand version 3.1.14
- **Navigation Menu**: Apps, Files, Jobs, Clusters, Interactive Apps, My Interactive Sessions, Help

#### Available Applications
The dashboard shows "Pinned Apps" with three main applications:

1. **Cluster Desktop**
   - Description: "System Installed App"
   - Provides desktop environment access

2. **Jupyter Notebook/Lab**
   - Description: "System Installed App"
   - Jupyter logo displayed
   - Alternative notebook access

3. **RStudio Server**
   - Description: "System Installed App"
   - RStudio logo displayed
   - R statistical computing environment

#### Interface Description
- **Platform Description**: "OnDemand provides an integrated, single access point for all of your HPC resources"
- **Footer**: "Powered by Open OnDemand" with version information

---

## Getting Started

### Access Instructions
1. Navigate to Science Central main page (https://sc.emsl.pnnl.gov/)
2. Select "Modeling Workbench" from the main modules
3. Choose from the three available environments:
   - Click "Data Science" for the JupyterHub environment
   - Click "TensorFlow" for deep learning environment
   - Click "Tahoma OnDemand" for HPC access

### Environment Selection
Based on the tooltip descriptions:
- **Data Science**: For multi-language data processing and analysis (Python, R, Julia)
- **TensorFlow**: For deep learning tasks using TensorFlow
- **Tahoma OnDemand**: For file management, job submission, GUI applications, and shell access

## Integration with Science Central

The Modeling Workbench is one of the main components accessible through the Science Central navigation, alongside:
- All Modules (main dashboard)
- Proposal Management
- LIMS
- Data Portal
- Insight Engine

## Support

For technical support or questions about the Modeling Workbench, contact sc.support@pnnl.gov
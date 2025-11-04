# Science Central Quick Start Guide

## Getting Started with Science Central™

### Platform Access
1. **Navigate to**: https://sc.emsl.pnnl.gov/
2. **Dashboard**: Access the All Modules view
3. **Selection**: Choose the appropriate tool for your research

### Component Selection Guide

#### Choose **Proposal Management** when you need to:
- Submit research proposals and letters of intent (LOI)
- Track the status of submitted proposals
- Manage user projects and experiments
- Schedule experiments and instrument time
- Access funding and collaboration opportunities
- View and manage publication requirements

#### Choose **Data Portal** when you need to:
- Search and discover scientific datasets
- Access released datasets from completed projects
- Browse MONet (Molecular Observation Network) data
- Download datasets for analysis
- Explore research data by project, instrument, or researcher
- Find datasets to enhance your research findings

#### Choose **Sample Submission (LIMS)** when you need to:
- Submit sample metadata for laboratory analysis
- Track sample shipment and analysis status
- Download metadata templates
- Manage sample information and workflows
- Access reviewer tables for sample status

#### Choose **L7 Enterprise Science Platform** when you need to:
- Manage laboratory information systems
- Track samples, projects, and workflows
- Access comprehensive LIMS functionality
- Monitor analysis progress and results
- Manage laboratory inventory and equipment
- Create and manage experimental workflows

#### Choose **Circles** when you need to:
- Collaborate with other researchers
- Share research findings
- Connect with peers in your field
- Participate in collaborative projects
- Access shared resources and datasets

#### Choose **Modeling Workbench** when you need to:
- Develop machine learning models
- Perform statistical analysis with Python, R, or Julia
- Train deep learning models with TensorFlow
- Access high-performance computing resources
- Run batch processing jobs

#### Choose **Insight Engine** when you need to:
- Create data visualizations
- Perform exploratory data analysis
- Analyze multi-omics datasets
- Use specialized bioinformatics tools
- Build interactive dashboards

## Quick Start Workflows

### For Proposal Submission and Management

#### Getting Started with Proposals
1. **Access**: Select Proposal Management from the main menu
2. **Login**: Authenticate through NEXUS User Portal
3. **Navigate**: Use the dashboard to access key functions:
   - **Proposals/Projects**: Submit new proposals and manage existing ones
   - **Schedule Experiments**: Book instrument time and plan experiments
   - **Get Data**: Access your experimental data and results
   - **Publications**: Manage publication requirements and submissions
4. **Submit**: Click "Submit a Proposal/LOI" to start a new proposal
5. **Track**: Monitor proposal status and project progress through the dashboard

#### Key Features Available:
- **ORCID Integration**: Link your ORCID profile for streamlined submission
- **Training Modules**: Access required training for facility use
- **Reviews**: Participate in the peer review process
- **Sample Status**: Track sample processing (coming soon)

### For Data Discovery and Access

#### Getting Started with Data Portal
1. **Access**: Select Data Portal from the main menu
2. **Browse**: Explore available datasets using multiple views:
   - **All Data**: Browse complete dataset collection
   - **MONet**: Access Molecular Observation Network datasets
3. **Search**: Use search functionality to find specific datasets:
   - Search by project title, abstract, or ID
   - Filter by released data, project, or instrument group
4. **Select**: Choose datasets of interest and review metadata
5. **Download**: Access and download datasets for your research

#### Dataset Information Includes:
- **Project Details**: Principal investigator, project duration, institution
- **Data Volume**: Number of uploads and total data size
- **Research Context**: Project abstracts and research objectives
- **Data Policy**: Access to data usage policies and guidelines

### For Sample Management and LIMS

#### Getting Started with Sample Submission
1. **Access**: Navigate to LIMS → Sample Submission
2. **Templates**: Download metadata templates for sample preparation
3. **Submit**: Create new shipment applications with sample metadata
4. **Track**: Monitor shipment status and processing progress
5. **Review**: Access reviewer tables for detailed sample information

#### Getting Started with L7 Platform
1. **Access**: Navigate to LIMS → L7 for comprehensive laboratory management
2. **Dashboard**: View key metrics and recent activity
3. **Manage**: Access various laboratory functions:
   - **Entities**: Register and manage laboratory entities
   - **Samples**: Track sample workflows and status
   - **Projects**: Manage experimental projects
   - **Analysis**: Monitor analytical processes
   - **Inventory**: Manage laboratory inventory
   - **Equipment**: Track instrument usage and maintenance

#### Key L7 Capabilities:
- **Workflow Management**: Design and execute analytical workflows
- **Data Integration**: Connect sample metadata with analytical results
- **Quality Control**: Monitor analytical quality and compliance
- **Collaboration**: Share data and workflows with team members

### For New Data Science Users

#### Getting Started with Python Analysis
1. **Access**: Select Modeling Workbench → Data Science
2. **Environment**: JupyterLab will open with Python 3 kernel
3. **Create**: New notebook for your analysis
4. **Libraries**: Pre-installed packages include pandas, numpy, matplotlib, seaborn
5. **Data**: Upload data through the file browser
6. **Analysis**: Begin with exploratory data analysis

#### Sample Python Code to Get Started:
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

# Load your data
df = pd.read_csv('your_data.csv')

# Basic exploration
print(df.head())
print(df.describe())
print(df.info())

# Quick visualization
plt.figure(figsize=(10, 6))
df.hist(bins=20, figsize=(12, 8))
plt.tight_layout()
plt.show()
```

### For Multi-omics Researchers

#### Getting Started with MAP
1. **Access**: Select Insight Engine → MAP
2. **Upload**: Use Data Upload to import your datasets
3. **Explore**: Browse MAP Store for relevant applications
4. **Select**: Choose application based on your data type and goals
5. **Workflow**: Design analysis workflow or use recommended pipeline
6. **Monitor**: Track progress through Job Status

#### Typical MAP Workflow:
1. **Quality Control** → Use PMart for initial data assessment
2. **Differential Analysis** → Apply statistical tests for group comparisons
3. **Visualization** → Create publication-ready figures with MODE
4. **Integration** → Combine datasets using iPMart (if multi-omics)
5. **Machine Learning** → Apply SLOPE for predictive modeling (if needed)

### For High-Performance Computing Users

#### Getting Started with Tahoma OnDemand
1. **Access**: Select Modeling Workbench → Tahoma OnDemand
2. **Dashboard**: Open OnDemand interface shows available applications
3. **Resources**: Choose between Cluster Desktop, Jupyter, or RStudio
4. **Jobs**: Submit computational jobs through the job scheduler
5. **Monitor**: Track job progress and resource usage

## Common Tasks

### File Management
- **Upload**: Use file browser upload buttons in each environment
- **Organization**: Create folders to organize your work
- **Sharing**: Set appropriate permissions for collaborative projects
- **Backup**: Download important results regularly

### Collaboration
- **Sharing Notebooks**: Export and share analysis notebooks
- **Team Access**: Invite collaborators to shared workspaces
- **Version Control**: Use Git integration where available
- **Documentation**: Maintain clear documentation of your work

### Troubleshooting

#### Common Issues and Solutions

**Issue**: Cannot access Proposal Management
- **Solution**: Ensure you have valid EMSL user credentials
- **Alternative**: Check ORCID integration and profile completion
- **Contact**: User Office at uo@emsl.pnnl.gov for account issues

**Issue**: Data Portal search not returning results
- **Solution**: Clear search filters and try broader search terms
- **Alternative**: Use "All Data" tab and browse by category
- **Contact**: Data management team for specific dataset questions

**Issue**: Sample submission templates not downloading
- **Solution**: Check browser settings to allow downloads
- **Alternative**: Try different browser or contact support
- **Contact**: LIMS support for template and submission issues

**Issue**: L7 Platform login or access issues
- **Solution**: Verify EMSL credentials and project permissions
- **Alternative**: Clear browser cache and retry login
- **Contact**: L7 administrator for platform-specific issues

**Issue**: Cannot access environment
- **Solution**: Clear browser cache and try again
- **Alternative**: Try different browser or incognito mode
- **Contact**: sc.support@pnnl.gov if problems persist

**Issue**: Kernel connection problems
- **Solution**: Restart kernel from Kernel menu
- **Alternative**: Refresh browser page
- **Prevention**: Save work frequently

**Issue**: Out of memory errors
- **Solution**: Process data in smaller chunks
- **Alternative**: Use Tahoma OnDemand for larger datasets
- **Optimization**: Remove unnecessary variables and objects

**Issue**: Package not available
- **Solution**: Install using pip or conda in terminal
- **Alternative**: Request package installation from support
- **Documentation**: Check environment-specific package lists

### Performance Tips

#### For Data Science Environment
- **Memory Management**: Clear unused variables with `del variable_name`
- **Chunk Processing**: Process large datasets in smaller pieces
- **Vectorization**: Use pandas/numpy vectorized operations
- **Visualization**: Use sample data for initial plot development

#### For TensorFlow Environment
- **GPU Usage**: Monitor GPU memory utilization
- **Batch Sizes**: Adjust batch sizes based on available memory
- **Model Checkpoints**: Save model checkpoints regularly
- **Data Loading**: Use efficient data loading pipelines

#### For MAP Applications
- **Data Preparation**: Ensure data is in correct format before upload
- **Workflow Planning**: Design complete workflow before execution
- **Resource Estimation**: Consider computational requirements
- **Result Management**: Organize outputs systematically

## Best Practices

### Proposal Management
- **Preparation**: Complete ORCID profile before submitting proposals
- **Documentation**: Maintain clear project descriptions and objectives
- **Deadlines**: Submit proposals well before deadline dates
- **Follow-up**: Regularly check proposal status and respond to reviews
- **Training**: Complete required safety and instrument training

### Data Management
- **Discovery**: Use Data Portal to avoid duplicating existing research
- **Citation**: Properly cite datasets used in your research
- **Metadata**: Provide comprehensive metadata for your own datasets
- **Access**: Understand data policies before downloading datasets
- **Sharing**: Follow EMSL guidelines for data sharing and publication

### Sample Management
- **Templates**: Always use current metadata templates for submissions
- **Preparation**: Prepare samples according to EMSL guidelines
- **Tracking**: Monitor sample status through submission system
- **Communication**: Maintain contact with facility staff during processing
- **Quality**: Ensure sample quality meets analysis requirements

### Laboratory Information Management
- **Workflows**: Design clear, reproducible analytical workflows
- **Documentation**: Maintain detailed records of all procedures
- **Quality Control**: Implement appropriate QC measures
- **Data Integrity**: Ensure accurate data capture and storage
- **Compliance**: Follow all facility and regulatory requirements

### Collaboration
- **Communication**: Use clear communication with team members
- **Sharing Protocols**: Establish data sharing agreements
- **Attribution**: Properly credit collaborators and data sources
- **Reproducibility**: Ensure analyses can be reproduced by others

## Advanced Features

### Custom Environments
- **Package Installation**: Install additional Python/R packages
- **Environment Configuration**: Customize computing environments
- **Docker Integration**: Use custom Docker containers when needed
- **Resource Scaling**: Access additional computing resources as needed

### API Access
- **Programmatic Access**: Use APIs for automated workflows
- **Integration**: Connect with external tools and platforms
- **Batch Operations**: Automate repetitive tasks
- **Data Pipelines**: Create automated analysis pipelines

## Support Resources

### Documentation
- **Platform Guides**: Comprehensive documentation for each component
- **Tutorials**: Step-by-step instructional materials
- **User Guides**: Specific documentation for Proposal Management, LIMS, and Data Portal
- **Best Practices**: Methodology recommendations
- **FAQ Resources**: Answers to common questions at https://www.emsl.pnnl.gov/user-program/faqs

### Contact Information
- **General Support**: sc.support@pnnl.gov
- **User Office**: uo@emsl.pnnl.gov (for account and proposal questions)
- **Data Management**: Contact through Science Central platform
- **LIMS Support**: Available through L7 platform help system
- **Emergency Contact**: 24/7 facility operations support available

### Getting Help
1. **In-Platform Help**: Use the "How can I help you?" chat feature
2. **Documentation**: Access comprehensive guides for each platform
3. **Training Resources**: Complete online training modules
4. **User Community**: Connect with other researchers through Circles
5. **Direct Support**: Contact appropriate support team for specific issues

---

**Science Central™ provides integrated access to world-class scientific computing, data management, and collaboration tools. Start with the appropriate platform for your research needs and expand to other tools as your project develops.**
# Science Central Quick Start Guide

## Getting Started with Science Central™

### Platform Access
1. **Navigate to**: https://sc.emsl.pnnl.gov/
2. **Authentication**: Use your EMSL credentials
3. **Dashboard**: Access the All Modules view
4. **Selection**: Choose the appropriate tool for your research

### Component Selection Guide

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

### Data Management
- **Naming Conventions**: Use clear, descriptive file names
- **Directory Structure**: Organize files logically
- **Documentation**: Include README files with project descriptions
- **Backup Strategy**: Maintain copies of important data and results

### Code Development
- **Version Control**: Use Git for code management
- **Comments**: Include clear comments in your code
- **Modular Design**: Break complex analyses into functions
- **Testing**: Validate your code with known datasets

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
- **API Documentation**: Technical specifications for developers
- **Best Practices**: Methodology recommendations

### Training
- **Video Tutorials**: Visual learning materials
- **Webinars**: Regular training sessions
- **Workshops**: Hands-on training opportunities
- **Office Hours**: Direct access to experts

### Community
- **User Forums**: Peer-to-peer support
- **Case Studies**: Examples of successful projects
- **Method Sharing**: Community-contributed methodologies
- **Collaboration Opportunities**: Connect with other researchers

### Technical Support
- **Help Desk**: Email sc.support@pnnl.gov for technical assistance
- **Bug Reports**: Report issues for prompt resolution
- **Feature Requests**: Suggest improvements and new features
- **System Status**: Check platform status and maintenance schedules

## Getting Help

### Self-Help Resources
1. **Documentation**: Check platform-specific documentation first
2. **Tutorials**: Follow step-by-step guides for common tasks
3. **Community Forums**: Search for similar questions and solutions
4. **FAQ**: Review frequently asked questions

### Contacting Support
1. **Email**: sc.support@pnnl.gov with detailed problem description
2. **Include**: Error messages, steps to reproduce, browser information
3. **Response Time**: Typically 1-2 business days
4. **Escalation**: Critical issues receive priority attention

### Emergency Support
- **System Outages**: Announcements via platform notifications
- **Data Loss**: Immediate assistance for data recovery
- **Security Issues**: Priority handling for security concerns
- **Critical Deadlines**: Expedited support for time-sensitive work

Remember: Science Central is designed to support your research goals. Don't hesitate to reach out for help or to explore new features that might enhance your work!
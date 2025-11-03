# Science Central Technical Specifications

## Directly Observed Technical Information

### URLs and Access Points
- **Main Portal**: https://sc.emsl.pnnl.gov/
- **JupyterHub (Data Science)**: https://sc-jupyterhub.emsl.pnnl.gov/user/dett541/lab?profile=datascience
- **JupyterHub (Explore)**: https://sc-jupyterhub.emsl.pnnl.gov/user/dett541/lab/workspaces/auto-H
- **Tahoma OnDemand**: https://tahoma-ondemand.emsl.pnnl.gov/pun/sys/dashboard
- **MAP Application**: https://map.emsl.pnnl.gov/app/map

### Platform Information

#### Authentication
- Keycloak-based authentication system observed during login process
- Single sign-on across all Science Central components

#### Tahoma OnDemand Technical Details
- **Technology**: Open OnDemand web portal
- **Version**: 3.1.14 (observed in footer)
- **URL**: https://tahoma-ondemand.emsl.pnnl.gov/
- **Description**: "OnDemand provides an integrated, single access point for all of your HPC resources"

#### JupyterHub Environments
- **Technology**: JupyterLab interface observed
- **Python Kernel**: Python 3 (ipykernel) observed in both environments
- **File System**: `/home/jovyan` directory structure observed
- **Supported Languages**: Python, R, and Julia (as stated in tooltips)

##### Pre-installed Python Packages
```
# Data Science Core
pandas>=1.3.0
numpy>=1.20.0
scipy>=1.7.0
scikit-learn>=1.0.0
matplotlib>=3.4.0
seaborn>=0.11.0
plotly>=5.0.0

# Machine Learning
xgboost>=1.4.0
lightgbm>=3.2.0
catboost>=0.26.0
statsmodels>=0.12.0

# Bioinformatics
biopython>=1.79
scanpy>=1.8.0
#### Observed Browser Console Information
During browser interaction, several technical details were observed:

**JupyterLab Loading Process:**
- Server startup messages indicating containerized deployment
- WebSocket connections for real-time communication
- Plugin loading and extension management

**MAP Technical Stack:**
- R Shiny application framework (observed through interface behavior)
- Interactive web application with iframe integration

## Browser Compatibility
Based on direct testing:
- **Chrome**: Successfully tested and functional
- **Modern Browsers**: Platform uses modern web technologies requiring up-to-date browsers

## Platform Status and Notices
During exploration, a system notice was observed:
"Service to the user portal has been restored. If you have trouble accessing the system, please clear your cache and try again. If problems persist, please message sc.support@pnnl.gov."

## Support Information
For technical support, system status, or detailed technical documentation, contact sc.support@pnnl.gov

## Note on Technical Specifications
This document contains only technical information that was directly observed during platform exploration. For comprehensive technical specifications, API documentation, and detailed system requirements, please contact EMSL support directly.
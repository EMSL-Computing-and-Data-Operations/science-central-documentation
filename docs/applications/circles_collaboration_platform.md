# Circles - Collaboration Platform

## Overview

**Circles** is a component of Science Central™ for collaboration and research sharing that integrates directly with Microsoft Teams.

### Primary Purpose
"Connect and collaborate to share research findings"

### Platform Tagline
"Share and connect with your peers"

### Platform Description (Development Environment)
"Share and connect with your peers via Microsoft Teams"

### Action Label
"Collaborate"

## Platform Integration

### Microsoft Teams Integration
Circles is implemented as a direct integration with Microsoft Teams, providing seamless collaboration capabilities within the familiar Teams environment. When accessed from Science Central, users are directed to Microsoft Teams web application.

#### Observed Technical Implementation
- **URL Pattern**: Uses Microsoft Teams launcher URLs with specific tenant and group IDs
- **Authentication**: Leverages Microsoft Teams authentication system
- **Team Structure**: "Science Central - MS Teams Integration" team observed as active implementation
- **Tenant ID**: d6faa5f9-0ae2-4033-8c01-30048a38deeb (observed in URLs)

### Access Methods
1. **From Science Central Development Environment**: Click on Circles component
2. **Direct Teams Access**: Launches Microsoft Teams web application
3. **Cross-Platform Navigation**: Seamless transition from Science Central to Teams

## Teams Environment Structure

### Observed Teams Structure
Based on direct exploration of the Microsoft Teams integration:

#### "Science Central - MS Teams Integration" Team
- **Team Name**: Science Central - MS Teams Integration
- **Active Channel**: General (currently selected)
- **Channel Types**:
  - General (public channel)
  - Test (private channel, observed timestamp 9/25)

#### Associated Research Teams
Multiple research-focused teams observed in the environment:
- Science Central (main team with multiple channels)
- EMSL LLMs
- EMSL CAM Science Area
- PNNL Public Cloud
- Various specialized research teams

### Channel Features
- **Public Channels**: Standard team collaboration
- **Private Channels**: Secure discussions (marked with lock icon)
- **Timestamps**: Active recent communication (observed messages from August 2025)
- **Guest Access**: External collaboration capabilities (observed guest user posts)

## Collaboration Features

### Communication Capabilities
- **Real-time Messaging**: Standard Teams messaging functionality
- **File Sharing**: Integrated file management through Teams
- **Meeting Integration**: Teams meeting capabilities
- **Thread Discussions**: Reply-in-thread functionality observed

### User Experience
- **Desktop Notifications**: Available for staying updated
- **Activity Tracking**: 7 new activities observed
- **Chat Management**: 3 chats with new messages
- **Search Functionality**: Global search across teams and channels

### External Collaboration
- **Guest Users**: Support for external PNNL users
- **Cross-Organizational**: Ability to collaborate beyond PNNL boundaries
- **Personal Accounts**: Integration with personal Microsoft accounts (observed Gmail user access)

## Platform Status

### Current Implementation Status
- **Production Environment**: Listed but not directly accessible
- **Development Environment**: Fully functional with active Teams integration
- **Active Usage**: Recent messages and activities observed (August 2025)

### Accessibility
- **Development Access**: Available on https://sc-dev.emsl.pnl.gov/
- **Teams Web App**: Fully functional through browser
- **Cross-Platform**: Works with Teams desktop and mobile applications

## Integration Benefits

### For Science Central Users
- **Familiar Interface**: Leverages existing Teams knowledge
- **No Additional Training**: Uses standard Microsoft Teams functionality
- **Unified Communication**: Brings research collaboration into established communication platform
- **External Access**: Enables collaboration with external researchers and partners

### For Research Collaboration
- **Project-Based Teams**: Organized by research projects and initiatives
- **Secure Channels**: Private channels for sensitive research discussions
- **File Management**: Integrated document sharing and collaboration
- **Meeting Coordination**: Built-in scheduling and video conferencing

## Technical Architecture

### Browser Compatibility
- **Tested Browsers**: Successfully tested with Chrome
- **Web Application**: Full functionality through Teams web interface
- **Mobile Support**: Compatible with Teams mobile applications

### Security and Authentication
- **Single Sign-On**: Integrated with organizational authentication
- **Tenant-Based**: Uses organizational Microsoft Teams tenant
- **Guest Management**: Controlled external user access
- **Data Classification**: Non-sensitive information labeling observed

## Contact for More Information

For detailed information about Circles functionality, Teams integration, and access permissions, contact sc.support@pnnl.gov
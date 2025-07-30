# User Profiling App

A comprehensive Microsoft Power Platform solution for user profile management and analytics.

## 📋 Overview

This application provides a complete user profiling system built using Microsoft Power Platform components, designed to streamline user management processes within organizations.

## 🚀 Features

- **User Profile Management**: Collect and manage comprehensive user profiles
- **Automated Workflows**: Power Automate flows for streamlined user processes
- **Data Analytics**: Power BI dashboard for user data visualization and insights
- **Organizational Structure**: Track and manage organizational hierarchies

## 🏗️ Architecture

### Components
- **Power Apps Application** (`ProfilingApp_PowerApps.msapp`)
  - Mobile-friendly user interface
  - Form-based data collection
  - User profile management screens

- **Power Automate Workflows** (`ProfilingApp_PowerAutomate_*.zip`)
  - Automated user onboarding processes
  - Data synchronization workflows
  - Notification systems

- **Power BI Dashboard** (`PROFILING APP PBI.pbix`)
  - User analytics and reporting
  - Visual data representation
  - Interactive dashboards

- **Data Sources** (Excel Files)
  - `User_Details.xlsx` - Personal user information
  - `User_Org.xlsx` - Organizational structure data  
  - `User_Profile.xlsx` - Profile-specific data

## 📊 Data Structure

The application manages three main data entities:
1. **User Details** - Personal information and contact details
2. **User Organization** - Department, role, and hierarchy information
3. **User Profiles** - Custom profile attributes and preferences

## 🛠️ Setup Instructions

### Prerequisites
- Microsoft Power Platform environment
- Power Apps license
- Power Automate license
- Power BI Pro license (for dashboard)
- Excel Online or SharePoint for data sources

### Installation Steps
1. **Import Power Apps Application**
   - Download `ProfilingApp_PowerApps.msapp`
   - Import into your Power Apps environment
   - Configure data connections

2. **Deploy Power Automate Flows**
   - Extract and import workflows from `ProfilingApp_PowerAutomate_*.zip`
   - Configure connections and permissions

3. **Setup Power BI Dashboard**
   - Open `PROFILING APP PBI.pbix` in Power BI Desktop
   - Configure data source connections
   - Publish to Power BI Service

4. **Configure Data Sources**
   - Upload Excel files to SharePoint or OneDrive
   - Update data connections in Power Apps and Power BI

## 📱 Usage

1. **For End Users**:
   - Access the Power App through mobile device or web browser
   - Complete profile information forms
   - Update personal and organizational details

2. **For Administrators**:
   - Monitor user profiles through Power BI dashboard
   - Manage organizational structure
   - Review automated workflow outputs

## 📄 Documentation

- `User Profiling App Documentation.pdf` - Complete technical documentation
- `Profiling2.3.pptx` - Presentation overview
- `Old Version/` - Previous iterations and backup files

## 🔧 Customization

The application can be customized to include:
- Additional profile fields
- Custom workflows
- Enhanced reporting features
- Integration with other Microsoft 365 services

## 📈 Analytics & Reporting

The Power BI component provides insights on:
- User profile completion rates
- Organizational distribution
- Usage patterns and trends
- Data quality metrics

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test the modifications
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🆘 Support

For support and questions:
- Review the documentation in `User Profiling App Documentation.pdf`
- Check the presentation materials in `Profiling2.3.pptx`
- Create an issue in this repository

## 🔄 Version History

- **Current Version**: Latest iteration with all components
- **Previous Versions**: Available in `Old Version/` folder

---

**Note**: This solution requires appropriate Microsoft Power Platform licenses and permissions to deploy and use effectively.

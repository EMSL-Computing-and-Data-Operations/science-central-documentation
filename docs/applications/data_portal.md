# Data Portal

## Introduction

Environmental Molecular Sciences Laboratory's (EMSL's) Data Portal provides users the ability to download project data across a variety of EMSL projects. Users can use search filters to find projects that they are interested in, create a cart with datasets across those projects, and either download those data to their computer or create a shared collection in Globus that they can access. Additionally, the data portal has functionality specifically for MONet projects, where users can similarly filter sample analytics data and download that analytics data. This includes a variety of analysis like pH, Chemical Soil Analysis, Metagenomics Analysis, etc.

Data Portal allows users to browse and search through projects data without logging in but login is required for download functionality.

## About Data Portal tabs

Data Portal has two primary pages "All Data" and "MONet". All Data is a project-oriented search across all project types, whereas MONet is a sample-oriented search pertaining to MONet projects only. In both views, users can use the search sidebar to add filters to the results. Users can toggle between the 2 views using the tabs at the top of the page.

![tabs_at_top_data_portal](../_static/images/data_portal/tabs_at_top.png)

### All Data tab

For All Data tab the search bar on the side looks as below,

![All_data_search_bar](../_static/images/data_portal/all_data_filters.png)

After the selections are made by user, search results appear as a scrollable list of projects on the screen. The title of the project can be clicked on to view more details about the project as members, project status, and data availability. Each project in the list that has data available will have a "Select datasets" button (shown as "Sign in to select datasets" when not logged in). 

![project_title_click](../_static/images/data_portal/project_title_click.png)

Users can click on the "Select datasets" button to open up the dataset selector. From here, users can check the datasets they want, and each checked dataset is added to the cart automatically (enabling downloads of data across multiple projects).

Users can also see more details such as the files and metadata of an individual upload by clicking the "View files" button. Each dataset has its own URL that can be shared between users. Users can add files to cart and/or download from here as well.

![doi_click](../_static/images/data_portal/doi_click.png)

With projects in the cart, users can see more information in the top app bar about the state of their cart which includes information about number of uploads and size. Clicking the top most cart icon will show users the projects currently in their cart. Users can go back to the project list by clicking the "cart icon" in the top app bar or clicking "Back to project list" text under the top bar on left corner.

![cart_view](../_static/images/data_portal/my_cart.png)

Once the user is ready with all the data for download, clicking on "Download" button in the top app bar brings up the download modal. In the modal, users can optionally give the download a name so they can recognize it later in Past Downloads. Modal has two options to select the download destination as local machine(this computer), and Globus.

![download_modal](../_static/images/data_portal/download_modal.png)

#### Transfer Methods

The Data Portal offers two distinct transfer methods for downloading datasets:

**Local Download (Direct Browser Download):**
- Available for cart sizes less than 10GB.
- Downloads directly to your computer through the browser.
- Best for smaller datasets and quick access.
- No additional account setup required.
- Files are prepared in the background (large or archived files are first staged from tape), then download to your default download location. The finished download is also available in Past Downloads.
- Downloads larger than 5GB show a warning recommending Globus, since large browser downloads often stall or fail.

**Globus Integration (High-Performance Transfer):**
- Required for cart sizes larger than 10GB.
- Enables high-performance file transfer for large datasets.
- Requires a Globus account to be linked to your Data Portal profile.
- Provides reliable transfer with automatic retry capabilities.
- Better for large-scale data transfers and institutional repositories.
- Supports transfer management and monitoring through Globus interface.

To use Globus transfers, users must link up a Globus ID. This can be done from the user settings (the gear icon next to the login/logout button on the top bar, or "Settings" in the menu under your user name).

![user_settings](../_static/images/data_portal/user_settings.png)

If the user already have a globus account configured in the Data Portal, they can select it when doing a globus transfer through download.

![globus_configures](../_static/images/data_portal/globus_configured.png)

After the user selects the globus id and clicks "download" button, the download is prepared in the background. Once it is ready, users can open Past Downloads to access their data through Globus (the "View in Globus" column).

### MONet tab

In the MONet search sidebar, different search facets are grouped together in collapsable sections. Users can adjust these filters to their needs. The free text search adds a filter that matches Project ID, title, or abstract. Users can expand/collapse all sections, and select show only active filters, or clear the current search from the top section of the search sidebar.The search sidebar in the MONet tab looks as below.

![monet_search_bar](../_static/images/data_portal/monet_search_bar.png)

For MONet, the main view contains a map annotated with the location of samples. Users can click zoom and pan, and click "Search Visible Region" to add a latitude/longitude filter to the samples. Users can see more information by opening the bottom panel of the view, they can see information about the current samples and projects that those samples belong to.

#### MONet Map Controls

The MONet interface provides interactive map-based data discovery with the following controls:

**Search Visible Region:**
- Enables geographic filtering based on the current map view.
- Click this button to filter samples by latitude/longitude within the visible map area.
- Useful for finding region-specific research data.
- Applied filter appears in the active filters list and can be cleared.

**Reset Map:**
- Returns the map to the default view (centered on the continental United States).
- Clears any geographic zoom or pan adjustments.
- Does not clear other applied filters.
- Use this to start fresh with map exploration.

**Additional Map Features:**
- Zoom controls for detailed geographic exploration.
- Pan navigation to move across different regions.
- Location markers showing sampling sites.
- Interactive selection of sample points.

![monet_main_view](../_static/images/data_portal/monet_main_view.png)

As shown below on the "Analytics" tab, users can filter data by various analytic analysis results. When more than one analysis is selected, sample sets that match any of the selected analyses are returned.

![analytic_results](../_static/images/data_portal/analytic_results.png)

Users can toggle the filter using the checkbox next to each analysis on the left. Users can initiate a download for MONet data by clicking the "Download" button in the top app bar (labeled "Download All" when no filters are applied). Users must be logged in to download MONet data; when logged out, hovering over the button shows "You must be logged in to download data" and the download modal does not open.

**Note**: MONet downloads do not require a Globus connection. All MONet data can be downloaded directly without Globus account setup.

![monet_download](../_static/images/data_portal/monet_download.png)

The download modal shows a summary of the download and the current filters, including the number of active filters and the number of files. "Include site-level environmental metadata" is checked by default and adds Site_Level_Metadata.csv, with soil survey, climate, topography, land cover and NDVI context for each core section in the selection from six public providers (SSURGO, Daymet, gridMET, USGS 3DEP, NLCD, HLS Landsat). These values are modelled or remotely sensed for the area around each site; they are not measurements of the sample. A README documenting every column, its source, and its citation is included. Checking "Include Full Replicate Data (L1 data)" returns replicate-level values instead of averaged values, where they are available. Clicking download on the modal initiates a download of a zip file containing the requested data. The button shows "Processing" while the zip file is prepared in the background; download sizes vary, so this may take a while. If the download fails, the modal shows an error and the button changes to "Try Again". Contact dataportal.support@pnnl.gov if the error persists.

#### MONet Resources

On the MONet tab, the "Resources" button in the top app bar opens "MONet Data Protocols, Files, and Resources", which links to:

- **MONet Lab Protocols**: the protocols followed to standardize sampling (https://raw.githubusercontent.com/EMSL-MONet/MONet-Protocols-/refs/heads/main/MONet%20Lab%20Protocols.docx)
- **Column Description Guide**: help understanding the columns in downloaded MONet data (https://raw.githubusercontent.com/EMSL-MONet/MONet-Protocols-/refs/heads/main/Column_Descriptions.xlsx)
- **EMSL MONet repository**: more information about MONet protocols and files (https://github.com/EMSL-MONet/MONet-Protocols-/)
- **MONet 1000 Soils Data Package** (https://sc-data.emsl.pnnl.gov/packages?file=1000soils.zip)
- **MONet Biogeochemistry Data Release Jan 2026** (https://sc-data.emsl.pnnl.gov/packages?file=MONet_biogeochemistry_XCT_January2026.zip)
- **MONet Biogeochemistry Data Release Apr 2026** (https://sc-data.emsl.pnnl.gov/packages?file=MONet_biogeochemistry_XCT_April2026.zip)
- **MONet Biogeochemistry Data Release Jul 2026** (https://sc-data.emsl.pnnl.gov/packages?file=MONet_biogeochemistry_XCT_ICR_July2026.zip)

The data package and data release links require users to be logged in to the Data Portal.

The "Data Policy" button explains EMSL's data availability policy, and the "Support" button provides the Data Portal support contact, dataportal.support@pnnl.gov.

## All Data vs MONet: Download Workflow Comparison

The Data Portal offers two distinct interfaces with different download approaches. Use this comparison to determine which interface best suits your needs:

| Feature | All Data Tab | MONet Tab |
|---------|-------------|-----------|
| **Primary Focus** | Individual project discovery and dataset selection | Geographic and analytical data discovery for MONet projects |
| **Discovery Method** | Project database browsing with filters | Interactive map-based geographic exploration combined with filters |
| **Selection Process** | Individual dataset selection from multiple projects | Bulk filtering by analytics type and geographic region |
| **Download Workflow** | Select datasets → Configure → Download | Filter data → Download |
| **Data Organization** | Project-centric with detailed dataset metadata | Sample and analytics-centric with standardized protocols |
| **Download Granularity** | Individual files and custom dataset configurations | Bulk standardized data packages |
| **Cart System** | Multi-project cart with selective file choices | No cart system - direct bulk download |
| **Globus Requirement** | Required for downloads larger than 10GB | Not required - all downloads are direct |
| **Transfer Options** | Local download (<10GB) or Globus (>10GB) | Direct zip download regardless of size |
| **Primary Use Case** | Targeted research data needs across various projects | Large-scale spatial/analytical dataset analysis for MONet |
| **Data Volume** | Configurable based on user selection | High-volume bulk downloads (thousands of files typical) |

### When to Use Each Interface:

**Use All Data Tab when:**
- You need specific datasets from particular projects.
- You want to review and select individual files before downloading.
- You need custom download configurations.
- You're working with data from multiple different project types.
- You need to manage downloads with a cart.

**Use MONet Tab when:**
- You need comprehensive geographic datasets from MONet projects.
- You want standardized analytical data (pH, soil analysis, etc.).
- You need bulk downloads for large-scale analysis.
- You're filtering data by sample location or analytics type.
- You prefer direct downloads without Globus setup.

## Download History and Management

The Data Portal provides a comprehensive download history interface that allows users to track and manage all their past downloads. This feature is accessible from the "Past Downloads" button in the top app bar of the All Data tab (also listed in the menu under your user name) and provides the following capabilities:

### Viewing Download History

The Past Downloads interface (titled "My Downloads") displays:
- **Name**: The download name assigned by the user to the collection at the time of download.
- **File Count**: Total number of files in each download.
- **Size**: Complete dataset size for each download.
- **Status**: Current status monitoring (Processing, Ready for Download, etc.).
- **Download**: Button to download or re-download the collection.
- **View in Globus**: Option to create a Globus collection for the download.
- **Transfer Data**: Option to transfer the download to an active EMSL project (available after a Globus collection has been created).
- **Delete**: Button to remove the download from the list.

### Download Management Actions

Users can perform the following actions on past downloads:

**Re-download Capabilities:**
- Initiate a new download of the same dataset without rebuilding the cart.
- Useful for re-acquiring data or sharing with collaborators.
- Maintains the same file selection and configuration.

**Globus Transfer Management:**
- View Globus transfers directly from the download history.
- Access Globus transfer interface for monitoring large transfers.
- Manage transfer data and configurations.

**Download Cleanup:**
- Delete completed downloads from history to keep the interface organized.
- Remove failed or cancelled downloads.

### Globus Account Integration

The download history integrates with your linked Globus accounts:
- Track all Globus-based transfers in one location.
- Support for multiple Globus account associations.
- User account linking maintained across sessions.
- Transfer history synchronized with Globus platform.

### Status Monitoring

Real-time status tracking provides:
- **Processing**: Download preparation in progress.
- **Complete**: Download successfully finished and available.
- **Failed**: Download encountered errors (with error details).
- **In Progress**: Active transfer ongoing (for Globus transfers).
- Download completion notifications.
# MyData

Science Central™’s MyData is a web app that allows registered users to view and download files stored on Environmental Molecular Sciences Laboratory (ESML) servers. This includes their home directories, EMSL Globus collections, active project directories, and files associated with other apps such as Modeling Workbench and Insights Engine.

## Active Project Directories (APD)

APD's are directories containing any files related to an active EMSL project that is shared amongst all members of that project. The goal of the APD is to foster collaboration and file sharing. Users with access to a project directory can transfer files to and from the directory or import the files into one of the Science Central™ applications. The data is backed up to alternate storage once per day. If you need data restored, please send a request to <msc-consulting@emsl.pnl.gov>.

Note: The daily backups are meant only for restoring files if they are accidentally deleted or modified. Backups cannot be kept indefinitely.  We do not guarantee that data can always be restored, especially if more than a few weeks have elapsed since a good backup was made of that data.

## How do I get data into an Active Project Directory

There are multiple methods for adding files to an APD.
1. Users may utilize the Data Portal to select datasets from EMSL projects and send them directly to their APD.
2. Users may utilize a Globus account to transfer files between an APD and another institution.
3. Users may install Globus Connect Personal to transfer files between their personal computer and an APD Globus Connect Personal: [https://www.globus.org/globus-connect-personal](https://www.globus.org/globus-connect-personal).
4. Users may connect via samba shares (see instructions below).

## Where and how to use the data in my Active Project Directory?

If you are using a Science Central™ app that supports it, you will be given the option to import files from an APD within the application.

## Connecting to APD via Samba
### Mac access
Connect to smb://workspaces.emsl.pnl.gov.  Enter your password and OneKey PIN if requested, and choose the folder matching the EMSL user project you are working on.

### Windows access
Connect to \\workspaces.emsl.pnl.gov  Enter your password and OneKey PIN if requested, and choose the folder matching the EMSL user project you are working on.

### Linux access
The Active Project Directories are available under /emslfs/napd/emsl{Project} where you substitute your project number for "{Project}".

# National Total Body PET - Australian Imaging Service Demonstration

## Navigating to an imaging session

### Descend through the tree 
* Select the project
* Select the subject
* Select the session

### Use the quick search

* Enter the session ID in the top right box


## OHIF Viewer

* View images and thumbnails
* Browse DICOM tags
* Make masks
  * Export mask

## File manager

* View full file-structure
* Explain about the resources under each scan
* Download individual files (good for HTML reports)


## Downloading data

* Zip
    * No dependencies
    * Not suitable for large data files (e.g. TBP data)
* XNAT Desktop
    * Stand-alone Java application with UI
    * Good for large download batches
* XML catalog
    * Select a list of scans/resources
    * Download selection for later processing


## Running pipelines

* Installed/enabled globally by site-administrator
* Project manager can enable them for project
* Demo launching `dicom2niix` pipeline
* Can be designed to run on
    * Scans
    * Sessions
    * Subjects
    * Projects
* Can be configured to run on data ingest
    * Particularly well-suited to QC pipelines
* Pipelines Stream of Australian Imaging Service


## Downloading data via command-line (typically required for HPC)

* Switch to Jupyter notebook for examples
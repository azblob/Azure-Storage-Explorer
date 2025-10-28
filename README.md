# Azure Storage Explorer

* [Installation](#installation)
* [System Requirements](#system-requirements)
* [Connecting to Storage](#connecting-to-storage)
  * [Signing in with Azure Active Directory](#signing-in-with-azure-active-directory)
  * [Using Storage Account Name](#using-storage-account-name)
  * [Connecting via Shared Access Signatures (SAS)](#connecting-via-shared-access-signatures-sas)

## Installation

Download the latest release from [Releases](https://github.com/access-manager/Azure-Storage-Explorer/releases/tag/1.38.0)

Azure Storage Explorer streamlines cloud storage management through an intuitive interface, allowing direct interaction with Azure services. Simply download the latest version, complete the installation, and authenticate using your Azure credentials or access keys. This tool enables efficient organization and administration of Blobs, Queues, and Tables.

### System Requirements

#### Windows

* **OS:** Windows 10 or newer (64-bit required)
* **Processor:** 1.4 GHz or faster
* **RAM:** Minimum 4 GB
* **Disk Space:** At least 500 MB available

#### macOS

* **OS:** macOS 10.12 (Sierra) or newer
* **Processor:** Intel processor
* **RAM:** Minimum 4 GB
* **Disk Space:** At least 500 MB available

#### Linux

* **Supported Distributions:** Ubuntu 18.04+, Fedora 30+, CentOS 8+
* **Processor:** 1.4 GHz or higher
* **RAM:** Minimum 4 GB
* **Disk Space:** At least 500 MB available

## Connecting to Storage

Azure Storage Explorer offers multiple methods to connect to storage accounts, allowing you to choose the approach that best suits your workflow.

### Signing in with Azure Active Directory

1. Launch Azure Storage Explorer.
2. From the sidebar, select **"Add an Account."**
3. Sign in using your Azure Active Directory credentials.
4. Once authenticated, your subscriptions will automatically appear.

### Using Storage Account Name

1. Obtain your storage account name and access key from the Azure portal.
2. In Storage Explorer, select **"Connect to Azure Storage"** and choose **"Storage account name and key."**
3. Enter the required details and provide a clear display name.
4. Confirm your entries to finalize the connection.

### Connecting via Shared Access Signatures (SAS)

1. Generate a SAS token from the Azure portal.
2. In Storage Explorer, pick **"Use a shared access signature (SAS) URI"** as the connection option.
3. Insert the SAS URI in the designated field and complete the setup.
4. The linked storage resources will now be accessible.

### Local Emulator Integration

* Storage Explorer also supports local emulator tools such as **Azurite.**
* Specify the emulator’s URL during connection configuration.

## Managing Your Storage Data

Azure Storage Explorer provides numerous feature to facilitate interaction with different storage services.

### Blob Storage

* **Main Functions:** Upload, download, copy, delete, and update blob objects.
* **Typical Uses:** Hosting unstructured data, storing images, backups.

### File Storage

* **Main Functions:** Browse file systems, upload, download, and organize files.
* **Typical Uses:** Cloud-based file sharing, smooth data migration.

### Queues

* **Main Functions:** Create, modify, and manage message queues.
* **Typical Uses:** Scheduling background tasks, asynchronous communication.

### Tables

* **Main Functions:** Query, edit, and delete table entries.
* **Typical Uses:** Semi-structured data storage, managing key-value pairs.

## Advanced Features

* **Storage Monitoring:** Track performance metrics and analyze logs for operational insights.
* **Seamless Integrations:** Works with Azure Functions, Logic Apps, and related services.
* **Customizable Settings:** Adjust network and proxy configurations for optimized performance.

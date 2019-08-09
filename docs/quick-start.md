# Rubrik Content Pack for vRealize Log Insight

## Installation

The Rubrik Content Pack for vRealize Log Insight can be installed through the following steps:

* Clone the git repository or download from GitHub
* Login to vRLI as an administrative user
* Go to the context menu in the top right, select Content Packs
* Click 'Import Content Pack'
* Browse for the location of the cloned GitHub repo, select the .vlcp file, click Import
* Should now see the content pack under 'Installed Content Packs'
* Clicking on it will reveal details of the Content Pack's contents

Rubrik CDM should be set up to send syslog to the vRealize Log Insight server (or cluster), instructions for configuring syslog on Rubrik CDM can be found in the Rubrik CDM User Guide.

## Dashboards

The initial release contains three dashboards:

* **Job History** - details of historical backup jobs
* **Security Dashboard** - details of successful and failed logon events to the Rubrik CDM cluster
* **Diagnostic** - details of unreachable Rubrik Backup Service clients

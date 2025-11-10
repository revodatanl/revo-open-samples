<img src="resources/revo-light-narrow-100px.png" alt="RevoData" height="80">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="resources/Databricks_Small.png" alt="Databricks" height="80">

# RevoData open-source Databricks examples 

Contains free sample assets for default Databricks features.

These examples are mostly simple code snippets. This repository does not contain any form of CI/CD.

## Sample Overview

 Sample Name                | Type      | Description                                 |
----------------------------|-----------|---------------------------------------------|
 [export-to-xml](assets/export-to-xml.ipynb) | notebook  | Demonstrates exporting data to XML format.  |
 [secret-handling](assets/secret-handling.ipynb) | notebook | Everything about Databricks Secrets         |
 [volumes](assets/volumes.ipynb) | notebook | Shows how to create volumes |
 [widgets](assets/widgets.ipynb) | notebook | Demonstrates Databricks notebook widgets    |
 [gateway-capacity](assets/gateway-capacity-metrics.dbquery.ipynb) | query | SQL query to report cluster resource usage and capacity. |
 [cluster-listing](assets/cluster-listing.dbquery.ipynb) | query | SQL query to list all clusters and their key properties. |
 [gateway-capacity-dashboard](assets/gateway-capacity-metrics-dashboard.lvdash.json) | dashboard | Dashboard visualizing cluster capacity and usage metrics. For hyperlinks to work, you need to alter the dataset. |

## How to use

There are two ways to use these examples:

1. **Fork and import as a Databricks repo**  
   - Fork this repository to your own Git provider (e.g., GitHub, Azure DevOps, GitLab, Bitbucket).  
   - In Databricks, go to "Repos" > "Add Repo" > "Clone from Git provider".  
   - Select your forked repository and import it as a Databricks repo.

2. **Download and upload notebooks directly**  
   - Download individual notebook files from the `assets/` directory.  
   - In Databricks, use "Workspace" > "Import" to upload the notebook file.

## Contributing

Feel free to add or expand an existing example and open a PR.
Notify RevoData at info@revodata.nl to review your commit.

## What is this for?
There are times where we need to move job definitions from:

* one dbt Cloud account to another
* one dbt Cloud project to another
* a Multi-tenant dbt Cloud account to a single-tenant one or vice versa
* Or simply have a file backup of our jobs

dbt Cloud does not have built-in import/export functionality through the UI, but it's possible to do through the API, so we do it here, via the API!

The script runs in [Google Colab](https://colab.research.google.com/) and uses the awesome [dbt-cloud-cli](https://github.com/data-mie/dbt-cloud-cli) project as a convenient wrapper around dbt Cloud's APIs
### what does it do?
1) downloads a list of dbt Cloud jobsjobs 
2) uploads them to Google Drive
3) Manipulates them as necessary
4) Imports them to a different dbt Cloud Account or Project

### Ok I heard enough I have to have it!
Simply click on the link at the top of the [notebook](https://github.com/ernestoongaro/dbt-cloud-job-exporter-and-migrator/blob/main/dbt_Cloud_Jobs_Migrator.ipynb) and go!

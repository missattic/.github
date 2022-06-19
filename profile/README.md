<img src="https://github.com/mara/.github/raw/main/assets/mara-animal.jpg"  style="width:40%; margin-left: auto; margin-right:auto; display:block;">

The **Mara ETL Framework** is a Python framework to build data pipelines.


It has been designed and build by [Dr. Martin Loetzsch](https://github.com/martin-loetzsch) at [Project A](https://github.com/project-a) as a lightweight data transformation framework for their ventures. Today the Mara Packages are maintained and developed further by the Mara Open Source community.

&nbsp;

Example projects
----------------

Runnable apps that demonstrates how to build a data warehouse app with mara:

* [Mara Example Project 1](https://github.com/mara/mara-example-project-1) - example ETL integrates publicly available e-commerce and marketing data into a more general modeling and structure for highlighting the capabilities of the Mara framework
* [Mara Example Project 2](https://github.com/mara/mara-example-project-2) - example ETL integrates PyPi download stats and GitHub repo activitiy metrics into more general Python project activity stats

&nbsp;

Packages overview
-----------------

### Core modules

The core modules of the framework. You might not need all of them.

* [mara-acl](https://github.com/mara/mara-acl) - adding basic permission management to the Mara Flask UI
* [mara-app](https://github.com/mara/mara-app) - a Mara Flask app
* [mara-db](https://github.com/mara/mara-db) - access and interact with databases
* [mara-page](https://github.com/mara/mara-page) - minimal API for defining Flask pages
* :star: [mara-pipelines](https://github.com/mara/mara-pipelines) - define DAG pipelines and execute them
* [mara-storage](https://github.com/mara/mara-storage) - access and manage Blob storage data

### Data Warehousing, Data Modelling and Documentation

* :star: [mara-schema](https://github.com/mara/mara-schema) - managing star schema entity models and use them
* [mara-dbt](https://github.com/mara/mara-dbt) - using the popular dbt engine inside a mara pipeline
* [mara-markdown-docs](https://github.com/mara/mara-markdown-docs) - display markdown documentation in mara UI
* [mara-etl-tools](https://github.com/mara/mara-etl-tools) - Utilities for creating ETL pipelines in PostgreSQL with mara

### Client integration & analytics

* [mara-data-explorer](https://github.com/mara/mara-data-explorer) - a minimal Flask based UI for data analytics
* [mara-metabase](https://github.com/mara/mara-metabase) - a client integration for Metabase from Mara Schema
* [mara-mondrian](https://github.com/mara/mara-mondrian) - a server/client integration for Mondrian Server with from Mara Schema
* [mara-superset](https://mara-superset.readthedocs.io/en/latest/) - a client integration for Apache Superset from Mara Schema

### Data Loading

We suggest loading data via tools like [Airbyte](https://airbyte.com/), [Fivetran](https://www.fivetran.com/) or [Stitch](https://www.stitchdata.com/), but there are some data loading packages available which are e.g. used in example projects:

* [mara-olist-ecommerce-data](https://github.com/mara/mara-olist-ecommerce-data) - (demo) downloading sample data from Olist E-Commerce Data in PostgreSQL
* [mara-google-sheet-downloader](https://github.com/mara/mara-google-sheet-downloader) - Download Google Sheets to a DB table in a mara ETL

### Other extensions

* [project-a/mara-campaign-tree-editor](https://github.com/project-a/mara-campaign-tree-editor) - Flask based Mara UI for correcting wrong UTM parameters or changing campaign structure
* [mara-cron](https://github.com/mara/mara-cron) - (experimental) managing crontab files from mara source code
* [project-a/mara-prophet](https://github.com/project-a/mara-prophet) - a lightweight framework for producing, integrating and historizing Facebook-prophet forecasts for time series data in Mara
* [leo-schick/mara-spark](https://github.com/leo-schick/mara-spark) - a basic implementation of pyspark into a mara pipeline

&nbsp;

Press Releases
--------------

* December 19, 2017 - [Reducing pain in Data Engineering | Martin Loetzsch](https://www.youtube.com/watch?v=WDBF3OMqltk) at YouTube | [Slides](https://www.slideshare.net/martinloetzsch/reducing-pain-in-data-engineering-data-natives-2017)
* April 08, 2018 - [code.talks commerce 2018 - Data Warehousing with Python](https://www.youtube.com/watch?v=GdtFuOah-5c) at YouTube
* October 11, 2018 - [Open Source: Project A Releases Its Data Warehouse Infrastructure](https://medium.com/@Project_A_Ventures/project-a-the-operational-vc-open-source-project-a-releases-its-data-warehouse-infrastructure-ba0993fb7b2) at Medium
* August 29, 2018 - [Dr. Martin Loetzsch - ETL Patterns with Postgres](https://www.youtube.com/watch?v=whwNi21jAm4) at Youtube | [Slides](https://www.slideshare.net/martinloetzsch/etl-patterns-with-postgres)

&nbsp;

Links
-----

* [Documentation](https://mara.readthedocs.io/)
* [PyPI Packages](https://pypi.org/user/mara-pypi-upload-account/)
* [Slack Chat](https://join.slack.com/t/mara-users/shared_invite/zt-1b2y0rr37-KXTnXtIqdxOTcNBTD2tQ4A)
* [GitHub Repositories](https://github.com/orgs/mara/repositories)

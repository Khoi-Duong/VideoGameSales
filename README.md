# Project Overview

For this project, you will tell a story using data visualizations. Here are the specific requirements:

1. Your visualization must include a Python Flask-powered API, HTML/CSS, JavaScript, and at least one database (SQL, MongoDB, SQLite, etc.).

2. Your project should fall into one of the following three tracks:

    * A combination of web scraping and Leaflet or Plotly

    * A dashboard page with multiple charts that update from the same data

    * A server that performs multiple manipulations on data in a database prior to visualization (must be approved)

3. Your project should include at least one JS library that we did not cover.

4. Your project must be powered by a dataset with at least 100 records.

5. Your project must include some level of user-driven interaction (e.g., menus, dropdowns, textboxes).

6. Your final visualization should ideally include at least three views.

For this project, you can focus your efforts within a specific industry, as detailed in the following examples.

### Finance
Tracking market data is crucial for equity traders. Not all traders code and are able to create custom-tailored visualizations. What’s the best way for them to get what they need for success?

One option is offered by the Wall Street Journal (https://www.wsj.com/market-data). Their website offers a dashboarding tool providing a high-level view of market performance.

* This highly interactive tool allows users to easily explore stocks, bonds, currencies, and commodities.

* Users of all skill levels can use the data.

* Visualizations help make the data easier to understand.

Multiple views are available for customized content.

### Healthcare
Imagine: Vacation time is coming up, and so is flu season. Trying to plan a road trip across the United States while keeping everyone’s health in mind can be tricky.

Using the FluView dashboard provided by the CDC, users can easily confirm which areas to avoid.

Different interactive features include:

* An overall view of the United States, or customizable view (state by state)

* Historic and current cases

* A chart showing the count of cases, broken down by strain

With this, data are delivered quickly and navigated through with ease.

### Custom
We’ve only specified healthcare and finance, but any industry can benefit from data visualization. Consider the following example of weather tracking.

While on the way to work one morning, you notice dark clouds on the horizon. You don’t remember hearing about a storm coming in, but this looks ominous.

A quick visit to Weather Underground’s Dashboard helps illuminate the situation.

Updated with live data, you can view a live map as well as specific conditions such as temperature, pressure, and even feed from a live webcam.

The data delivery is up-to-date and seamless, making it easy to understand current conditions without digging too deeply.

### Project Proposal
Before you start writing any code, you should outline the scope and purpose of your project. This will help provide direction and safeguard against **scope creep** (the tendency for projects to become more complex after work begins).

The proposal is essentially a brief summary of your interests and intent. Be sure to include the following details:

* The kind of data you’d like to work with and the field you’re interested in (finance, healthcare surveys, etc.)

* The questions you’ll ask of the data

* Possible source for the data

Use the following example for guidance:

The aim of our project is to uncover patterns in credit card fraud. We’ll examine relationships between transaction types and location, purchase prices and times of day, purchase trends over the course of a year, and other related relationships derived from the data.

### Finding Data
Once you have written a proposal, it’s time to start searching for data. We recommend the following curated sources of high-quality data:

* data.world (https://www.data.world/)

* Kaggle (https://www.kaggle.com/)

* Data.gov (https://www.data.gov/)

* Awesome Public Datasets (https://github.com/awesomedata/awesome-public-datasets)

* Public-APIs (https://github.com/n0shake/Public-APIs)

* Awesome API (https://github.com/Kikobeats/awesome-api)

* Medium API List (https://benjamin-libor.medium.com/a-curated-collection-of-over-150-apis-to-build-great-products-fdcfa0f361bc)

**IMPORTANT**:

Whenever you use a dataset or create a new dataset based on other sources (such as existing datasets or information scraped from websites), make sure to use the following guidelines:

   1. Check for copyright protections, and make sure that the way you plan to use this dataset is within the bounds of fair use.

   2. Document how you intend to use this dataset now and in the future. Find any licenses or terms of use associated with the dataset, and review them to confirm that    your intended use is in compliance.

   3. Investigate how the dataset was collected. Identify any indicators that the data was obtained from a source that the compilers were not authorized to access.

You’ll likely have to adjust your project plan as you explore the available data. That’s okay! This is all part of the process. Just make sure that everyone in the group is aligned on the project’s goals as you make changes.

Make sure that your datasets are not too large for your personal computer. Big datasets are difficult to manage locally, so consider using data subsets or different datasets altogether.

### Data Cleanup and Analysis
Now that you’ve picked your data, it’s time to tackle development and analysis. This is where the fun starts!

The analysis process can be broken into two broad phases: (1) exploration and cleanup, and (2) analysis.

As you’ve learned, you’ll need to explore, clean, and reformat your data before you can begin answering your research questions. We recommend keeping track of these exploration and cleanup steps in a dedicated Jupyter notebook to keep you organized and make it easier to present your work later.

After you’ve cleaned your data and are ready to start crunching numbers, you should track your work in a Jupyter notebook dedicated specifically to analysis. We recommend focusing your analysis on multiple techniques, such as aggregation, correlation, comparison, summary statistics, sentiment analysis, and time-series analysis. Don’t forget to include plots during both the exploration and analysis phases. Creating plots along the way can reveal insights and interesting trends in the data that you might not notice.


# Video Game Sales

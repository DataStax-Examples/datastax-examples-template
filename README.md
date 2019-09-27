---
author: bechbd
page_type: sample
level: beginner
languages:
- python
- DSE Search
products:
- apollo
description: "This is a description for sample."
urlFragment: datastax-example-template
---

# datastax-examples-template
This is an template repo which should be used for all examples on the DataStax examples site.  

## README File Requirements
All README files need to begin with a table block that specifies a few details of the repository for its inclusion in the DataStax examples site.  This block must come before any other text in the README and should be followed by the title.  This block looks like this:

---
author: bechbd
page_type: sample
level: beginner
languages:
- python
products:
- apollo
description: "This is a description for sample."
urlFragment: datastax-example-template
---

Each of these fields has a very specific usage within the DataStax Examples site which is explained below
* author - This represents the GitHub username of the owner of the sample.  This is used for attribution purposes as well as to properly routing any additional questions and feedback.
* page_type - This can be one of the following options
  - snippet - This is a short reusable piece of code which can frequently be handled by creating a Gist in github
  - sample - A more extensive example of code which demonstrates a concept throughly (e.g. Using Kafka to Populate Apollo)
  - project - A fully complete example project which demonstrates an entire end to end workflow.  This is likely to contain multiple projects and should include all relevant testing.  (e.g. Using DSE for an e-commerce site)
  - tool - A fully complete tool for use within the DataStax product environment (e.g. Cassandra Schema Diff tool)
 * level - This specifies the relative level of knowledge required to understand the content
   - beginner - No prior knowledge of Cassandra or DSE is required
   - intermediate - Prior knowledge of Cassandra or DSE is expected
   - advanced - Extensive knowledge of Cassandra or DSE is required
 * languages - A lowercase array of tags specifying the languages used in the example.  Options include 
    - c/c++
    - c#
    - java
    - nodejs/javascript
    - python
    - shell
 * products - A lowercase array of tags specifying which products of the DataStax portfolio this is code is relevent to.  Options include:
  - apollo
  - insights
  - dse
  - dse search
  - dse analytics
  - ds graph
  - ddac
  - cassandra
  - studio
  - kafka connector
  - bulk loader
  - drivers
  - opscenter
* description - An informative few sentences to describe what the sample does.  This is what is shown on the card in the main site
* urlFragment - A slugified (https://blog.tersmitten.nl/slugify/) string that is a short name for the project.  This needs to be unique for all samples as this is what is used in the URL to uniquely identify the project
 

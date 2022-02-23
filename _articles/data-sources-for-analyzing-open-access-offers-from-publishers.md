---
layout: post
date: 2022-02-23T20:09:44.428Z
title: Data Sources for Analyzing Open Access Offers from Publishers
summary: This document outlines free and subscription-based data sources, their
  purposes and uses for analyzing open access publishing, as well as their
  strengths and weaknesses and suggestions for additional assistance.
working-groups:
  - Data Analysis
authors:
  - Allison Langham-Putrow
  - Yuan Li
  - Carrie Nelson
  - Mathew Willmott
  - Jason Price
full_page: false
---
# Introduction

This document is meant to be a companion to “[OA agreement factors to consider](https://docs.google.com/document/d/1tVfw0XE0Rj4iL-jz9mVhpgx1egk7YLpSZ-dLUlki2ys/edit#heading=h.sxet594i01kd),” which  provides an overview of factors to consider when evaluating potential investments in open access (OA). These investments could include read-and-publish/publish-and-read agreements, or various types of membership models that discount or eliminate article processing charges (APCs) for the participating institutions’ authors.

Here, a number of data sources, their uses, purposes, strengths and weaknesses, and suggestions for additional assistance are described. It is composed of three sections:

* Article-level data (Web of Science, Scopus, Dimensions, Unpaywall)
* Journal-level data (DOAJ, SHERPA/RoMEO, publisher web pages, vendor knowledge bases)
* Analytical tools (OADAT, Unsub)

The document is in no way a comprehensive catalog of potential resources, but serves as a starting point for this type of analysis. There are a mixture of subscription (indicated with 🔶) and freely available sources (indicated with 🔵).

# Article-level data

## Web of Science

🔶Subscription tool

### Description and uses

Web of Science (WoS) is a subscription A&I (abstracting and indexing) tool from Clarivate which covers the bulk of the core, most highly-cited literature in science, social science, and arts and humanities. Data includes basic bibliographic metadata as well as citation linkages, and can be used through the GUI (graphical user interface) or downloaded for external analysis. Article-level data from Unpaywall is embedded into the WoS dataset, and can be included in data outputs or used to filter searches.

### Why you might use it

An analyst would use Web of Science to gather data about a specific article or set of articles—a vast amount of information about each article is available and is indexed for search, making WoS a valuable tool for understanding, for example, what (or how much) has been published in a given journal, from a given publisher, or by authors with a given affiliation. Many fields are normalized, allowing for more effective and comprehensive searching. While coverage is not comprehensive, it is quite broad across publishers and subject areas, allowing for targeted large-scale analyses.

### How to use it

The WoS GUI allows analysts to define datasets by journal, publisher, author affiliation, or other facets, for analysis using built-in WoS tools. Data sets built through the GUI can also be exported for external use, although a limitation of 500 articles per export exists, making the creation of large datasets in this way difficult.

Additionally, an API allows for connection to existing services or for data file requests. A “lite” version with a subset of available fields comes with the WoS subscription. An “enhanced” version with all available fields requires an added subscription.

OA-related analyses, in particular, include using the embedded Unpaywall data to measure the portion of a given set of articles that is openly available through various pathways (full OA journals, hybrid OA, repositories, etc.) to assess how much content would be available without a subscription. This data could also be used to assess impacts of potential agreements including open access to affiliated authors’ research. Additionally, incorporating list-price APC data could help estimate OA expenditures among authors within a given dataset.

### Strengths and weaknesses

#### Strengths

* Clarivate (and its predecessor companies) has historically offered the most thorough indexing service of a wide swath of impactful literature. While other A&I services have grown recently to be more comprehensive of academic literature, Web of Science continues to have very deep indexing, including:
* * Reprint author data, allowing each article to be linked to what is likely its primary author/institution
  * Funder indexing, including full text of the funder acknowledgement as well as a normalized list of funders
  * Citation linking going back decades in time

#### Weaknesses

* Web of Science access is expensive. 
* Limitations to the GUI only allow an export of 500 article records at a time, meaning that to build large datasets one must export in batches and merge the outputs outside of WoS. 
* Additional services, such as API access or the provision of data files direct from Clarivate, offer significant added value, but come at added cost.
* An additional weakness is that WoS is not attempting to index all literature in the world, only that which reaches a certain threshold of impact (as judged by Clarivate curators). Analyses run with WoS must therefore include this caveat, and sometimes require steps to be taken to try to account for this limitation.

### Who can help

Clarivate is generally quite responsive to customers, and experts on staff are usually able to help subscribers maximize the value they can get from the tools offered. Additionally, WoS is a standard tool within libraries, and many other libraries conduct analyses using WoS data. Significant help can come from library colleagues who are using the tool for similar purposes.

Clarivate has a number of training videos available. [Exporting Records](https://videos.webofsciencegroup.com/watch/vMykfbThsZfYPMJa3S48bx) shows how to export up to 500 records to citation management software and to a tab-separated values file. It points to [help](https://images.webofknowledge.com/images/help/WOK/hs_output_records.html) files accessible from the Web of Science interface that describe the different file formats and the [field codes](https://images.webofknowledge.com/images/help/WOK/hs_alldb_fieldtags.html).

- - -

## Scopus

🔶Subscription tool

### Description and uses

Scopus is a subscription-based, large interdisciplinary A&I database from Elsevier. As of January 2020, it includes over 23,000 peer-reviewed journals, of which 5,500 are fully open access, as well as conference proceedings and books. The database can be searched for documents, authors, or affiliations. 

### Why you might use it

Scopus can be used as a large dataset of scholarly output and mined for information about the publications coming from an institution’s scholars. 

### How to use it

Within the search interface, you can create a subset of articles of interest, such as all articles associated with an institution’s authors, all articles from a particular journal, or all articles from a set of journals.

Identified articles can be exported into Mendeley, RefWorks, or CSV format with selected information about the articles and journals, abstracts and keywords, and funding details for further analysis outside of Scopus. Exports of the full record are limited to 2,000; up to 20,000 records of basic citation information can be exported at one time.

These article sets include an “Access type” field to identify OA articles. This flags articles from fully OA journals and those in hybrid journals identified in Crossref as open. This information could be useful when trying to estimate APCs for affiliated authors.

### Strengths and weaknesses

#### Strengths

* Scopus has stronger international and non-English-language coverage than Web of Science.
* Scopus allows download of a much larger number of records of citation information at one time than Web of Science does.

#### Weaknesses

* It is more difficult to disambiguate author and affiliation with Scopus than with Web of Science.
* The article-level OA designation does not include green/repository-based access.
* It is common to find gaps in coverage within a particular journal run, so information and data about an available journal can’t be considered comprehensive.

### Who can help

Much of the Scopus help documentation is focused on the needs of researchers and authors, but they do have an [FAQ](https://service-elsevier-com.ezproxy.library.wisc.edu/app/overview/scopus/) and [visual tutorials](https://service-elsevier-com.ezproxy.library.wisc.edu/app/answers/detail/a_id/14799/supporthub/scopus/). They have an [email contact form](https://service-elsevier-com.ezproxy.library.wisc.edu/app/contact/supporthub/scopus/), [live chat support](https://service-elsevier-com.ezproxy.library.wisc.edu/app/chat/chat_launch/supporthub/scopus/), and [Facebook and phone support](https://service-elsevier-com.ezproxy.library.wisc.edu/app/phone/supporthub/scopus/). 

- - -

## Dimensions 

🔶🔵Subscription required for some functions

### Description and uses

Dimensions (<https://app.dimensions.ai/>) is a “freemium” database (termed a research information system by its creator, Digital Science). It has data for over 128 million publications, grants, policy, data, and metrics. More about the data sources can be found at: <https://www.dimensions.ai/resources/a-guide-to-the-dimensions-data-approach/>.

Dimensions’ publications and citations data is freely available for personal, non-commercial use, but the free version has significant limits.

### How to use it

Dimensions’ free version is available at <https://app.dimensions.ai/>. Its capabilities are limited to searching by keyword in the full data or title and abstract, or by DOI. Results can be filtered by publication year, researcher, research categories, publication type, source title, journal list, and open access status. The subscription version (Dimensions Analytics) is required to search by institution ([this version](https://www.dimensions.ai/products/dimensions-analytics/) provides additional features). The subscription version also provides the option to filter by publisher.

Both versions allow for export of search results (limited to 500 records per download for the free version) in .csv or .xlsx format, to a citation manager file format, or for use in a bibliometric network visualization tool (e.g., [VOSviewer](https://www.vosviewer.com/) or [CiteSpace](https://sourceforge.net/projects/citespace/)).

#### API

Dimensions provides the Metrics API to the public, which returns a limited set of article-level metrics based on an input set of identifiers. The Metrics API can be queried using PubMed ID, DOI, or Dimensions ID, and is able to return metrics including times cited, recent citations,  Relative Citation Ratio ([RCR](https://app.dimensions.ai/details/publication/pub.1017460035); a metric used by NIH for grant funding) and Field Citation Ratio ([FCR](https://plus.dimensions.ai/support/solutions/articles/23000018848-what-is-the-fcr-how-is-it-calculated-)) scores, and more. Find out more about the Metrics API [here](https://badge.dimensions.ai/).

For subscribers, Dimensions also provides two other APIs, Analytics API and CRIS API.The Analytics API supports extraction of Dimensions data for use in complex analyses and visualizations or for the building of analytical tools and reporting templates. The API uses an intuitive [query language](https://docs.dimensions.ai/dsl/) specifically developed for Dimensions data. You can retrieve, aggregate, and sort data from highly specific requests in a single API call. Additional services like text categorization are also available. Learn more about these in this [introductory video to Dimensions APIs](https://www.dimensions.ai/resources/an-introduction-to-the-dimensions-api/). [The Dimensions API Lab](https://api-lab.dimensions.ai/) provides API cookbooks on how to use API to fetch data. The CRIS API is specifically designed to retrieve Dimensions data and enrichments for all internal CRIS/RIMS (current research information systems/research information management systems), such as Symplectic Elements, Interfolio, or Elsevier’s Pure. You can [sign up](https://www.dimensions.ai/webinars/use-dimensions-and-its-api-to-enrich-records-in-pure-and-other-cris-rims-systems/) to watch a webinar about Dimensions and how to use its API to enrich records in Pure and other CRIS/RIMS. This recorded [webinar](https://www.dimensions.ai/webinars/use-dimensions-and-its-api-to-enrich-records-in-pure-and-other-cris-rims-systems/) shows how research institutions who are using a CRIS system can use the Dimensions API for their different needs.

### Strengths and weaknesses

Note: We are unable to provide information about the weaknesses of the subscription version of Dimensions due to lack of access. Please contact Allison Langham-Putrow ([lang0636@umn.edu](mailto:lang0636@umn.edu)) or Katharine Macy ([macyk@iupui.edu](mailto:macyk@iupui.edu)) if you are able to help!

#### Strengths

* The Publication module is available to the public for free.
* The built-in Analytical Views provides readily available analytical information.
* The tool is easy to use (only basic searching skills required).
* The dataset is large.

#### Weaknesses

* Search options are limited in the free version.
* API and export function are limited in the free version.

### Who can help

You can reach Dimensions support staff [here](https://www.dimensions.ai/contact-us/).

- - -

## Microsoft Academic Graph

🔵No subscription required

Microsoft Academic Graph will be retired December 31, 2021. <https://www.microsoft.com/en-us/research/project/microsoft-academic-graph/>.

Our Research (the group behind Unpaywall) announced that they are building a replacement. They provided more information on OpenAlex on [their blog](https://blog.ourresearch.org/openalex-update-june/).

- - -

## Unpaywall

🔵No subscription required

### Description and uses

Unpaywall ([unpaywall.org/](http://unpaywall.org/)) provides data on whether an open version of an article exists based on the article’s DOI. The tool was developed and is maintained by the non-profit Our Research (previously Unpaywall, previously ImpactStory).

Unpaywall harvests data from journals, open-access repositories, PubMed Central, DOAJ (the Directory of Open Access Journals), Crossref, and DataCite. It does not harvest from sources like ResearchGate, where the legality of the freely available content is not certain.

Scopus and Web of Science use Unpaywall data to identify whether items are OA.

There are two approaches to using Unpaywall data.

1. Analyze the OA status of your institution’s output
2. Analyze the OA status of a publication (note: this is most realistic when looking at a relatively small journal or a specific, narrow timeframe)

### How to use it

Before using Unpaywall, you will need to generate a list of DOIs. If your institution has a research information management system (e.g., [Pure](https://www.elsevier.com/solutions/pure), [Symplectic Elements](https://www.symplectic.co.uk/theelementsplatform/), [VIVO](https://duraspace.org/vivo/)), you may be able to export a list of DOIs for authors at your institution. Other options are to access Crossref, Web of Science, or Scopus. 

Note that Web of Science allows the download of bibliographic information for 500 articles at a time. Scopus allows for the download of full bibliographic information for 2,000 articles at a time; more if downloading the citation information only (which includes DOI). Crossref has an API through which DOIs from a known ISSN can be downloaded. [Read more about the Crossref REST API here](https://www.crossref.org/documentation/retrieve-metadata/rest-api/). The “[non-technical introduction to our API](https://www.crossref.org/education/retrieve-metadata/rest-api/a-non-technical-introduction-to-our-api/)” section is particularly useful.

There are a number of ways to access Unpaywall data: through their Simple Query Tool, through their API, and through the [Unpaywall browser extension](http://unpaywall.org/products/extension). An article DOI is the only input needed for both the Simple Query Tool and API.

This [Unpaywall data format page](http://unpaywall.org/data-format) gives the full list of data outputs. A few of the most relevant for analyzing the OA output from an institution are:

| Field                    | Description/Use                                                                                                                                              |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| oa_status                | Returns closed, green, bronze, hybrid, or gold                                                                                                               |
| journal_name             | Can be useful if the source of the DOI does not report the journal title                                                                                     |
| publisher                | Can be useful if the source of the DOI does not report the publisher                                                                                         |
| journal_issns            | Can be useful for further exploration of the journal (e.g., via SHERPA/RoMEO                                                                                 |
| journal_is_in)doaj       | TRUE/FALSE if the journal is listed in DOAJ                                                                                                                  |
| best_oa_location_version | Returns which version is the best available OA is: published, accepted, submitted                                                                            |
| best_oa_license          | License type if an OA version is found                                                                                                                       |
| best_oa_url              | Link to the version that Unpaywall considers the "best"; can identify cases in which the institutional repository is essential to providing OA to an article |
|                          |                                                                                                                                                              |

“Best” location is determined using an algorithm that prioritizes publisher-hosted content first (e.g., Hybrid or Gold), then prioritizes versions closer to the version of record (PublishedVersion over AcceptedVersion), then more authoritative repositories (PubMed Central over CiteSeerX) (<http://unpaywall.org/data-format>).

#### Simple Query Tool

The [Simple Query Tool](https://unpaywall.org/products/simple-query-tool) is the simplest way to access Unpaywall data. On the tool’s webpage, paste in a list of DOIs (one per line) and select the output type (CSV, JSON, or Excel). Enter your email address and the results will arrive quickly—usually within a few minutes. Be sure to check your spam folder. The Simple Query Tool has a limit of 1,000 DOIs per submission.

#### API

If you are checking a single DOI or a very large number, you may want to use the API. API queries are formatted as:

http://api.unpaywall.org/v2/YourDOI?mailto=youremail@yourdomain

The results will be in JSON format. To view the output for a single DOI in your browser, you can use an extension such as Chrome’s [JSON Viewer](https://chrome.google.com/webstore/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh?hl=en-US).

A simple way to run a large number of queries is through [OpenRefine](https://openrefine.org/) (previously GoogleRefine). Importing a .csv or .xls\[x] file of DOIs, you can call the Unpaywall API by choosing “Add column by fetching URLs” under “Edit Column.”  

"http://api.unpaywall.org/v2/" + value + "?mailto=youremail@yourdomain" 

The JSON in the new column can be parsed using “value.parseJson()”.

A second option is to use the R client roadoi, described here: <https://cran.r-project.org/web/packages/roadoi/vignettes/intro.html> 

#### Integration with discovery layer

Unpaywall can be implemented within a discovery layer to provide a direct link to the OA version of an article when searching your institution's catalog. See the example from Primo below:

![This shows an example of a journal article where Unpaywall is integrated into the discovery layer.](https://lh4.googleusercontent.com/1jBELo1-CXg5D7Xn89Y1wUws2hcxIX2E7uxbUYRrdfB5xv1b81Grh6uM6g3PajRpHXfONKI2h2izrqIiix4veKaNzbpK_WaxXfBMFn5SIfoTGli6ktc3mnC7x4U7Ed8zEsQVLOI)

### Strengths and weaknesses

#### Strengths

* The tool is free.
* The dataset is free.
* The dataset is very large. 
* The tool is easy to use in its most basic form (Simple Query Tool), yet also offers API access.

#### Weaknesses

* Unpaywall requires a DOI. 
* * It can be difficult to generate a list of all DOIs you need, especially if you do not have access to a subscription tool.
  * Not all publications have a DOI. For example, transactions articles or conference papers are an important form of communication in many disciplines, but not all are assigned at DOI by the publisher.
  * In conducting an analysis of your institution’s publishing, you would miss potentially a large portion of outputs if focusing only on items with DOIs. 

### Who can help

Unpaywall is usually very quick to respond to questions. Contact information is available [here](https://unpaywall.org/team).

- - -

# Journal-level data

## DOAJ (Directory of Open Access Journals)

🔵No subscription required

### Description and uses

DOAJ is a website that hosts a community-curated list of open access journals that meet [DOAJ best practices](https://doaj.org/bestpractice). Its member organizations are publishers, libraries, and research institutions. Their mission is to increase the visibility, accessibility, reputation, usage, and impact of quality, peer-reviewed, open access scholarly research journals globally, regardless of discipline, geography, or language. 

The Directory currently includes information on 15,042 journals and over 5 million articles. Journal metadata includes subject, license, publisher, ISSN, country of publisher, language, APC, and style of peer review.

### Why you might use it

DOAJ is often used as a definitive listing of OA journals or for determining the OA status of a particular title. The metadata for each journal can be searched and filtered in order to get counts of subsets in these categories. It’s also a relatively stable aggregate source for APCs.

### How to use it

* On their site, browse or search to discover journals or categories of journals and get information on individual titles
* Download and use all metadata [as CSV file](https://doaj.org/csv) or as JSON from [Full Data Dump service](https://doaj.org/public-data-dump)
* Provides [OAI-PMH service](http://www.doaj.org/oai) and [search API](https://doaj.org/api/v1/docs)
* Includes a [feed of notification of changes](https://doaj.org/feed)

### Strengths and weaknesses

#### Strengths

* DOAJ indexes journals from around the world. It does not index all open access journals, but does include journals from the Global South as well as the Global North.

#### Weaknesses

* Perceived weakness: DOAJ has a reputation, among some, of indexing poor quality journals (including “predatory” journals). All journals were re-evaluated in 2016 with stricter requirements. 
* DOAJ data sometimes falls out of date. As with SHERPA/RoMEO, specific information such as publication charges and editorial information should be confirmed on the publisher’s website.
* DOAJ [no longer tracks journals’ open access start date](https://blog.doaj.org/2021/02/05/why-did-we-stop-collecting-and-showing-the-open-access-start-date-for-journals/), so inclusion in the directory may or may not indicate OA status for the years analyzed.

### Who can help

[DOAJ FAQ and contact us form](https://doaj.org/contact)

- - -

## SHERPA/RoMEO

🔵No subscription required

### Description and uses

SHERPA/RoMEO is a project from Jisc that aggregates publisher open access policies.

SHERPA/RoMEO has a new interface as of August 1, 2020. The previous version assigned color labels to publications (green, blue, yellow, white). These labels became insufficient to capture the nuances of increasingly complex publisher policies and have been removed altogether. 

Additional information and answers to some FAQs is available at <https://v2.sherpa.ac.uk/romeo/about.html>

### How to use it

On the [search page](https://v2.sherpa.ac.uk/romeo/search.html), enter a journal title or ISSN to retrieve a summary of publication information and the publisher policy for the published, accepted, and submitted versions of articles. An example of a journal with a complex open access policy is Chemical Physics (ISSN: 0301-0104), which has three pathways for making the publisher version OA, three for the accepted version, and one for the submitted version. Clicking on + for any pathway expands to provide more detailed information for each of the icons.

#### API

Information about the new SHERPA APIs is available at <https://v2.sherpa.ac.uk/api/>. Due to the upgrade, the new RoMEO API is complex and the JSON it returns is not easy to parse ([an example of RoMEO JSON output](https://v2.sherpa.ac.uk/cgi/retrieve?&api-key=45A84130-D5AC-11EA-8F2B-2C08C64AD0EC&item-type=publication&format=Json&filter=%5B%5B%22issn%22,%22equals%22,%221946-6234%22%5D%5D)).

#### Working with historical SHERPA/RoMEO data

SHERPA/RoMEO had an API that would return a color for each ISSN. This API was retired in September 2020. Some sources may still use the colors; the definitions were:

| Color  | Policy                                                                                  |
| ------ | --------------------------------------------------------------------------------------- |
| green  | Can archive pre-print and post-print or publisher's version/PDF                         |
| blue   | Can archive post-print (i.e., final draft, post peer review) or publisher's version/PDF |
| yellow | Can archive pre-print (i.e., peer review)                                               |
| white  | Archiving not formally supported                                                        |
|        |                                                                                         |

### Strengths and weaknesses

#### Strengths 

* SHERPA/RoMEO’s strength is that it aggregates a very large number of journal policies.
* The new version of the site and API contain much more detailed information about publisher/journal open access policies. 

#### Weaknesses

* SHERPA/RoMEO’s weakness is that publishers can change their policies as often as they choose and it will be difficult for SHERPA/RoMEO to maintain currency. 
* The color coded “shorthand” to categorize journals was not sufficient for understanding publisher/journal policies, but it was much easier to use.

- - -

## Publisher sites

🔵No subscription required

### Description and uses

This category refers to publisher websites in general; these are maintained by the publishers to provide information about their journals to the public. Different pieces of information may be targeted towards libraries, authors, or readers, and much of it may be useful for various types of OA-related analyses about APCs, licensing, OA policy, and other facets.

#### Why you might use it

Publisher websites are useful as an authoritative source of data and information about a particular journal or portfolio of journals. Critical information that can be obtained from publisher websites may include:

* Open Access business models (which journals are full OA, hybrid, subscription-only, etc.)
* Up-to-date list-price APCs or other OA pricing models
* Creative Commons and other available license options

This data can be critical for estimating existing or future open access spend by authors, for assessing the options available to authors, and for strategizing around various negotiation terms.

### How to use it

Depending on the publisher, the data may be available in a structured way across all journals within the portfolio, or may be only available journal-by-journal in unstructured formats that require manual gathering processes. Strategies and methods therefore need to be tailored to the specific publisher and the data being sought.

If the publisher uses consistent page names and web structures, then it may be possible to write web-scraping functions which can gather data in an automated way that will be more efficient than manual data-gathering. However, this strategy is not guaranteed to be successful or comprehensive.

### Strengths and weaknesses

#### Strengths

* The publisher’s site represents the most authoritative, up-to-date source of information on these journals. Indexing and other tracking services may be delayed in updating their data, or may alter data in translation or interpretation to consolidate with other sources.
* Data gathered in this way is likely to offer the most comprehensive coverage within the publisher (as opposed to aggregated data sources, which may not be entirely comprehensive).

#### Weaknesses

* Publisher sites are all unique; any effort in gathering and refining data is unlikely to be directly transferable to gathering data from other publishers (although general methods such as web-scraping algorithms may be able to help elsewhere).
* Some types of available information may not necessarily be consistent across publishers, making comparisons difficult.
* Data may not be available in machine-readable formats or other formats which allow for easy gathering and incorporation into other analyses; manual processes to gather or encode data may be necessary.
* Historical data (e.g., list price APCs from two years ago) is often unavailable, and so efforts to use this data for historical assessments may incorporate added uncertainty.

### Who can help

This depends on the particular publisher you are gathering data from. Informal discussions with other institutions that have recently worked with that particular publisher may be helpful to gather insights about data-gathering strategies.

- - -

## Vendor OpenURL Knowledge Bases

🔶Subscription tool

### Description and Uses

Vendor [OpenURL knowledge bases](http://en.wikipedia.org/wiki/OpenURL_knowledge_base) (KBs) (e.g., ExLibris 360 KB, ExLibris SFX, OCLC WorldCat, EBSCO KB) contain collections of open access journals. While the accuracy and comprehensiveness of these collections is variable, they can be a useful source of lists of freely available journal titles, ISSNs, and coverage dates at the platform level. 

While KBs often have disciplinary OA collections, these are scattershot and rarely well maintained. KBs are likely to be more valuable as a central source of OA titles by publisher platform. 

### Why you might use them

Although OA journal lists are frequently available on publisher platforms, they can be difficult to find and may lack coverage dates or be in unfriendly formats. Knowledge base lists are useful for identifying open access journals that are included in publisher package lists or COUNTER reports. When these titles are not included in publisher package lists, or when your library does not subscribe to that publisher’s package, they can also be activated to promote use of these journals through your institution’s link resolver.

A comparison between the number of titles listed in one KB’s top 20 publisher specific packages versus the number of titles listed in DOAJ for those same publishers does suggest that the KB collections are more comprehensive. The number of titles listed in the top 20 KB collections ranged from 20 to 780, totalling around 4,000. While DOAJ includes a total of more than 15,300 journal titles, the average number of titles in KB publisher collections was 1.8 (+/-0.2 SE) times higher than the number of titles listed for that publisher in DOAJ. 

### How to use them

This will vary by KB. It is usually relatively simple, if a bit clunky. At least one (OCLC Worldcat) has a field that identifies OA collections. In other cases, it is necessary to search by collection name for “Open Access” or “Freely Available.” These searches yield a manageable number of results which can be sorted by title number, though book collections may need to be filtered out. Collections of interest can typically be downloaded for external use.

### Strengths and Weaknesses 

#### Strengths

* KBs can serve as a useful, complementary repository of open access journal title lists.

#### Weaknesses

* KBs are not necessarily comprehensive, well maintained, or easily discoverable from among the hundreds or thousands of collections they contain. 

- - -

## Cabells Journalytics and Cabells Predatory Reports

🔶Subscription tool

### Description and Uses

Cabells provides two products that report on the “quality” of journals. Cabells Journalytics provides a list of journals they have deemed reputable and Cabells Predatory Reports provides a list of journals they consider questionable. 

The [Journalytics database](https://www2.cabells.com/about-journalytics) includes “a curated list of over 11,000 academic journals spanning 18 disciplines that guides researchers and institutions in getting the most impact out of their research.”

[Predatory Reports](https://www2.cabells.com/about-predatory) provides detailed reports of problematic behaviour they have identified for journals, based on “over 60 behavioral indicators”.

Cabells also offers manuscript preparation services.

### Why you might use it

Cabells Journalytics can be filtered by publisher, discipline, and type of OA (hybrid, green, and gold versus “traditional”). This is another source to find the types and numbers of OA journals in a publisher’s portfolio in a particular discipline. 

### How to use it

Cabells curates both Journalytics and Predatory Reports to guide researchers and institutions in selecting journals that best fit their research. 

* You can filter Journalytics by publisher, discipline, and type of OA.
* Journalytics provides additional, detailed information, including acceptance rates, time to publication, type of peer review, and their proprietary “Cabell's Classificiaton Index.” This might be of more interest to authors than librarians analyzing OA agreements with publishers.

### Strengths and Weakness

#### Strengths

* Journal data is well curated and comprehensive across many publishers.
* Journals are re-evaluated and the list is updated regularly.

#### Weaknesses

* It’s not clear how comprehensive the list is. Currently the list contains 11,000 journals (for comparison, Scopus indexes more than 30,000).
* This resource requires a subscription. References to data, analyses, and visualizations from the tool can therefore only be followed by other subscribers, making replicability a potential issue.
* A more foundational concern is that the product further entrenches particular metrics as indicators of quality. The term “predatory” is also problematic as its application has often been seen to have racist undertones. Subscription publishers can exhibit predatory behaviours but are often not evaluated in the same way. For more, see “[There is no black and white definition of predatory publishing](https://blogs.lse.ac.uk/impactofsocialsciences/2020/05/13/there-is-no-black-and-white-definition-of-predatory-publishing/)” or “[Ethics in academic publishing: A timely reminder](http://jmla.mlanet.org/ojs/jmla/article/view/122).” 

### Who can help

Cabells is a subscription service. Questions can be addressed by contacting the institution account manager. Their contact form is available at <https://www2.cabells.com/contact>. 

# Analytical tools

## OADAT (DeltaThink)

🔶Subscription tool

### Description and Uses

The [OA Data & Analytics Tool](https://deltathink.com/open-access/oa-data-analytics-tool/) (OADAT) is a tool provided by Delta Think, a consulting firm that historically has provided market analysis services to publishers. It is available by subscription; price depends on the number of individual users granted access to the service.

### Why you might use it

The tool provides thorough, in-depth analysis of various trends in the OA marketplace at a global level, with the capacity to narrow down further to specific publishers, countries, regions, etc. Areas covered by the OADAT include:

* APCs: list-price data across many major publishers, collated by publisher, Impact Factor, business model, subject, etc.
* OA market sizing and proportions, by article and by total financial spend.
* Information about other global OA market drivers, including mandates, research funding, and different business models.

### How to use it

The tool has a well-developed interface providing different categories of analysis in a narrative format. No inputs are required from users; the analysis is all based on data gathered by Delta Think, collated into visualizations and dashboards.

### Strengths and weaknesses

#### Strengths

* Data is comprehensive across many publishers, and well researched. Gathering a similar dataset by hand can take significant amounts of time.
* Data is updated regularly and new analyses are added to expand the tool’s offerings often.
* Monthly in-depth analyses are created which explore targeted topics.
* Interactive data visualizations are provided which make the data easier to understand.
* The raw data behind all analyses are available for download to conduct further analysis.

#### Weaknesses

* The OADAT provides thorough global analyses but does not directly incorporate local data (e.g., institutional publishing patterns, institutional subscriptions); raw global data must be downloaded by users to merge with local data for local analyses.
* This resource requires a subscription. References to data, analyses, and visualizations from the tool can therefore only be followed by other subscribers, making replicability a potential issue.

### Who can help

Delta Think has made a [video walk-through](https://youtu.be/3vDjgl_g-Is) and a [digital sandbox](https://deltathink.com/open-access/oa-data-analytics-tool/) (see “Try It Out”).

Staff at Delta Think are generally available to subscribers to offer support in using and understanding the tool. Additionally, some subscription options include committed developer time to help with working with the analyses and raw data. Their contact form is available at <https://deltathink.com/contact-us/> 

- - -

## Unsub (formerly “Unpaywall Journals”)

🔶Subscription tool

### Description and Uses

Unsub (<https://unsub.org/>) is a data dashboard that enables librarians to predict the impact of “unbundling” by comparing individualized title-by-title scenarios to an e-journal package’s status quo. Librarians can customize a dozen parameters that leverage local usage, citation and authorship data, and global OA availability and journal usage patterns to model each scenario’s annualized cost and percent fulfillment in their particular context.

Unsub was developed by [Our Research](https://ourresearch.org/), a 501c3 non-profit ([formerly Impactstory](https://blog.ourresearch.org/our-research/), [Heather Piwowar](https://docs.google.com/document/d/1S7aKmG_l3wJxAc4lb5gJYMwNVDnAT7HlQWcaXADwA1s/edit) and [Jason Priem](https://docs.google.com/document/d/1SkUuOYrpfUF-LC7aC1sBa_phG-_qN-f3hkL9fMooTm4/edit)). It was launched in November 2019 for Elsevier data. Coverage has expanded: Elsevier, Wiley, Springer Nature, Taylor & Francis, and Sage (“The Big Five”) are available. Pricing is based on the size of the library’s materials budget, from $500 for budgets up to $500,000 and $3,000 for budgets of $2.5 million or more (as of May 2021). A consortial version and discounts may be available.

Unsub has a variety of openly available recordings, including a [20-minute video overview](https://vimeo.com/420183913) from May 2020 ([plus several others](https://vimeo.com/user113300769)). Demos are available; send an email from the [unsub.org](https://unsub.org/) homepage to request one.

### Why you might use it (and what data you get out)

* Editor’s note: this description is based on the COUNTER 4 version of Unsub; the COUNTER 5 version will be reviewed for a future update of this section
* Libraries may choose to use Unsub when finances and/or principles call for evaluation or cancellation of a major publisher e-journal package. 
* Unsub is designed to rank paywalled titles based on their “cost effectiveness,” which incorporates local and global usage patterns, local citation and authorship, open access availability, perpetual access rights, and local cost parameters.
* * Nearly all parameters can be customized and/or excluded in a variety of alternative scenarios created by the library.
* Unsub returns the average estimated annual cost of subscriptions plus ILL based on a 5-year forecast that incorporates full access to subscribed titles selected in each scenario.
* Data you can get from Unsub:
* * Availability:
  * * Estimated percent of content available for instant usage: i.e., from Open Access, Backfile, ASNs, or Subscription \[instant_usage_percent]
    * * Unsub includes, distinguishes, and can display percent availability by academic social networks (e.g., ResearchGate)
    * Estimated percent OA availability, which takes into account [title-specific download decay curves](https://www.biorxiv.org/content/10.1101/795310v1) (i.e., distribution of article level usage by year of publication) \[use_oa_percent]
    * * Unsub includes and distinguishes and can display Hybrid, Bronze, Green, peer-reviewed, and not peer-reviewed 
      * It can also incorporate embargo periods for “delayed OA journals,” which make works at least temporarily available after some date \[bronze_oa_embargo_months]
    * Percent delayed access/not available \[use_other_delayed_percent] 
  * Usage
  * * Downloads, from library-uploaded COUNTER reports
    * Expected number of citations by your institution’s authors, based on the patterns of the previous five years \[citations]
    * Expected number of articles with at least one author from your institution, based on publication patterns from the previous five years \[authorships]
  * Costs
  * * Journal subscription price, based on the list prices or from uploading a custom price list \[subscription_cost]
    * ILL costs, which are based on multiple parameters (see [this article](https://intercom.help/get-unsub/en/articles/4061177-how-do-we-calculate-ill-requests-and-ill-cost) about how Unsub estimates ILL costs) \[ill_cost]
  * Estimated Publishing Costs
  * * To calculate the APC spending from your institution, the list APC from the publisher’s website is multiplied by the total fractional authorship
    * * Unsub assigns fractional authorship based on the number of authors from your institution in the author list (e.g., if a paper is published OA and two of the three authors are from your institution, the fractional authorship is 66%)
      * This workaround is necessary because Unsub does not yet have data on which author is the corresponding author. There is also no guarantee that the corresponding author paid part or all of the APC
  * Many of these data fields are available for download. For descriptions, see [What are the columns in Download as Spreadsheet?](https://intercom.help/get-unsub/en/articles/4246610-what-are-the-columns-in-download-as-spreadsheet) 
  * Libraries develop scenarios based on their estimated price increases, costs for ILL, perpetual access rights, and tolerance for delayed/reduced access
* Unsub uses historical data to forecast costs for the next five years

### How to use it

* Editor’s note: this description is based on the COUNTER 4 version of Unsub; the COUNTER 5 version will be reviewed for a future update of this section
* The subscribing library creates a package by uploading a recent 12-month COUNTER report(s)
* * COUNTER 4 JR1s, or
  * Added May 2021: COUNTER 5 TR_J2, TR_J3, TR_4
  * * See the [new release notes](http://help.unsub.org/en/articles/5238375-release-notes-may-2021) for changes
* Configurable Parameters
* * Post cancellation access rights: titles by year
  * * Default is 2010
  * Title by title costs, specific and/or parameters
  * * List price is used if local cost data is unavailable
  * ILL usage and cost parameters
  * Parameters for relative importance of usage, citation, and publication from local perspective
* Data Sources
* * Uses global data collected from the Unpaywall dataset of OA availability and request patterns
  * Uses recent local usage and cost data to forecast scenario costs over the next five years
  * Default prices are based on publisher-reported list prices
* Output
* * Title-by-title spreadsheet export containing summary of recommended subscribe/do-not-subscribe determinations
  * The export provides “fuzzed” data for sharing more widely. These are low, medium, or high for: cost per use, subscription cost, subscription minus ILL cost, downloads, citations, authorships.

### Strengths and weaknesses

#### Strengths

* Provides access to title-level article-demand curves, OA availability, and local publication and citation data, which most libraries lack 
* The five largest for-profit publishers (Elsevier, Wiley, Springer Nature, Taylor & Francis, and SAGE) were available as of Spring 2021
* Uses multiple data sources to provide a much more sophisticated and localized metric of journal value ([net cost per paid use](https://support.unpaywall.org/support/solutions/articles/44001843595-description-of-data-fields#:~:text=Net%20cost%20per%20paid%20use,getting%20for%20your%20subscription%20dollar.)). 
* Most parameters can be adjusted by the library to reflect their local objectives, priorities, and perspective 
* The results are highly actionable

#### Weaknesses

* Definitions and assumptions (and the impact of deviating from default settings) need to be better understood and further explored
* * Delayed access costs assume by default that 19 out of 20 full-text requests for paywalled article access will go unfilled, i.e., there is an assumption of a 95% reduction in access to articles that are not available via backfile or open access although this parameter is adjustable in the system it is determined by user behavior
  * Usage is redefined as including significant impact of citation (x10) and publication (x100) although these parameters are adjustable
* Complex model behind output makes a comprehensive understanding of the results very challenging
* * The many parameters are interdependent and complex
* Does not address fully OA journals given lack of ability to measure use

### For more information

* [Understand the data | Unsub](https://intercom.help/get-unsub/en/collections/2361360-understand-the-data)
* Publicly available demonstration recording for [RLUK](https://youtu.be/eXOxkP8kxaw)
* SPARC members can contact SPARC for the password to a recording from 30 June 2020.
* Some people (within SPARC DAWG) might be able to help you!
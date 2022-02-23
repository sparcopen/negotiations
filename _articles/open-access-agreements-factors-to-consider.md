---
layout: post
date: 2022-02-23T19:59:58.631Z
title: "Open Access Agreements: Factors to Consider"
summary: This document provides an overview of questions and factors to consider
  when evaluating potential investments in open access. It is a companion to
  Data Sources for Analyzing Open Access Offers from Publishers.
working-groups:
  - Data Analysis
authors:
  - Allison Langham-Putrow
  - Yuan Li
full_page: false
---


# Introduction

This document is intended to provide an overview of questions to ask and factors to consider when evaluating potential investments in open access (OA). 

* When evaluating an offer from a publisher that incorporates an open access component with a subscription offer. This might include offers for read-and-publish/publish-and-read agreements or tiered membership models.
* When evaluating an OA membership model that provides your institution’s authors with a discount on \[or removal of] article processing charges (APCs).

There are many other models for open access transformations. Many of the same principles described in this document would apply to evaluating those offers. 

You can refer to [OA analysis data sources](https://docs.google.com/document/d/1ganUpSjF_HPp3mamm-ayuWCgOWhC5mvNO8bEIoXTn6o/edit#heading=h.n6jzpihj2nkr) for information on tools available for gathering this data.

In evaluating any OA offer, one must remember that collections decisions are based on many factors. Each subscription must be considered within the institution’s entire collections portfolio. This document addresses questions specific to agreements that include some sort of OA component.

# Fundamental questions

Before anything else, an institution should consider these fundamental questions:

* Does this publisher align with your institution’s values?
* Does the publisher’s open access model align with your institution’s values?
* What is the publisher’s history with open access? Have they demonstrated a commitment to full OA? 
* How transparent is the publisher with its business model and agreements with other institutions? 
* How equitable is the model? Will researchers or institutions who cannot afford to pay per article continue to be able to publish in the journals?
* What exactly are our institution’s options moving forward? Is status quo an option, or are there multiple paths into the future that we need to choose from?
* Do we believe enough institutions will adopt the offer to change the overall model of the publisher?
* How does the model decision fit into the larger picture? Could there be unintended effects if we decide to participate or not? 

# Data-related factors to consider

## How important is the material to my community? 

Most institutions cannot afford to support publishers that are not important for their community. We consider three types of usage data: downloads, citation, and authorship. This data can be used as indicators for the value of the publisher’s materials to their user community. 

### Downloads

Number of downloads can indicate your community’s interest in a particular journal or group of journals. Trends in usage can indicate areas of emerging research interest.

COUNTER reports are the most common sources of download data. See [COUNTER 4 versus COUNTER 5](https://docs.google.com/document/d/1pm1IY_-L1skGibOAfy5hOC1gBTN9SNL8yMtIKi4drDs/edit) for an explanation of COUNTER reports and the key data elements they provide. 

With the release of COUNTER 5, usage of OA materials is separated. Since libraries mostly pay publishers through subscription fees, OA material should not be included in cost-per-use calculations. The “Journal Requests, Excluding OA_Gold* (TR_J1)” report shows usage of subscription content, excluding Gold Open Access content.

#### Benefits: 

Download data is more inclusive of the ways in which scholarly literature is used in an institution. Citation and authorship are specific to research uses—they are based on research outputs that are indexed by databases. Usage by download can indicate the importance of a particular title to the educational mission of an institution. 

#### Drawbacks:

Download data is just one indicator of the value of the subscription portion of an agreement, and has various limitations noted above. Also, download data can overestimate the value of material—not all downloads are ultimately used in research; researchers may download articles that they never read or put to use in their research. 

Fully OA publishers (and fully OA journals) may not offer COUNTER data, so this data point is most readily available for considering offers that combine subscriptions with OA.

### Citations

Citations by your institution’s authors to a publisher’s output is an indication of how important the material is for their research. 

It is possible to extract citation data from Crossref API output based on a list of DOIs for publications from your institution.

Unsub gathers data on citations from [Microsoft Academic Graph](https://intercom.help/get-unsub/en/articles/4055293-where-do-we-get-your-faculty-s-citation-and-authorship-data). Unsub is described in [OA analysis data sources](https://docs.google.com/document/d/1ganUpSjF_HPp3mamm-ayuWCgOWhC5mvNO8bEIoXTn6o/edit#heading=h.aa6e6hfkwl4p).

Citation data is available through both the Web of Science and the Scopus APIs. See more detail on Elsevier’s [Scopus API website](https://dev.elsevier.com/sc_apis.html).Use of the API requires you to apply for an API key. Information on receiving help with using the APIs are available on [Elsevier’s website](https://dev.elsevier.com/support.html). More information on Web of Science API is available on Clarivate's [Swagger description page](https://api.clarivate.com/swagger-ui/?url=https%3A%2F%2Fdeveloper.clarivate.com%2Fapis%2Fwos%2Fswagger) (see/references).

#### Benefits: 

Citation data is an indicator of how cancellation of a journal would affect researchers. Presumably, cancellation of highly cited journals would be “felt” more heavily by the user community. 

#### Drawbacks:

There are limitations to using citation data as an indicator of the value of a journal. Not all “use” of materials by researchers is captured through citations in scholarly publications. The importance of a title to researchers in disciplines where outputs are not scholarly journal articles can be underestimated by citation data (e.g., researchers in social work or education may create materials for practitioners in the field; citations in these materials would not be captured through Scopus or Web of Science).

### Authorship

For the third type of usage data, we assume that authors publish in the journals that they value. Many librarians are also used to getting requests to subscribe to journals in which their institution’s researchers have published, indicating the importance from the researcher’s perspective. 

Subscription data sources include major databases, such as Scopus, Web of Science and Dimensions. Author disambiguation remains a challenge and can affect the accuracy of data.

Unsub aggregates this data from Microsoft Academic Graph. 

A faculty activity reporting system that is used institution-wide is another source of authorship data.

This data can be requested directly from the publisher. The publisher may or may not be willing to provide the data. Some may also report being unable to gather this data (e.g., some societies partner with commercial publishers; the publishers may not be able to provide data for the society’s journals).

Other important aspects of authorship data are OA status, current APC spending, and total spending.

### Authorship/OA status

Again, with a set of DOIs, Unpaywall can return the OA status, including the type of OA, which would indicate whether authors are using paid OA options or archiving their work in open repositories (green OA).

Another use of this data is to estimate how much work would be made OA if your institution participated in the offer.

### Authorship/current APC spending

Authorship data can also be used to estimate the potential savings across the institution (although not necessarily from the library’s budget if the library is not currently paying APCs on behalf of authors if all authors were to take advantage of the agreement.

The question of *who* is paying the APC is difficult to resolve. Articles often have multiple authors, from multiple institutions. There is no convention for which the author pays the APC. Offers generally apply to articles in which the corresponding author is from the participating institution. There are conventions for choosing the corresponding author; these vary among disciplines and in some cases, the designation is not particularly important, which creates the possibility for authors to “shop around” and select the corresponding author as the author from the institution with the best deal on APCs.

Another option for gathering this information would be to contact the publisher. However, from experience, publishers have reported being unable to provide institution-based spending data.

### Authorship/total spending

Some publishers still charge authors page fees, color image fees, cover art fees, general publication charges, etc. If these charges are paid through the university, university accounting systems can provide data on how much authors have spent with journals. However, some authors pay these fees from personal funds, in which case it would require a very high level of effort to estimate. Journals charging such fees would need to be identified and individual articles would need to be examined for length beyond the set page limit, images, etc. This requires a significant time investment and may not be worth the effort. The data can show whether the publisher already has a significant stream of funding beyond APCs—if the publisher is taking even more money from the institution, one must consider whether they “deserve” additional funds. 

## Prevalence of OA

How much of the publisher’s work is currently OA may indicate how close the publisher or journal is to a “full flip” to OA. When this flip *should* occur is debated by many. Plan S specifies that a “[transformative journal](https://www.coalition-s.org/transformative-journals-faq/)” (a designation for a specific type of hybrid journals that are Plan S compliant) should make a full flip to OA by the time 75% of its content is published OA. In response to the initial proposed Plan S requirement of flipping at 50%, [Springer Nature](https://group.springernature.com/gp/group/media/press-releases/alternative-conditions-needed/17508260) argued that the flip should not occur until 90% of content is OA.

Estimating the amount of OA content within a journal or publisher package is difficult. Scopus and Web of Science use Unpaywall data to identify OA articles and which type of OA. Unfortunately, both are subscription databases and neither allow searching by publisher. For smaller publishers, with a manageable number of journal titles, you can design a search in Scopus or Web of Science for the titles and analyze the results by OA type. 

Unsub allows for the export of a field called “use_oa_percent.” This is an estimate of how much of your institution’s use is of OA content in a journal. The value is based on data from the [Unpaywall browser extension](https://intercom.help/get-unsub/en/articles/4537771-where-do-we-get-year-of-publication-data-for-backfile-and-open-access-calculations). 

Another option is to request this data from the publisher. However, in our experience, publishers have been reticent to provide this data beyond publications for your institution.

## Pricing/payment structure

OA offers can take many forms. With models like [Subscribe to Open](https://crln.acrl.org/index.php/crlnews/article/view/24227/32038) or [SCOAP3](https://scoap3.org/faqs/), libraries are participating in coordination with many other libraries to make journals completely open. In read-and-publish/publish-and-read, payments are based on the institution’s number of publications. 

* Can we afford the offer right now? 
* If we wanted to accept the offer, would we have to make cuts elsewhere to support it and are those cuts we would want to make? 
* If publishing patterns from your institution change, will our ability to afford an agreement change? 

Some OA agreements are termed “cost neutral” because they are based on the total payment from the libraries (i.e., subscriptions and possibly APCs) and rest of the institution (i.e., researcher-paid APCs) and the total number of publications, often averaged over some past period. For this type of agreement, libraries must consider:

* How much, beyond what the library pays, is being paid from our institution?
* Are researchers using grant funding?
* Do we want to enter into an agreement that expects/requires researchers to use their grant funding for publishing?
* Does the library’s budget office have capacity to manage article-based payments?

# Additional considerations

* What kind of profit or surplus does the publisher make from its publications? 

  * Publicly traded commercial publishers are beholden to their shareholders to make a profit. They report their income, expenses and profits in annual reports (See [MIT’s website](https://libraries.mit.edu/scholarly/publishing/elsevier-fact-sheet/) for an example). To what extent do you believe your institution should be supporting this?
  * Scholarly societies often rely on surplus income from their publishing operations to fund their other activities (e.g., conferences, scholarships). (See David Lewis’s [Scholarly Societies and the Newspaper Problem](https://scholarworks.iupui.edu/handle/1805/17836) for more on this). To what extent do you believe the library budget should fund society activities? Should one discipline be prioritized over others?
* How important is it to continue supporting a publisher? For example, is support for a society publisher essential to maintain positive library-research community relations?
* What else can be negotiated into a license? Can you retain authors’ rights to post articles wherever they choose? Would the publisher set up a feed directly to your institutional repository? 

# Scenarios

## Evaluating publisher offers

Here we describe four scenarios and the types of questions we would ask when evaluating an agreement. For any scenario, first consider the fundamental questions listed at the beginning of this document.

**Scenario 1: A fully OA publisher offers a model in which the institution pays a flat fee to support the making of all publications from your institution OA. (Example: [Jisc’s agreement with PLOS](https://theplosblog.plos.org/2020/10/new-apc-free-open-access-agreements-test-alternative-funding-models/))**

1. What is our institution’s usage?

   1. Consider COUNTER statistics, publisher-provided data on downloads/views from our IP ranges, number of articles published, number of citations to the publications
2. What is our current investment with this publisher?

   1. What do we, as the library, pay?
   2. What is our institution’s current investment with this publisher? Include APCs and other publication charges (e.g., page charges, color figure charges) in this amount.
3. What will the costs for the new model be?

   1. Will the costs currently paid by authors be incorporated into the payment from the library?
   2. Will the publisher continue to charge our authors fees of any type?
4. How do the costs align with our budget?

   1. Will our library’s collection budget be able to afford the model? Are there places where the budget can be cut to redirect spending towards OA publishing?
   2. What kind of stability in pricing will we need from the publishers and will they assure it? If the library’s payment is based on a per-article-published rate, what will happen if this increases or decreases over the length of the agreement?
5. What kind of profit or surplus does the publisher make from its publications? Does this align with our library’s values?
6. Will we continue to have the same access we currently do? Will we need to purchase backfiles or pay for additional services (e.g., text mining, publisher platforms)?
7. How transparent are the agreements the publisher has with other institutions? 

   1. Are participating institutions able to provide information about how the agreement is being implemented? 
   2. Is the price fixed for all institutions or does each institution negotiate a separate agreement? Are the agreements subject to NDAs?
   3. What challenges have they experienced in implementing the agreement?
8. What evidence can the publisher provide to demonstrate how their publications are reaching a wide, inclusive, appropriate audience?

 

**Scenario 2: A publisher offers a collective action model where all (or most) institutions must participate to transform the publisher’s entire portfolio of publications from subscription to full open access. (Example: [European Mathematics Society’s Subscribe to Open program](https://ems.press/subscribe-to-open))**

1. What is our institution’s usage?

   1. Consider COUNTER statistics, publisher-provided data on downloads/views from our IP ranges, number of articles published, number of citations to the publications
2. What is our current investment with this publisher?

   1. What do we, as the library, pay?
   2. What is our institution’s current investment with this publisher? Include APCs and other publication charges (e.g., page charges, color figure charges) in this amount.
3. What will the costs for the new model be?

   1. Will the costs currently paid by authors be incorporated into the payment from the library?
   2. Will the publisher continue to charge our authors fees of any type?
4. How do the costs align with our budget?

   1. If our library does not currently fund this publisher, how will we pay for the model?
   2. Will our library’s collection budget be able to afford the model? Are there places where the budget can be cut to redirect spending towards OA publishing?
   3. What kind of stability in pricing will we need from the publishers and will they assure it? If the library’s payment is based on a per-article-published rate, what will happen if this increases or decreases over the length of the agreement?
5. Will we continue to have the same access we currently do? Will we need to purchase backfiles or pay for additional services (e.g., text mining, publisher platforms)?
6. Are participating institutions able to provide information about how the agreement is being implemented? What challenges have they experienced in implementing the agreement?
7. What is the publisher’s long term plan? What will happen if they do not reach the required number of participants in future years?
8. If it is a society publisher, what kinds of relationships do our institution’s researchers have with it? Do researchers consider the society essential to their work? Is it of broad interest across campus?
9. What evidence can the publisher provide to demonstrate how their publications are reaching a wide, inclusive, appropriate audience?

 

**Scenario 3: APC-based read-and-publish/publish-and-read agreement with a medium to large publisher. (There are many examples in the [ESAC registry](https://esac-initiative.org/about/transformative-agreements/agreement-registry/).) One of the most well-documented agreements is the publish-and-read agreement between Projekt DEAL and Wiley.**

1. What is our institution’s usage?

   1. Consider COUNTER statistics, publisher-provided data on downloads/views from our IP ranges, number of citations to the publications
2. How many articles does our institution publish? 

   1. How many are paid OA? 
   2. How many are OA through other means (e.g., green OA through author deposit)
3. What is our current investment with this publisher?

   1. What do we, as the libraries, pay?
   2. What is our institution’s current investment with this publisher? Include APCs and other publication charges (e.g., page charges, color figure charges) in this amount.
   3. How many of our instititon’s publications are paid OA? How many are OA through other means (e.g., green OA through author deposit
4. What will the costs for the new model be?

   1. Will the costs currently paid by authors be incorporated into the payment from the library?
   2. Will the publisher continue to charge our authors fees of any type?
5. What kind of profit or surplus does the publisher make from its publications? Does this align with your library’s values?
6. What proportion of the journals’ content is OA?
7. How do the costs align with our budget?

   1. Will our library’s collection budget be able to afford the model? Are there places where the budget can be cut to redirect spending towards OA publishing?
   2. If payments from authors are incorporated into a new price for the program, will the library alone be able to afford it? 
   3. What kind of stability in pricing will we need from the publishers and will they assure it? If the library’s payment is based on a per-article-published rate, what will happen if this increases or decreases over the length of the agreement?
8. What will be the process for managing per article charges? 

   1. How easy will it be for authors to identify their eligibility within the publisher’s system? 
   2. Will there be a process for refunding authors who pay an APC but are later determined to be eligible?
   3. What level of administrative effort from library staff will be required to manage the agreement?
9. Will we continue to have the same access we currently do? Will we need to purchase backfiles or pay for additional services (e.g., text mining, publisher platforms)?
10. How transparent are the agreements the publisher has with other institutions? 

    1. Are participating institutions able to provide information about how the agreement is being implemented? 
    2. Are their agreements, particularly the prices, subject to NDAs?
    3. What challenges have they experienced in implementing the agreement?
11. How viable do we believe the model is? 

    1. How many institutions are currently participating?
    2. What is the publisher’s long term plan, how will they reach fully OA?
    3. If the model for full OA is based on per-article charges, how will the publisher ensure that all researchers, regardless of funding, can publish in their journals?
12. If it is a society publisher, what kinds of relationships do our institution’s researchers have with it? Do researchers consider the society essential to their work? Is it of broad interest across campus?
13. What evidence can the publisher provide to demonstrate how their publications are reaching a wide, inclusive audience?

 

**Scenario 4: Tiered model for hybrid publisher, where the price is based on some indication of the size of the institution, perhaps based on FTEs or annual number of publications. (Example: [ACM OPEN](https://libraries.acm.org/subscriptions-access/acmopen))**

1. What is our institution’s usage?

   1. Consider COUNTER statistics, publisher-provided data on downloads/views from our IP ranges, number of articles published, number of citations to the publications
2. What is our current investment with this publisher?

   1. What do we, as the libraries, pay?
   2. What is our institution’s current investment with this publisher? Include APCs and other publication charges (e.g., page charges, color figure charges) in this amount.
3. How many articles does our institution publish? 

   1. How many are paid OA? 
   2. How many are OA through other means (e.g., green OA through author deposit)
4. What is our current investment with this publisher?

   1. What do we, as the library, pay?
   2. What is our institution’s current investment with this publisher? Include APCs and other publication charges (e.g., page charges, color figure charges) in this amount.
   3. How many of our instititon’s publications are paid OA? How many are OA through other means (e.g., green OA through author deposit
5. What will the costs for the new model be?

   1. Will the costs currently paid by authors be incorporated into the payment from the library?
   2. Will the publisher continue to charge our authors fees of any type?
6. What kind of profit or surplus does the publisher make from its publications? Does this align with your library’s values?
7. What proportion of the journals’ content is currently OA?
8. How viable do we believe the model is? 

   1. How many institutions are currently participating?
   2. How realistic does it seem that others would participate based on the pricing model?
   3. What is the publisher’s long term plan, how will they reach full OA?
   4. If the model for full OA is based on per-article charges, how will the publisher ensure that all researchers, regardless of funding, can publish in their journals?
9. If it is a society publisher, what kinds of relationships do our institution’s researchers have with it? Do researchers consider the society essential to their work? Is it of broad interest across campus?
10. What evidence can the publisher provide to demonstrate how their publications are reaching a wide, inclusive audience?

 

## Evaluating the landscape for potential partners

Not all publishers have developed transformative models. Smaller publishers, and especially society publishers, may not have had the capacity/chance to consider how they might transform to full OA publishers. Questions you might consider:

Are you part of a consortium? Has your consortium expressed interest in supporting new OA models? 

* Working with a group of institutions may lead to the development of a model that would have broad appeal and adoption.
* Publishers may benefit by being able to reduce the number of negotiations they have to carry out.
* Libraries can gain a better understanding of how the publisher operates
* Libraries can gain a better understanding of how other institutions operate and their beliefs and priorities for transformations..
* Publishers may be more willing to work to develop the model if they think it will appeal to many institutions.

Is the publisher working with other institutions? Have they implemented a model with other institutions?

* Most publishers/journals will have information pages on their websites describing agreements they have. Some publishers and some institutions will share out press releases when a new agreement is signed.
* The [ESAC registry](https://esac-initiative.org/about/transformative-agreements/agreement-registry/) has information about transformative agreements between many institutions/consortia and publishers. Each agreement has basic information but terms and pricing are not always available.

Have you learned of any society publishers important to your institution who are considering a transition to full OA? 

* Many of the largest publishers already have established transformative models and may not be open to discussions about what an agreement should look like.
* Society publications chairs and editors often work at universities. Some may have strong relationships with their society and be in a position to start discussions about potential transitional models.
* Society publication editors may approach the library for assistance in understanding new developments/requirements for OA (e.g., how to manage Plan S requirements if their journal has authors who are funded by [cOAlition S members](https://www.coalition-s.org/organisations/)). This can be an entry to discussing a variety of models and a chance to develop one that works for both society and libraries/institutions.
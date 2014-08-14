#Developing a Research Object - Clinicalcodes.org

### Q:  What Is the Purpose of the Research Object? (See Determining the Purpose of a Research Object Using User Stories.) ###

e.g. Paper Publication with supporting material, Record of Experimental Process,  Publication of Code, Data Publication, Software Publication, Basic Aggregation, Other?  

I want to export a study so that I can import the cohort descriptions into FARSITE.  


###Q:  What resources do you need to share to support that purpose?

To support this the resources required are: 
1. The publication describing the study itself.
2. Each of the codelists that was used as part of the study.
 
###Q:  Do those resources currently reside online or offline? 

The publication describing the study will be published and typically resides online in a digital library.
The code lists for the publication are hosted online at clinicalcodes.org 

###Q:  What identity mechanism/s currently exist for those resources? 
Recommendation: Permanent Identifiers (PIDs) or Permanent URLs (PURLs) are preferred over standard URLs.  

The publication is typically identified by a DOI, which has a supporting URL scheme e.g http://dx.doi.org/10.1136/bmj.g330 
The codelists are each identified by a URI/URL on clinicalcodes.org e.g. https://clinicalcodes.rss.mhs.man.ac.uk/medcodes/article/5/codelist/asthma_clinicals/

###Q:  What are the licensing requirements/restrictions for each of those resources? 

The licensing of the paper publication will vary according to the publisher’s restrictions. 
 
###Q:  Do you need to support the exchange and use of the Research Object’s resources offline?  


###Q:  Do you need to manage versioning of the Research Object and its resources?  If so what constitutes a new version of your Research Object?

###Q:  What additional metadata must / should / is optionally required to support the stated purpose of the research object?
The following provides an example of the metadata that should be shared alongside the article:

````json
{
	"article_ID" : 5,
    "article_title" : "Withdrawing Performance Indicators: Retrospective Analysis of General Practice Performance Under the UKs Quality and Outcomes Framework",
    "article_author" : "Kontopantelis, Evangelos; Springate, David; Reeves, David; Ashcroft, Darren; Valderas, Jose M; Doran, Tim",
    "article_year" : 2014,
    "article_type" : "Research article",
    "article_journal" : "British Medical Journal",
    "article_doi" : "http://dx.doi.org/10.1136/bmj.g330",
    "article_link" : "http://www.bmj.com/content/348/bmj.g330?ijkey=AwxEb4LKHleAKNk&keytype=ref",
    "article_abstract" : "Objectives: To investigate the effect of withdrawing incentives on recorded quality of care, in the context of the UK Quality and Outcomes Framework pay-for-performance scheme. Design: Retrospective longitudinal study. Setting: Data for 644 general practices, from 2004/5 to 2011/12, extracted from the Clinical Practice Research Datalink. Participants: All patients registered with any of the practices over the study period, 13,772,992 in total. Intervention: The removal of financial incentives for aspects of care for patients with asthma, coronary heart disease, diabetes, stroke and psychosis. Main outcome measures: Performance on eight clinical quality indicators withdrawn from a national incentive scheme: influenza immunisation (asthma) and lithium therapy monitoring (psychosis), removed in April 2006; blood pressure monitoring (coronary heart disease, diabetes, stroke), cholesterol level monitoring (coronary heart disease, diabetes) and blood glucose monitoring (diabetes), removed in April 2011. Multilevel mixed effects multiple linear regression models were used to quantify the effect of incentive withdrawal. Results: Mean levels of performance were generally stable after the removal of the incentives, both short- and long-term. For the two indicators removed in April 2006/7, levels in 2011/12 were very close to 2005/6 levels, although a small but statistically significant drop was estimated for influenza immunisation. For five of the six indicators withdrawn in from April 2011/12, there was no significant impact on performance in that year following removal and differences between predicted and observed scores were small. Performance on related outcome indicators retained in the scheme (e.g. blood pressure control) was generally unaffected. Conclusions: Following the removal of incentives, levels of performance across a range of clinical activities generally remained stable. This indicates that health benefits from incentive schemes can potentially be increased by periodically replacing existing indicators with new indicators relating to alternative aspects of care. However, most of the aspects of care we investigated remained indirectly incentivised and further work is required to assess the generalisability of the findings when incentives are fully withdrawn.",
    "article_fulltext" : true,
    "article_correspondence_author" : "Evangelos Kontopantelis",
    "article_correspondence_email" : "e.kontopantelis@manchester.ac.uk"
    }
````
###Q:  What controlled vocabularies currently exist to support the recording of that metadata?  

There are controlled vocabularies 

<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Media_to_Info

Building AI course project - Extract textual information from spoken or visual media

## Summary

Compute audio and video speech content in order to extract named entities, topics sentiment and other relevant information in order to process the information as text and generate inter-operability, findability and, more broadly, better contextualization for these types of content within a given ecosystem. Further use would be to analyze the bias for these ecosystem through time for further use in other applications.


## Background

* Findability issue: In various ecosystem, such as news media platforms, it is difficult, at best, to find all related information tied to a topic or a named entity as the spoken media content is rarely tagged with all the potentially appropriate information.
* Historicity issue: In a business context, it is often very difficult to identify an issue that have been reported both through textual content (emails) and on the phone. Moreover, there's rarely a possible regression path to identify the root of the problem as the content is not accessible through time. The idea here would be to create a timeline for any potential issue that could be identified regardless of the input medium.


## How is it used?

Content is picked up from archives or as post-production and the information extracted is stored as a graph. Data can then be exposed through a search engine UI, custom dashboard or API, depending on the use case. Extracted information would also be stored as metadata for every document and be reprocessed asynchronously in order to be enriched as our information extraction models are updated.


## Data sources and AI methods

To simplify the project, news media archives could be used as single ecosystem. For instance, the following platform could be used to extract and process audio and videos content from current feeds and archives:
https://ici.radio-canada.ca/
https://ici.radio-canada.ca/ohdio/premiere
https://ici.radio-canada.ca/archives

## Challenges

The project is limited by the sheer volume of potential information and the necessary concept of a define ecosystem to identify a bias. A general applicability to the model would also require a similar capacity to process multiple languages with the same level of accuracy.

## What next?

The idea would be to integrate the system as a commodity for any organization (or users) wanting to extract information from audio and video content in order to make it operable or findable. Required infrastructure would likely be an important component to develop in order to build a scalable application that could be used iteratively on rich media content both in real-time or asynchronously.


## Acknowledgments

Thanks to the University of Helsinki for the Building AI course.

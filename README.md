# Full-Text Search Based on Lucene

## Abstract

This paper introduces us the full-text search engine based on Lucene and full-text search technology, including in-dexing and system architecture, compares the full-text search of Lucene with the String search retrieval’s response time, the experimental results show that the full text search of Lucene has faster retrieval speed.

## Introduction
The core of information is the full-text search technology. Full-text search technology provided us with the information retrieval tool according to the content of data rather than the external features based on a variety of computer data such text, sound, image as processing object. Create all the possible terms in the index which are searched by network users as well as help people to manage and order extensive information and enable network users to quickly and easily retrieve any information they need. Lucene is a pure Java software  project which is free and open source. In recent years, Lucene has become one of the most highly praise and most popular information retrieval library. 

## Apache Lucene

Apache Lucene is a high-performance, full-featured text search engine library written entirely in Java. It is a technology suitable for nearly any application that requires full-text search, especially cross-platform. It offers implementation of algorithms for creating indexes and doing search and ranking of documents based on query. Its provides a very sophisticated querying model and support document faceting as well.

### Process of Full Text Search

1. Build a Text Database :  we should build a text database which is used to store all information retrieved by the user, then determine
text model of retrieval system.

2. Create Indexing : Create index with the model according to the text of database. Indexing can greatly improve the speed of information retrieval. Which way do you use depends on the scale of information retrieval system. Large-scale information retrieval systems such as Google take advantage of the approach of inverted index. 

3. Search : After indexing the documents, you can start to search
information you need. Search requests are submitted by
the users and information retrieval systems to preprocess
and search the information eventually return user the
information.

4. Filter and Sort the Results :  After the information retrieval system search the information that the users need and it will filter or sort the
information by making a certain rule and then return the
user related information

## What is Elasticsearch 

Elasticsearch is also an open-source search engine built on top of Apache Lucene. Elasticsearch is a distributed, open-source search and analytics engine built on Apache Lucene and developed in Java. Elasticsearch allows you to store, search, and analyze huge amount of data quickly and in real-time and give back answers in milliseconds. It’s able to achieve fast search responses because instead of searching the text directly, it searches an index.   Additionally, it supports full-text search which is completely based on documents instead of tables or schemas.

### Benefits of Elasticsearch
1. High Performance 

2. Near real-time operations 

3. Fast time-to-value

4. Easy application development 
5. Effective Investment Right Out of The Box 

6. Scalability 
 
### What is Elasticsearch used for?

Elasticsearch’s primary use cases and examples of how companies are using it today.
1. Application Search 

2. Website Search

3. Enterprise Search

4. Logging and log analytics

## Apache Solr

Apache Solr (stands for Searching On Lucene w/ Replication) is a free, open-source search engine based on the Apache Lucene library. An Apache Lucene subproject, it has been available since 2004 and is one of the most popular search engines available today worldwide.

Solr provides advanced real-time searching capabilities such as fielded search, spell check, wildcards, joins, grouping, auto-complete and many more across different types of data.

- Solr and Elasticsearch are similar in many ways. They are abstractions built on top of Lucene that add enhanced search functionality, both Solr and Elasticsearch have been adapted for analytics use cases as well as enterprise search.
- Solr is an older technology and certainly still has many fans and an experienced community. If you judge by the size of the community, however, Elasticsearch overtook Solr a few years ago. 

- Solr started as a search engine on top of Lucene. Though it is still open source but it is embedded into a commercial product by Lucidworks which can provide enterprise search by connecting to various data sources.

### Similarities between Apache Solr and Elasticsearch-

Apache Solr and Elasticsearch are the search engines implemented using Lucene library. Using the featured provided by Lucene both have great job in making search and analysis easy and developer friendly. Both has very competitive features like:

- Both expose API end points for indexing and searching content.
- Both support structured and unstructured content.
- Both have means to connect with data sources.
- Both supports very comprehensive data some of which are not even supported by Lucene directly.
- Both have ways to define and customize data schema and indexes.
- Both are distributed in nature and hence can handle scale easily.
- Both can provide near real-time search with high availability.

Solr and Elasticsearch are similar in many ways. They are abstractions built on top of Lucene that add enhanced search functionality, both Solr and Elasticsearch have been adapted for analytics use cases as well as enterprise search.
- Solr is an older technology and certainly still has many fans and an experienced community. If you judge by the size of the community, however, Elasticsearch overtook Solr a few years ago. 

- Solr started as a search engine on top of Lucene. Though it is still open source but it is embedded into a commercial product by Lucidworks which can provide enterprise search by connecting to various data sources.


## Conclusion 

Lucene is a full text indexing engine toolkit written in
Java, multi-user support access, quickly visit indexing
time and can cross-platform use. A simple way to conceptualize the relationship between Solr, Elasticsearch is that both are based on Apache Lucene. Similarly, Lucene is a programmatic library which you can't use as-is, whereas Solr and elesticsearch is a complete application which you can use out-of-box.

## Reference
- https://lucene.apache.org/core/
- https://www.knowi.com/blog/what-is-elastic-search/
- https://sematext.com/guides/solr/
- https://www.nextbrick.com/blog/differences-between-apache-solr-and-apache-lucene/
- https://medium.com/javarevisited/deep-dive-into-elastic-search-702e501762b
- https://medium.com/techshots/introduction-to-apache-solr-d3e734a5c346

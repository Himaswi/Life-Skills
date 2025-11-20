# Full Text Search: Investigation of Elasticsearch, Solr, and Lucene

## Introduction
Our project is currently facing performance and scaling issues, especially when handling search features. After a brief analysis, the team lead asked me to investigate whether using a specialized full-text search engine can improve performance. Full-text search engines are designed to handle large volumes of text, execute fast searches, and scale better than traditional relational databases. I explored three widely used technologies: Elasticsearch, Solr, and Lucene.

## Elasticsearch
Elasticsearch is a distributed search engine built on top of Lucene. It provides fast indexing, near real-time search, and horizontal scalability. It offers an easy-to-use REST API and supports complex queries at high speed. It is suitable for applications that need fast search across large datasets.

## Solr
Solr is an enterprise search platform built on top of Lucene. It offers powerful search capabilities, including filtering, faceting, and ranking. Solr offers robust configuration options and is well-suited for projects that require customized search logic. It is stable, mature, and widely used in large organizations.

## Lucene
Lucene is the underlying library used by both Elasticsearch and Solr. It provides low-level search features but requires more programming effort. Lucene is suitable when a project needs full control over search behavior or when building a custom search engine. It is fast and reliable, but requires more work compared to Elasticsearch and Solr.

## Conclusion
Based on this investigation, Elasticsearch is the best option for our project. It supports large-scale searches, provides easy integration, and offers strong performance. Solr is also a good choice if the team needs more control over configuration. Lucene is powerful but requires more development effort. Using any of these tools will likely improve search performance compared to normal database queries.

## References
* https://www.elastic.co/elasticsearch
* https://solr.apache.org/
* https://lucene.apache.org/

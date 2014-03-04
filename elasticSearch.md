Elastic Search
==========


### feature
- http://www.elasticsearch.org/guide/en/elasticsearch/reference/current/search-suggesters-completion.html
- http://www.elasticsearch.org/guide/en/elasticsearch/reference/current/search-suggesters.html - jednoduché použití pro autocomplete

### articles
- http://dev-blog.xoom.com/2013/12/01/natural-language-and-targeted-search-using-elastic-search/ - vyhledávání s tagy jmeno:Tomas deal:3434...
- http://nhhagen.wordpress.com/2013/11/28/query-log-analysis-using-logstash-elasticsearch-and-kibana/ - efektní dashboard s přehledem dat z elesticsearch logu
- http://found.no/foundation/similarity/ - vysvětlení jak lucene zachází se similarity
- http://www.elasticsearch.org/videos/big-data-search-and-analytics/ - přednáška o použití es s hodně daty
- http://blog.bugsense.com/post/35580279634/indexing-bigdata-with-elasticsearch - opět es s hodně daty, tady jsou zároveň i zmíněny změny nastavení es indexy
- http://www.slideshare.net/netconstructor/bigdata-f-apache-solr-vs-elasticsearch - porovnání Solr a lucene
- http://www.elasticsearch.org/blog/disk-based-field-data-a-k-a-doc-values/ - doc values aneb jak nechat data na disku ala couch a použit je jen pro analyzování
- http://www.elasticsearch.org/blog/disk-based-field-data-a-k-a-doc-values/ - tutorial na logstash, kibana a es
- http://blog.florian-hopf.de/2013/11/reindexing-content-in-elasticsearch.html - povídání o reindexaci
- http://dougmcclure.net/blog/2013/11/event-analysis-using-smartcloud-analytics-log-analysis-scala-v1103-deploying-logstash/ - opět tu  máme scalu a logstash
- http://www.elasticsearch.org/tutorials/2012/03/21/deploying-elasticsearch-with-chef-solo.html - instalace s chef
- http://www.ripariandata.com/blog/time-to-relax-installing-couchdb-and-elasticsearch - manuální instalace s couchdb
- fuzzy query - http://www.elasticsearch.org/guide/reference/query-dsl/fuzzy-query.html - vyhledává s určitou podobností/přesností
- http://www.elasticsearch.org/guide/reference/api/search/fields.html - formát dotazu a možnost navrátit pouze některé klíče
- http://stackoverflow.com/questions/13403900/elasticsearch-ignore-words-breakers?rq=1 - vlastní filtr - slug a řešení mapping
- http://www.elasticsearch.org/guide/reference/index-modules/analysis/lang-analyzer.html - podpora cz pro stopwords
- http://www.elasticsearch.org/guide/reference/mapping/conf-mappings.html - mapping in file
- http://stackoverflow.com/questions/7774285/search-couchdb-using-elasticsearch-river?rq=1 - základní vyhledávání při použití couchdb
- http://ufal.mff.cuni.cz/morfo/ - jiná implementace dobré češtiny a vyhledávání
- https://github.com/jprante/elasticsearch-analysis-hunspell - možnost vyhledávání českých znaků
- http://www.elasticsearch.org/guide/reference/api/admin-indices-analyze.html (http://d.n13.cz:9200/_analyze?analyzer=czech&text=vyv%C3%ADjet) - rozpis tokenizace slov
- https://github.com/rgrove/node-elastical/pull/14 - chybka s river, kter me provazi
- npm i https://github.com/rgrove/node-elastical/tarball/master -- instalace z dev

### pluginy
- https://github.com/vhyza/elasticsearch-analysis-lemmagen - od českého autora zajímavá implementace LemnaGen - vyhleádávní - převede slova z textu na základní tvary
- https://github.com/mobz/elasticsearch-head - přehled databází, dotazování, prohlížení dat
- https://github.com/OlegKunitsyn/elasticsearch-browser - prohlížení kolekcí a dat
- https://github.com/polyfractal/elasticsearch-inquisitor - přehled, statistiky, dotazy
- https://github.com/polyfractal/elasticsearch-inquisitor - live statistiky, grafy
- https://github.com/jprante/elasticsearch-analysis-hunspell - openoffice slovníky pro vyhledávání


### ejs
- http://www.fullscale.co/blog/2013/01/17/Tackling_Big_Data_with_elasticsearch.html - pár příkladů s ejs a reduce


### software
- http://sematext.com/search-analytics/ - služba poskytující grafy a nalitiku pro elasticsearch

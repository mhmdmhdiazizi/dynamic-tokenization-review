# Sources

## 1. Google Scholar

Address: scholar.google.com

Date : August, 17, 2025

Range: 2017-2026

Results: Top 200 articles per query.

Notes: 
- multiple shorter queries because of the 256 chard limitation of Google Scholar
- Publish or Perish utilized to export the results:
*Harzing, A.W. (2007) Publish or Perish, available from https://harzing.com/resources/publish-or-perish*
- Citations and patents were not included in search
- Detailed log: 'search_log/googlescholar/'


### Queries:

```
("dynamic*" OR "adaptive" OR "flexible" OR "dependent") AND ("token*" OR "patch*" OR "embedding*" OR "chunk*") AND ("sequence model*" OR "large * model*" OR "Transformer" OR "foundation* model*") AND ("language" OR "text*" OR "linguistic" OR "NLP" OR "word*" OR "character*" OR "byte*")

("tokenization-free" OR "compress* token*" OR "compress* for token*") AND ("sequence model*" OR "large * model*" OR "Transformer" OR "foundation* model*") AND ("language" OR "text*" OR "linguistic" OR "NLP" OR "word*" OR "character*" OR "byte*")

("dynamic*" OR "adaptive" OR "flexible" OR "dependent") AND ("token*" OR "patch*" OR "embedding*" OR "chunk*") AND ("sequence model*" OR "large * model*" OR "Transformer" OR "foundation* model*") AND ("vision" OR "image*" OR "video" OR "visual" OR "spatio*")

("tokenization-free" OR "compress* token*" OR "compress* for token*") AND ("sequence model*" OR "large * model*" OR "Transformer" OR "foundation* model*") AND ("vision" OR "image*" OR "video" OR "visual" OR "spatio*")

("dynamic*" OR "adaptive" OR "flexible" OR "dependent") AND ("token*" OR "patch*" OR "embedding*" OR "chunk*") AND ("sequence model*" OR "large * model*" OR "Transformer" OR "foundation* model*") AND ("time*" OR "temporal*" OR "signal" OR "electro*gra*" OR "bio*al" OR "sensor*")

("tokenization-free" OR "compress* token*" OR "compress* for token*") AND ("sequence model*" OR "large * model*" OR "Transformer" OR "foundation* model*") AND ("time*" OR "temporal*" OR "signal" OR "electro*gra*" OR "bio*al" OR "sensor*")

("dynamic*" OR "adaptive" OR "flexible" OR "dependent") AND ("token*" OR "patch*" OR "embedding*" OR "chunk*") AND ("sequence model*" OR "large * model*" OR "Transformer" OR "foundation* model*") AND ("sequence" OR "audio" OR "speech" OR "acoustic*" OR "music*")

("tokenization-free" OR "compress* token*" OR "compress* for token*") AND ("sequence model*" OR "large * model*" OR "Transformer" OR "foundation* model*") AND ("sequence" OR "audio" OR "speech" OR "acoustic*" OR "music*")

```

## 2. ACM Digital Library

Address: dl.acm.org

Search date: August, 17, 2025

Results: 230

Range: From Jan, 2017

Notes: 
- Search items from: The ACM Guide to Computing Literature
- Search for cell neural network and attention for more simple queries.
- Search within: title and abstract.
- Search results: 'search_log/acm/'

### Queries:

Raw query:

```
((("dynamic*" OR "adaptive" OR "flexible" OR "dependent") AND ("token*" OR "patch*" OR "embedding*" OR "chunk*")) OR "tokenization-free" OR "compress* token*" OR "compress* for token*") AND ("sequence model*" OR "large * model*" OR "Transformer" OR "foundation* model*") AND ("language" OR "text*" OR "linguistic" OR "NLP" OR "word*" OR "character*" OR "byte*" OR "vision" OR "image*" OR "video" OR "visual" OR "spatio*" OR "time*" OR "temporal*" OR "signal" OR "electro*gra*" OR "bio*al" OR "sensor*" OR "sequence" OR "audio" OR "speech" OR "acoustic*" OR "music*")

```

Search query:

```
Title:(((("dynamic*" OR "adaptive" OR "flexible" OR "dependent") AND ("token*" OR "patch*" OR "embedding*" OR "chunk*")) OR "tokenization-free" OR "compress* token*" OR "compress* for token*") AND ("sequence model*" OR "large * model*" OR "Transformer" OR "foundation* model*") AND ("language" OR "text*" OR "linguistic" OR "NLP" OR "word*" OR "character*" OR "byte*" OR "vision" OR "image*" OR "video" OR "visual" OR "spatio*" OR "time*" OR "temporal*" OR "signal" OR "electro*gra*" OR "bio*al" OR "sensor*" OR "sequence" OR "audio" OR "speech" OR "acoustic*" OR "music*")) OR Abstract:(((("dynamic*" OR "adaptive" OR "flexible" OR "dependent") AND ("token*" OR "patch*" OR "embedding*" OR "chunk*")) OR "tokenization-free" OR "compress* token*" OR "compress* for token*") AND ("sequence model*" OR "large * model*" OR "Transformer" OR "foundation* model*") AND ("language" OR "text*" OR "linguistic" OR "NLP" OR "word*" OR "character*" OR "byte*" OR "vision" OR "image*" OR "video" OR "visual" OR "spatio*" OR "time*" OR "temporal*" OR "signal" OR "electro*gra*" OR "bio*al" OR "sensor*" OR "sequence" OR "audio" OR "speech" OR "acoustic*" OR "music*"))
```

Resulted query:

```
[[[[[Title: "dynamic*"] OR [Title: "adaptive"] OR [Title: "flexible"] OR [Title: "dependent"]] AND [[Title: "token*"] OR [Title: "patch*"] OR [Title: "embedding*"] OR [Title: "chunk*"]]] OR [Title: "tokenization-free"] OR [Title: "compress* token*"] OR [Title: "compress* for token*"]] AND [[Title: "sequence model*"] OR [Title: "large * model*"] OR [Title: "transformer"] OR [Title: "foundation* model*"]] AND [[Title: "language"] OR [Title: "text*"] OR [Title: "linguistic"] OR [Title: "nlp"] OR [Title: "word*"] OR [Title: "character*"] OR [Title: "byte*"] OR [Title: "vision"] OR [Title: "image*"] OR [Title: "video"] OR [Title: "visual"] OR [Title: "spatio*"] OR [Title: "time*"] OR [Title: "temporal*"] OR [Title: "signal"] OR [Title: "electro*gra*"] OR [Title: "bio*al"] OR [Title: "sensor*"] OR [Title: "sequence"] OR [Title: "audio"] OR [Title: "speech"] OR [Title: "acoustic*"] OR [Title: "music*"]]] OR [[[[[Abstract: "dynamic*"] OR [Abstract: "adaptive"] OR [Abstract: "flexible"] OR [Abstract: "dependent"]] AND [[Abstract: "token*"] OR [Abstract: "patch*"] OR [Abstract: "embedding*"] OR [Abstract: "chunk*"]]] OR [Abstract: "tokenization-free"] OR [Abstract: "compress* token*"] OR [Abstract: "compress* for token*"]] AND [[Abstract: "sequence model*"] OR [Abstract: "large * model*"] OR [Abstract: "transformer"] OR [Abstract: "foundation* model*"]] AND [[Abstract: "language"] OR [Abstract: "text*"] OR [Abstract: "linguistic"] OR [Abstract: "nlp"] OR [Abstract: "word*"] OR [Abstract: "character*"] OR [Abstract: "byte*"] OR [Abstract: "vision"] OR [Abstract: "image*"] OR [Abstract: "video"] OR [Abstract: "visual"] OR [Abstract: "spatio*"] OR [Abstract: "time*"] OR [Abstract: "temporal*"] OR [Abstract: "signal"] OR [Abstract: "electro*gra*"] OR [Abstract: "bio*al"] OR [Abstract: "sensor*"] OR [Abstract: "sequence"] OR [Abstract: "audio"] OR [Abstract: "speech"] OR [Abstract: "acoustic*"] OR [Abstract: "music*"]]] AND [E-Publication Date: (01/01/2017 TO *)]
```


## 3. PubMed

Address: pubmed.ncbi.nlm.nih.gov

Search date: August, 17, 2025

Results: 321

Range: From 2017/01/01

Notes:
- Search results: 'search_log/pubmed/'

### Queries:

Search query:

```
(("dynamic*"[Title/Abstract] OR "adaptive"[Title/Abstract] OR "flexible"[Title/Abstract] OR "dependent"[Title/Abstract]) AND ("token*"[Title/Abstract] OR "patch*"[Title/Abstract] OR "embedding*"[Title/Abstract] OR "chunk*"[Title/Abstract]) OR "tokenization-free"[Title/Abstract] OR "compress* token*"[Title/Abstract] OR "compress* for token*"[Title/Abstract]) AND ("sequence model*"[Title/Abstract] OR "large * model*"[Title/Abstract] OR "Transformer"[Title/Abstract] OR "foundation* model*"[Title/Abstract]) AND ("language"[Title/Abstract] OR "text*"[Title/Abstract] OR "linguistic"[Title/Abstract] OR "NLP"[Title/Abstract] OR "word*"[Title/Abstract] OR "character*"[Title/Abstract] OR "byte*"[Title/Abstract] OR "vision"[Title/Abstract] OR "image*"[Title/Abstract] OR "video"[Title/Abstract] OR "visual"[Title/Abstract] OR "spatio*"[Title/Abstract] OR "time*"[Title/Abstract] OR "temporal*"[Title/Abstract] OR "signal"[Title/Abstract] OR "electro*gra*"[Title/Abstract] OR " biosignal"[Title/Abstract] OR "sensor*"[Title/Abstract] OR "sequence"[Title/Abstract] OR "audio"[Title/Abstract] OR "speech"[Title/Abstract] OR "acoustic*"[Title/Abstract] OR "music*"[Title/Abstract])

```

## 4. IEEE Explore

Address: ieeexplore.ieee.org

Search date: August, 17, 2025

Results: 687 + 17 + 443 + 5

Range: 2017-

Notes: 
- Because of the 25 cards and 10 wild card limitation the search conducted in five groups.
- Search results: 'search_log/ieee/'

### Queries:

Search queries:

```
(("Abstract":"dynamic*" OR "Abstract":"adaptive" OR "Abstract":"flexible" OR "Abstract":"dependent") AND ("Abstract":"token*" OR "Abstract":"patch*" OR "Abstract":"embedding*" OR "Abstract":"chunk*")) AND ("Abstract":"sequence model*" OR "Abstract":"large language model" OR "Abstract":"Transformer" OR "Abstract":"foundation model*") AND ("Abstract":"language" OR "Abstract":"text" OR "Abstract":"linguistic" OR "Abstract":"NLP" OR "Abstract":"word*" OR "Abstract":"character*" OR "Abstract":"byte" OR "Abstract":"vision" OR "Abstract":"image" OR "Abstract":"video" OR "Abstract":"visual" OR "Abstract":"spatio*")

(("Document Title":"dynamic*" OR "Document Title":"adaptive" OR "Document Title":"flexible" OR "Document Title":"dependent") AND ("Document Title":"token*" OR "Document Title":"patch*" OR "Document Title":"embedding*" OR "Document Title":"chunk*")) AND ("Document Title":"sequence model*" OR "Document Title":"large language model" OR "Document Title":"Transformer" OR "Document Title":"foundation model*") AND ("Document Title":"language" OR "Document Title":"text" OR "Document Title":"linguistic" OR "Document Title":"NLP" OR "Document Title":"word*" OR "Document Title":"character*" OR "Document Title":"byte" OR "Document Title":"vision" OR "Document Title":"image" OR "Document Title":"video" OR "Document Title":"visual" OR "Document Title":"spatio*")

(("Abstract":"dynamic*" OR "Abstract":"adaptive" OR "Abstract":"flexible" OR "Abstract":"dependent") AND ("Abstract":"token*" OR "Abstract":"patch*" OR "Abstract":"embedding*" OR "Abstract":"chunk*")) AND ("Abstract":"sequence model*" OR "Abstract":"large languge model" OR "Abstract":"Transformer" OR "Abstract":"foundation model*") AND ("Abstract":"time" OR "Abstract":"temporal" OR "Abstract":"signal" OR "Abstract":"electro*" OR "Abstract":"biosignal" OR "Abstract":"sensor*" OR "Abstract":"sequence" OR "Abstract":"audio" OR "Abstract":"speech" OR "Abstract":"acoustic" OR "Abstract":"music")

(("Document Title":"dynamic*" OR "Document Title":"adaptive" OR "Document Title":"flexible" OR "Document Title":"dependent") AND ("Document Title":"token*" OR "Document Title":"patch*" OR "Document Title":"embedding*" OR "Document Title":"chunk*")) AND ("Document Title":"sequence model*" OR "Document Title":"large language model" OR "Document Title":"Transformer" OR "Document Title":"foundation model*") AND ("Document Title":"time" OR "Document Title":"temporal" OR "Document Title":"signal" OR "Document Title":"electro*" OR "Document Title":"biosigal" OR "Document Title":"sensor*" OR "Document Title":"sequence" OR "Document Title":"audio" OR "Document Title":"speech" OR "Document Title":"acoustic" OR "Document Title":"music")
```

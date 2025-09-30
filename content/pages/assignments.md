---
content_type: page
description: The assignments section contains 6 homework files and 24 supporting .txt,
  .gz, and .tar files for the homework files.
hide_download: true
hide_download_original: null
learning_resource_types:
- Assignments
ocw_type: CourseSection
title: Assignments
uid: 48a8a6b4-bb3a-c5c6-9c7c-63540f644c1f
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
ASSIGNMENTS
{{< thclose >}}
{{< thopen >}}
SUPPORTING FILES
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
Homework 1 ({{% resource_link b6328289-5297-b539-dbad-9d03be88c0de "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Homework 2 ({{% resource_link 4ff230d8-df38-8931-d7b2-b7bf3ff73301 "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
counts.gz ({{% resource_link 3dfc0800-3133-f5b5-847b-4301d966289e "GZ - 3.2 MB" %}}) (The GZ file contains: counts.txt.)  
theirthere.test ({{% resource_link f9b0c1dd-bc59-23ae-e149-d8871296e2b9 "TXT" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Homework 3 ({{% resource_link c194dabd-a13c-61b9-d854-d1e431847bb0 "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
data.gz ({{% resource_link 96fb05ef-f0fb-1e1c-b91f-f342ae388d56 "GZ" %}}) (The GZ file contains: data.txt.)  
synrev ({{% resource_link 164f70e9-8cb3-138c-bdaa-03fbbbd4b064 "TXT" %}})  
  
_Development Data_  
  
Verb pairs and associated cosine similarity scores (note that sim.in = synrev).  
sim.in ({{% resource_link 1d7318ef-f408-3ae8-951d-918b965fd5dc "TXT" %}})  
sim.out ({{% resource_link efc7d4c2-95ee-7909-01f8-5f9a7d60f019 "TXT" %}})  
  
Result of complete-link clustering to the 2-cluster level.  
cluster1 ({{% resource_link 79461f79-6f5c-91c1-22c2-453de2fe5a9d "TXT" %}})  
cluster2 ({{% resource_link bd6833d0-6f73-85b8-15a8-e18ada21bc7a "TXT" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Homework 4 ({{% resource_link bcd3c33c-cafa-a579-035f-1c77c1212380 "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
poscounts.gz ({{% resource_link 9e4a5160-969f-a5ef-c6b2-2c17ee35f924 "GZ" %}}) (The GZ file contains: poscounts.txt.)  
wsj.19-21.test ({{% resource_link b8387031-571c-1f6d-f7bc-8d495bf9f40f "TXT" %}})  
  
_Extra Materials_  
  
A package containing the scripts that were used to generate the poscounts.gz corpus. We are providing this code in case you are curious about the data generation. For the purposes of the problem set, however, please use the poscounts.gz training corpus to ensure that your results comply with the reference implementation.  
ft.tar.tar ({{% resource_link 423ee415-75ea-fa67-d604-b89562567976 "TAR - 2.5 MB" %}})  
  
Development data for testing your tag-trigram probabilities; tritest contains tag trigrams, while tritest.probs contains the corresponding probabilities.  
tritest ({{% resource_link ecf4dbba-b46e-20cd-791f-93a3bf1b8e6c "TXT" %}})  
tritest.probs ({{% resource_link 4b45f500-f7f9-4df7-4e4c-49859e37844e "TXT" %}})  
  
Development data for testing your Viterbi tag assignments. The simplesents file contains about 530 simple sentences that admit relatively few possible tag assignments. The simplesents.bf\_tagged file contains optimal tag assignments and log-probabilities as discovered by brute-force enumeration. The first element in every line of simplesents.bf\_tagged gives the log-probability of the best tagging, and the rest of the line gives the tag assignment itself.  
simplesents ({{% resource_link 69f12382-4afa-6f4d-5bc7-6a91b95362d8 "TXT" %}})  
simplesents.bf\_tagged ({{% resource_link becd5baa-a6fe-adb0-1b27-4c9abbd97ebd "TXT" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Homework 5 ({{% resource_link 76e629e7-2732-d5b1-3187-8d0d4f56ea85 "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
_Resources_  
  
[BoosTexter](http://rob.schapire.net/) - The download page for the BoosTexter binaries. If you get an error message, try reloading the link. BoosTexter is UNIX®-based, so if you want to run it in Windows, you will need to get a UNIX® shell such as [Cygwin](http://www.cygwin.com/) or [U/Win](http://www.research.att.com/sw/tools/uwin).  
  
[Penn Treebank Tagset](https://www.ling.upenn.edu/courses/Fall_2003/ling001/penn_treebank_pos.html) - Descriptions of the Penn part-of-speech tags. NB: When you are determining the plurality of a noun phrase, you will find that the last tag is not always a noun-type tag. Use the following rule to determine the plurality of these other parts of speech:  
Plural: CD, JJP, SYM  
Singular: DT, JJ, RB, VBG, WDT  
  
_Datasets_  
  
Sentence pairs with coreference annotations.  
coref\_samples.train ({{% resource_link 2c0612f4-c6b3-b071-66cd-7ea3476f471a "TXT" %}})  
coref\_samples.test ({{% resource_link b137dd0c-1b73-e3ef-1844-c36d887c694d "TXT" %}})  
  
BoosTexter .names template for feature generation. Please adhere to this template to ensure that your features conform to the reference results.  
coref.names ({{% resource_link 1e51155c-7d37-8737-60e3-d7689f6d4d42 "TXT" %}})  
  
Reference features for the first 30 sentence pairs in coref\_samples.train. The feature vectors were generated in a left-to-right postorder traversal of the noun phrases in a given sentence pair; e.g.  
\[\[ \[\[ 1 \]\] 2 \]\] \[\[ 3 \]\] \[\[ 4 \]\] \[\[ \[\[ 5 \]\] \[\[ \[\[ 6 \]\] 7 \]\] 8 \]\]  
first30.data ({{% resource_link 932ac531-255a-aa57-c1f7-71df1b4f2e7c "TXT" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Homework 6 ({{% resource_link e71a9d7c-4fdc-8efa-76e6-131fc7d6642c "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
corpus.de.gz ({{% resource_link e549b14f-589a-1d81-9bb9-d6838ec5c5b9 "GZ" %}}) (The GZ file contains: corpus.de.txt.)  
corpus.en.gz ({{% resource_link 8bdbfba4-7966-3a71-a610-7bf823f73629 "GZ" %}}) (The GZ file contains: corpus.en.txt.)  
  
_Datasets_  
  
A set of words and their associated translation probabilities. The output file is formatted as a series of lines, where each line contains a number of (German word, translation probability) pairs, all tokens separated by spaces.  
devwords ({{% resource_link 4a6ea3e7-00ec-76a4-a9bd-03256e842850 "TXT" %}})  
devwords.out ({{% resource_link 0706b103-f5dc-f29e-4127-da764cb360b2 "TXT" %}})  
  
A set of words for which you must provide output probabilities. Please provide a file testwords.out with the same format as devwords.out above.  
testwords ({{% resource_link 4e727ea0-8221-2fee-fae6-e1e5cfc0c257 "TXT" %}})
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}
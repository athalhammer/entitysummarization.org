[Research](./index)

[Systems](./systems)

___
Entity summarization is the problem of identifying a limited number of ordered RDF triples that summarize an entity in the best way—the result is typically presented in knowledge panels.

___


## LinkSUM - Awesome!
Currently, LinkSUM and the WDAqua SummaServer are the only entity summarization systems freely available:

* <https://km.aifb.kit.edu/services/link/>
* <https://km.aifb.kit.edu/services/summaServer/> (SUMMA API reference implementation, source code <https://github.com/athalhammer/summaServer>)

This boils down to the following **endpoints**:
* DBpedia - <https://km.aifb.kit.edu/services/link/sum>
* DBpedia - <https://km.aifb.kit.edu/services/summaServer/sum>
All of these endpoints comply to the SUMMA API and can be consumed with the summaClient implementation:

**Demos**: 
* <https://athalhammer.github.io/summaClient/>

(source code: <https://github.com/athalhammer/summaClient>)

A demo which combines the DBpedia Spotlight entity linking and LinkSUM entity summarization can be found here:
* <https://athalhammer.github.io/ELES/> (source code: <https://github.com/athalhammer/ELES>)

**Dataset**
Wikidata PageRank <https://danker.s3.amazonaws.com/index.html>

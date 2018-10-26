# CrowdTruth ground truth for Open Domain Relation Extraction

Crowdsourced ground truth dataset for 4,100 sentences and 16 relations from the open domain. The corpus has been referenced in the following papers:

* Anca Dumitrache, Lora Aroyo and Chris Welty: **[ Crowdsourcing Semantic Label Propagation in Relation Classification](https://arxiv.org/abs/1809.00537)**. [FEVER](http://fever.ai/) Workshop at [EMNLP 2018](http://emnlp2018.org/) (in publication).
* Anca Dumitrache, Lora Aroyo and Chris Welty: **[False Positive and Cross-relation Signals in Distant Supervision Data](https://arxiv.org/abs/1711.05186)**. [AKBC](http://www.akbc.ws/) Workshop at [NIPS 2017](http://nips.cc/).
* Anca Dumitrache, Lora Aroyo and Chris Welty: **[Disagreement in Crowdsourcing and Active Learning for Better Distant Supervision Quality](http://crowdtruth.org/wp-content/uploads/2017/03/collint17-open-domain.pdf)**. [Collective Intelligence 2017](http://collectiveintelligenceconference.org/).

Sentence-level data is available in file:
``` |--data/output/aggregated_sentences.csv ``` 

Worker-level data is available in file:
``` |--data/output/aggregated_workers.csv ``` 

Raw crowdsourcig data is available in folder:
``` |--data/input/ ```

Results of the relation classification model are available in folder:
``` |--data/model_results/ ```

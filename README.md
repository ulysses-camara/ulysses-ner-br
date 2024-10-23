# UlyssesNER-Br
Repository for PT-br Legal Named Entity Recognition (NER) resources.

Spreadsheet containing the results of NER models trained with the datasets: https://docs.google.com/spreadsheets/d/1uygceS1sOaSLkBWRXzevWAcWoCNWUbv8-nppoisOXio/

---

## Related papers:
### UlyssesNER-Br (PL-corpus and ST-corpus)

- [UlyssesNER-Br: A Corpus of Brazilian Legislative Documents for Named Entity Recognition](https://doi.org/10.1007/978-3-030-98305-5_1)
```bibtex
@InProceedings{10.1007/978-3-030-98305-5_1,
author="Albuquerque, Hidelberg O.
and Costa, Rosimeire
and Silvestre, Gabriel
and Souza, Ellen
and da Silva, N{\'a}dia F. F.
and Vit{\'o}rio, Douglas
and Moriyama, Gyovana
and Martins, Lucas
and Soezima, Luiza
and Nunes, Augusto
and Siqueira, Felipe
and Tarrega, Jo{\~a}o P.
and Beinotti, Joao V.
and Dias, Marcio
and Silva, Matheus
and Gardini, Miguel
and Silva, Vinicius
and de Carvalho, Andr{\'e} C. P. L. F.
and Oliveira, Adriano L. I.",
editor="Pinheiro, Vl{\'a}dia
and Gamallo, Pablo
and Amaro, Raquel
and Scarton, Carolina
and Batista, Fernando
and Silva, Diego
and Magro, Catarina
and Pinto, Hugo",
title="UlyssesNER-Br: A Corpus of Brazilian Legislative Documents for Named Entity Recognition",
booktitle="Computational Processing of the Portuguese Language",
year="2022",
publisher="Springer International Publishing",
address="Cham",
pages="3--14",
abstract="The amount of legislative documents produced within the past decade has risen dramatically, making it difficult for law practitioners to consult and update legislation. Named Entity Recognition (NER) systems have the untapped potential to extract information from legal documents, which can improve information retrieval and decision-making processes. We introduce the UlyssesNER-Br, a corpus of Brazilian Legislative Documents for NER with quality baselines. The presented corpus consists of bills and legislative consultations from Brazilian Chamber of Deputies. We implemented Conditional Random Field (CRF) and Hidden Markov Model (HMM) models, and the promising F1-score of 80.8{\%} in the analysis by categories and 81.04{\%} in the analysis by types, was achieved with the CRF model. The entities with the best average F1-score results were ``FUNDlei'' and ``DATA'', and the ones with the worst results were ``EVENTO'' and ``PESSOAgrupoind''. The corpus was also evaluated using a BiLSTM-CRF and Glove architectures provided by the pioneering state-of-the-art paper, achieving F1-score of 76.89{\%} in the analysis by categories and 59.67{\%} in the analysis by types.",
isbn="978-3-030-98305-5"
}
```
### UlyssesNER-Br (C-corpus)
- [Expanding UlyssesNER-Br Named Entity Recognition Corpus with Informal User-Generated Text](https://link.springer.com/chapter/10.1007/978-3-031-16474-3_62)
```bibtex
@InProceedings{10.1007/978-3-031-16474-3_62,
author="Costa, Rosimeire
and Albuquerque, Hidelberg Oliveira
and Silvestre, Gabriel
and Silva, N{\'a}dia F{\'e}lix F.
and Souza, Ellen
and Vit{\'o}rio, Douglas
and Nunes, Augusto
and Siqueira, Felipe
and Pedro Tarrega, Jo{\~a}o
and Vitor Beinotti, Jo{\~a}o
and de Souza Dias, M{\'a}rcio
and Pereira, Fab{\'i}ola S. F.
and Silva, Matheus
and Gardini, Miguel
and Silva, Vinicius
and de Carvalho, Andr{\'e} C. P. L. F.
and Oliveira, Adriano L. I.",
editor="Marreiros, Goreti
and Martins, Bruno
and Paiva, Ana
and Ribeiro, Bernardete
and Sardinha, Alberto",
title="Expanding UlyssesNER-Br Named Entity Recognition Corpus with Informal User-Generated Text",
booktitle="Progress in Artificial Intelligence",
year="2022",
publisher="Springer International Publishing",
address="Cham",
pages="767--779",
abstract="Named Entity Recognition (NER) is a challenging Natural Language Processing task for a language as rich as Portuguese. When applied in a scenario appropriate to informal language and short texts, the task acquires a new layer of complexity, handling a particular lexicon to the domain in question. In this paper, we expanded the UlyssesNER-Br corpus for NER task with Brazilian Portuguese comments about bills. Additionally, we enriched the annotated set with a formal corpora, in order to analyze whether the combination of formal and informal texts from the same domain could improve NER. Finally, we carry out experiments with a Conditional Random Fields (CRF) model, a Bidirectional LSTM-CRF (BiLSTM-CRF) model, and subsequently, we realized fine-tuning of a language model BERT on NER task with our dataset. We concluded that formal texts helped identification of entities in informal texts. The best model was the fine-tuned BERT which achieved an F1-score of 73.90{\%}, beating the benchmark of related works.",
isbn="978-3-031-16474-3"
}
```
``` bibtex
@mastersthesis{costa2023reconhecimento,
  title={Reconhecimento de entidades nomeadas em textos informais no dom{\'\i}nio legislativo},
  author={Costa, Rosimeire Pereira da, and and da Silva, N{\'a}dia F. F.},
  year={2023},
  school={Master’s thesis, Universidade Federal de Goi{\'a}s},
  url={http://repositorio.bc.ufg.br/tede/handle/tede/12862}
}
```
### UlyssesNER-Br (PL-corpus v2)
The updated version of the PL-corpus was used by Rafael O. Nunes, Dennis G. Balreira, Andre S. Spritzer and Carla Maria D.S. Freitas, all by Federal University of Rio Grande do Sul (UFRGS).
The full works is available in:
- ["A Named Entity Recognition Approach for Portuguese Legislative Texts Using Self-Learning", PROPOR (2024)](https://aclanthology.org/2024.propor-1.30/)
- ["Out of Sesame Street: A Study of Portuguese Legal Named Entity Recognition Through In-Context Learning", ICEIS (2024)](https://doi.org/10.5220/0012624700003690)
- ["Named Entity Recognition and Data Leakage in Legislative Texts: A Literature Reassessment" Linguamática (2024), *Under review - Preprint](http://dx.doi.org/10.13140/RG.2.2.25781.69602)

We thank the UFRGS collaborators for their kindness and collaboration. 
This interaction is essential for to continue improving the quality and accuracy of our research, and Science as a whole. We remain available for future joint research efforts.

``` bibtex
@inproceedings{nunes-etal-2024-named,
    title = "A Named Entity Recognition Approach for {P}ortuguese Legislative Texts Using Self-Learning",
    author = "Nunes, Rafael Oleques  and
      Balreira, Dennis Giovani  and
      Spritzer, Andr{\'e} Suslik  and
      Freitas, Carla Maria Dal Sasso",
    editor = "Gamallo, Pablo  and
      Claro, Daniela  and
      Teixeira, Ant{\'o}nio  and
      Real, Livy  and
      Garcia, Marcos  and
      Oliveira, Hugo Gon{\c{c}}alo  and
      Amaro, Raquel",
    booktitle = "Proceedings of the 16th International Conference on Computational Processing of Portuguese - Vol. 1",
    month = mar,
    year = "2024",
    address = "Santiago de Compostela, Galicia/Spain",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.propor-1.30",
    pages = "290--300",
}
```
``` bibtex
@conference{iceis24,
author={Rafael {Oleques Nunes}. and Andre Spritzer. and Carla {Dal Sasso Freitas}. and Dennis Balreira.},
title={Out of Sesame Street: A Study of Portuguese Legal Named Entity Recognition Through In-Context Learning},
booktitle={Proceedings of the 26th International Conference on Enterprise Information Systems - Volume 1: ICEIS},
year={2024},
pages={477-489},
publisher={SciTePress},
organization={INSTICC},
doi={10.5220/0012624700003690},
isbn={978-989-758-692-7},
issn={2184-4992},
}
```
``` bibtex
@inproceedings{nunes2024ulyssesner,
  title = "Reconhecimento de Entidades Nomeadas e Vazamento de Dados em Textos Legislativos: Uma Reavaliação da Literatura",
  author = "Nunes, Rafael Oleques  and
      Balreira, Dennis Giovani  and
      Spritzer, Andre Suslik  and
      Freitas, Carla Maria Dal Sasso",
  year = {2024},
  pages = {},
  title = {Named Entity Recognition and Data Leakage in Legislative Texts: A Literature Reassessment},
  url={http://dx.doi.org/10.13140/RG.2.2.25781.69602},
}```

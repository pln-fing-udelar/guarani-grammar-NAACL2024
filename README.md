# Grammar-based Data Augmentation for Low-Resource Languages - NAACL2024
This repository contains information about the code and resources used in the *Grammar-based Data Augmentation for Low-Resource Languages: The Case of Guarani-Spanish Neural Machine Translation* paper, accepted at NAACL2024.

✨**TL;DR**✨ In this work we explore the feasability of using grammar-generated text as a Data Augmentation strategy for low-resource languages, and we find that synthetic text is useful to boost Guarani-Spanish Machine Translation systems.

Authors:
- [Agustín Lucas](https://www.researchgate.net/profile/Agustin-Lucas-2)
- [Alexis Baladón](https://www.researchgate.net/profile/Alexis-Baladon)
- Victoria Pardiñas
- [Marvin Agüero-Torales](https://scholar.google.com/citations?user=JqrU3FUAAAAJ)
- [Santiago Góngora](https://scholar.google.com/citations?user=p1lKpmYAAAAJ)
- [Luis Chiruzzo](https://scholar.google.com/citations?user=C7c4uCsAAAAJ)

## Related resources

The work presented in this paper was part of an undergraduate thesis, named ["Generación de datos sintéticos para traducción automática entre español y guaraní"](https://hdl.handle.net/20.500.12008/42425) (*Synthetic Data Generation for Spanish-Guarani Machine Translation*).

### Grammars for Spanish and Guarani

One of the main components of this work is the development of a Feature Grammar to model simple Spanish-Guarani sentence pairs. The code for the grammar and the resources needed to run can be found [in this repository](https://github.com/baladon-lucas-pardinas/SyntaxGrammar-es-gn).

### NMT experiments using MarianNMT (C++)

The experiments were carried out using MarianNMT. You can find the [code here](https://github.com/baladon-lucas-pardinas/NMT-Translation-gn-es).

### Jojajovai corpus

To fine-tune and test the models we use the [Jojajovai parallel corpus](https://aclanthology.org/2022.lrec-1.226/), consisting of 8 subsets with different kinds of text (e.g. journalistic, user interfaces).

## Paper

Published paper (ACL Anthology): https://aclanthology.org/2024.naacl-long.354/

## Citation

If you use some part of this work in your research, please cite:

Agustín Lucas, Alexis Baladón, Victoria Pardiñas, Marvin Agüero-Torales, Santiago Góngora, and Luis Chiruzzo. 2024. Grammar-based Data Augmentation for Low-Resource Languages: The Case of Guarani-Spanish Neural Machine Translation. In Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 1: Long Papers), pages 6385–6397, Mexico City, Mexico. Association for Computational Linguistics.


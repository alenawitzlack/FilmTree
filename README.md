**FilmTree: A parallel corpus of film subtitles**

This corpus extends the ParTree corpus developed by Ebert et al. (2023), which, in turn, builds on the ParTy corpus by Levshina (2016). 
We selected subtitles for two movies, ‘Bridge of Spies’ and ‘The Godfather’, and performed a fully manual alignment in order to improve cross-linguistic correspondences between translations. 
The resulting corpus consists of 53 languages from 13 language families: 92 texts in total for two films. 
Of these, 68 texts were taken directly from ParTree, while 24 have been added from other sources. 
42 languages with available models were further automatically annotated following the Universal Dependencies (UD) framework (v2.17; Zeman et al., 2025) using UDPipe2 (Straka, 2018).

The corpus files are organised into three folders, following the structure implemented in the ParTree corpus. 
The raw folder contains the original subtitle files in the ._SRT_ format. 
The text folder contains files that have been converted to the ._TXT_ format, their text aligned and lines numbered. 
The conllu folder contains the files in the ._CONLLU_ format that have been annotated with Universal Dependencies. 
Inside each folder, the files are organised into subfolders by movie title.

For each movie text file, the file name includes the movie title, the ISO 639-3 language code1, and the language Glottocode, e.g. _Godfather_eng_stan1293_. 
The corresponding annotated .CONLLU filename additionally includes the UDPipe model identifier after the Glottocode, e.g. _Godfather_eng_stan1293_english-ewt_.

_____________

Ebert, C., N. Levshina & P. Widmer. 2023. Partree – parallel treebanks: A multilingual corpus of movie
subtitles (version 1.0.0) [data set]. _Tech. rep. LaRS - Language Repository of Switzerland._ https://doi.org/10.48656/5mz4-x435.

Levshina, Natalia. 2016. Verbs of letting in Germanic and Romance: A quantitative investigation based on
a parallel corpus of film subtitles. _Languages in Contrast 16(1)_. 84–117. https://doi.org/10.1075/lic.16.1.04lev.

Straka, Milan. 2018. UDPipe 2.0 prototype at CoNLL 2018 UD shared task. 
In _Proceedings of the CoNLL 2018 shared task: Multilingual parsing from raw text to universal dependencies_, 197–207. Brussels, Belgium: Association for Computational Linguistics. 
doi:10.18653/v1/K18-2020. https://www.aclweb.org/anthology/K18-2020.

Zeman, Daniel et al. 2025. Universal dependencies 2.17. _LINDAT/CLARIAH-CZ digital library at the
Institute of Formal and Applied Linguistics (ÚFAL)_. http://hdl.handle.net/11234/1-6036.

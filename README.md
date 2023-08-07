# SD-W2
A collection of SD-W2 pretrained models
UNDER CONSTRUCTION


Pretrained model:
Wikipedia Corpus (ukwac), Window Size 2

https://figshare.com/ndownloader/files/39146411

to use the Pretrained Model launch sse.jar via command line
general commands:
- load a model: "load MODEL_NAME"
- get similarities between two words: "gs WORD1 WORD2 [MEASURE]"
- get neighbors of a word: "gn WORD [NUMBER][MEASURE]"


Please cite the paper:
Maisto, Alessandro. "Extract Similarities from Syntactic Contexts: a Distributional Semantic Model Based on Syntactic Distance." Italian Journal of Computational Linguistics vol. 8, n. 2 december 2022 8 (2022): 63.


Bibtex
@article{maisto2022extract,
  title={Extract Similarities from Syntactic Contexts: a Distributional Semantic Model Based on Syntactic Distance},
  author={Maisto, Alessandro},
  journal={Italian Journal of Computational Linguistics vol. 8, n. 2 december 2022},
  volume={8},
  pages={63},
  year={2022}
}


# DoMa
The DoMa project include a set of domain specific matrices for Italian Language. Matrices were provided with a simple User Interface which helps to extract similarities, neighbors or word vectors from one or more matrices using different similarity measures. DoMa uses sse.jar in order to read the matrices and needs Java to work.
download the zip file at:

https://figshare.com/ndownloader/files/39962242

unzip the folder and start the UI.

The program reads the list of words in the text box on the left and generates:
- Neighbors: a file with the n° neighbors for each word
- Vectors: a file with all the required vectors, which includes all the words in the list
- Similarities: a file for each word with a table of target_words X matrix

The list of Matrices includes also a General Matrix built with Paisà Corpus (ITA)

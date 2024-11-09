# git-practice - Environmental Sound Classification
The ESC-50 dataset is a labeled collection of 2000 environmental audio recordings suitable for benchmarking methods of environmental sound classification. The dataset consists of 5-second-long recordings organized into 50 semantical classes (with 40 examples per class). For convenience, they are grouped in 5 loosely defined major categories (10 classes per category):

• animal sounds,

• natural soundscapes and water sounds,

• human (non-speech) sounds,

• interior/domestic sounds,

• exterior/urban noises

The ESC-10 is a selection of 10 classes from the bigger dataset, representing three general groups of sounds:

• transient/percussive sounds, sometimes with very meaningful temporal patterns (sneezing, dog barking, clock
ticking)

• sound events with strong harmonic content (crying
baby, crowing rooster )

• more or less structured noise/soundscapes (rain, sea
waves, fire crackling, helicopter, chainsaw)

---
Clips in this dataset have been manually extracted from public field recordings gathered by the [Freesound.org project.](https://freesound.org/) The dataset has been prearranged into 5 folds for comparable cross-validation, making sure that fragments from the same original source file are contained in a single fold.

The dataset esc50.csv can be accesed through the ESC-50-master/meta folder. A description of each column can be found in the table below:

| Header        |Description            |
| ------------- |:-------------:|
| filename| The name of the file  |  
| fold|index of the cross-validation fold   |    
| target |target accuracy for a sound recognition system with near-human capacity       |     
| category |The subclass of each category that the sound fits in      |
| esc10 |Indicates if a given file belongs to the ESC-10 subset        |
| src_file |Name of the source that the file belongs to       |
| take |Letter disambiguating between different fragments from the same Freesound clip      |

A more thorough description of the dataset is available in the original [paper](https://www.karolpiczak.com/papers/Piczak2015-ESC-Dataset.pdf) with some supplementary materials on GitHub: [ESC: Dataset for Environmental Sound Classification - paper replication data](https://github.com/karolpiczak/paper-2015-esc-dataset).

# License
The dataset is available under the terms of the [Creative Commons Attribution Non-Commercial license](https://creativecommons.org/licenses/by-nc/3.0/). A smaller subset (clips tagged as ESC-10) is distributed under CC BY (Attribution).

# Curator
[Karol Piczak](https://twitter.com/karoldvl) is a machine learning scientist focusing on sound classification tasks and assistant professor at Warsaw University of Technology.

# Citing
If you find this dataset useful in an academic setting please cite:

K. J. Piczak. ESC: Dataset for Environmental Sound Classification. Proceedings of the 23rd Annual ACM Conference on Multimedia, Brisbane, Australia, 2015.

[DOI: http://dx.doi.org/10.1145/2733373.2806390](https://dl.acm.org/doi/10.1145/2733373.2806390)

@inproceedings{piczak2015dataset,
  title = {{ESC}: {Dataset} for {Environmental Sound Classification}},
  author = {Piczak, Karol J.},
  booktitle = {Proceedings of the 23rd {Annual ACM Conference} on {Multimedia}},
  date = {2015-10-13},
  url = {http://dl.acm.org/citation.cfm?doid=2733373.2806390},
  doi = {10.1145/2733373.2806390},
  location = {{Brisbane, Australia}},
  isbn = {978-1-4503-3459-4},
  publisher = {{ACM Press}},
  pages = {1015--1018}
} 

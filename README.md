# git-practice
# Environmental Sound Classification
### The ESC-50 dataset is a labeled collection of 2000 environmental audio recordings suitable for benchmarking methods of environmental sound classification.The dataset consists of 5-second-long recordings organized into 50 semantical classes (with 40 examples per class). For convenience, they are grouped in 5 loosely defined major categories (10 classes per category):
• animal sounds,
• natural soundscapes and water sounds,
• human (non-speech) sounds,
• interior/domestic sounds,
• exterior/urban noises
### The ESC-10 is a selection of 10 classes from the bigger dataset, representing three general groups of sounds:
• transient/percussive sounds, sometimes with very meaningful temporal patterns (sneezing, dog barking, clock
ticking),
• sound events with strong harmonic content (crying
baby, crowing rooster ),
• more or less structured noise/soundscapes (rain, sea
waves, fire crackling, helicopter, chainsaw).
### Clips in this dataset have been manually extracted from public field recordings gathered by the Freesound.org project. The dataset has been prearranged into 5 folds for comparable cross-validation, making sure that fragments from the same original source file are contained in a single fold.
### The dataset esc50.csv can be accesed through the ESC-50-master/meta folder. A description of each column can be found in the table below.

| Header        |Description            |
| ------------- |:-------------:|
| filename| The name of the file  |  
| fold|index of the cross-validation fold   |    
| target |target accuracy for a sound recognition system with near-human capacity       |     
| category |The subclass of each category that the sound fits in      |
| esc10 |Indicates if a given file belongs to the ESC-10 subset        |
| src_file |Name of the source that the file belongs to       |
| take |Letter disambiguating between different fragments from the same Freesound clip      |

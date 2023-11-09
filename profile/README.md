## Universal Dependencies - Morphosyntactically Tagged Corpora

UDMorph is the Git organization for the [UDMorph](https://lindat.mff.cuni.cz/services/teitok-live/udmorph/) project. UDMorph attempts to gather morphologically annotated corpora and taggers, following the guidelines of the [Universal Dependencies](https://universaldependencies.org/), for as many languages as possible. The set-up is as far as possible similar to that of UD itself, but for data-sets that do not contains dependencies.

This organisation contains a all releasable UD data-sets in UDMorph, as well as several [tools](https://github.com/UDMorph/udmorph_tools) to interact with various formats that are helpful in the construction of (new) UDMorph data-sets. Datasets developed using TEITOK on UDMorph have 2 branches. The *files* branch contains a data folder with a separate CoNLL-U file for each files in the corpus, with metadata where relevant. While the main branch contains the traditional distribution over a dev, train, and test file, which have been automatically generated from the files in the files branch, with shuffled sentences in a 80/10/10 distribution.

UDMorph is a community effort, which will only work with the participation of researchers around the world. To contribute to UDMorph, please consult the dedicated repository [udmorph_contibutions](https://github.com/UDMorph/udmorph_contributions).

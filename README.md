# PanPA
PanPA (Pan-Proteome Aligner) is a tool written in Cython that builds protein graphs from MSAs, builds an index for the MSAs, and align query sequences back to the graphs generated. It is designed to work on amino acid graphs and the alignment can be done using many possible substitution matrix instead of only doing alignment using edit distance. It can also align DNA sequences back to amino acid graphs by translating the DNA sequences into 6 different possible reading frames and aligning the different reading frames.

The original repository with the code base, full documentation and running examples can be found [here](https://github.com/fawaz-dabbaghieh/PanPA)

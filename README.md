# Manifold Learning

One of the most important task in biological data analysis is manifold learning, especially for high-dimensional data. Let's consider a set of k-mers in sequences.csv. There are 3 motifs and random sequences, with lable 0 meaning random sequences. We would like to visualize the data in 2D space using t-SNE, by utilizing the Hamming distance matrix between all pairs of sequences.

Task:

Implement the t-SNE algorithm from scratch. Your code should take a distance matrix as input and output a 2D embedding. Please also print the loss value during the optimization process.

Visualize the 2D embedings of data points in normal_data.csv, colored by their labels. There are 20 features and the last column is the label. Compare your results with the t-SNE implementation in scikit-learn.

Visualize the 2D embedding of the sequences in sequences.csv, colored by their labels. Compare your results with the t-SNE implementation in scikit-learn. Report your findings about this data.

Reference: t-SNE, Laurens van der Maaten

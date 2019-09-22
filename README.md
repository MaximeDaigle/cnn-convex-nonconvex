# cnn on convex-nonconvex dataset

Larochelle et al. (2007) did an empirical evaluation of deep architectures. They obtained an error rate of 18.63 and 18.41 using Deep Belief Networks (DBN-3) and Stacked Autoassociators (SAA-3) on the convex nonconvex dataset. In this notebook, I give a 3-layer cnn obtaining an error rate of 1.28.

note: in the paper, they used 8000 train examples and 50000 test examples. I reversed it and used 50000 train examples and 8000 test examples.

convex nonconvex dataset and paper from: 
http://www.iro.umontreal.ca/~lisa/twiki/bin/view.cgi/Public/DeepVsShallowComparisonICML2007#Downloadable_datasets

http://www.dmi.usherb.ca/~larocheh/publications/deep-nets-icml-07.pdf

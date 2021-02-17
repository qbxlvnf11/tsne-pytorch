

Description
=============

#### - t-SNE for graph nodes neighbors
  - t-SNE learns a two-dimensional embedding vector that preserves a certain neighboring structure of data represented as a high-dimensional vector, and expresses high-dimensional data as a two-dimensional map.
  - We add two py files (get_neighbor_index.py, select_feature.py) to get neighbors index list of target node and select embedding vector appropriated for index list.
  - Plot the x-axis and y-axis of t-SNE classified labels

#### - Examples


Contents
=============

#### - get_neighbor_index.py
  - Save neighbors index list txt of target node using NetworkX
#### - select_feature.py
  - Select embedding vector apropriated to index list
  - index_text mode: read index list txt, index_range mode: set range of index list
#### - tsne_torch.py
  - Read feature vectors & labels and learning t-SNE
  - Plot axies of t-SNE
  - Using CUDA tensor
  - Examples
  
##### Order of execution: get_neighbor_index.py -> select_feature.py -> tsne_torch.py

Datasets
=============

#### - Amazon-Bok Dataset

https://jmcauley.ucsd.edu/data/amazon/

References
=============

#### - NetworkX Library

https://networkx.github.io/documentation/stable/index.html

#### - t-SNE Pytorch

https://github.com/mxl1990/tsne-pytorch

Author
=============

#### - LinkedIn: https://www.linkedin.com/in/taeyong-kong-016bb2154

#### - Blog URL: https://blog.naver.com/qbxlvnf11

#### - Email: qbxlvnf11@google.com, qbxlvnf11@naver.com

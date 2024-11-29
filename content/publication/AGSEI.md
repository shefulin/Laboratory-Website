+++
abstract = "Empowered by their remarkable advantages, graph neural networks (GNN) serve as potent tools for embedding graph-structured data and finding applications across various domains. Particularly, a prevalent assumption in most GNNs is the reliability of the underlying graph structure. This assumption, often implicit, can inadvertently lead to the propagation of misleading information through structures like false links. In response to this challenge, numerous methods for graph structure learning (GSL) have been developed. Among these methods, one popular approach is to construct a simple and intuitive K-nearest neighbor (KNN) graph as a sample to infer true graph structure. However, KNN graphs that follow the single-point distribution can easily mislead the true graph structure estimation. The primary reason is that, from a statistical perspective, the KNN graph, as a sample, follows a single-point distribution, whereas the true graph structure, as the population, as a whole mostly follows a long-tail distribution. In theory, the sample and the population should share the same distribution; otherwise, accurately inferring the true graph structure becomes challenging. To address this problem, this paper proposes an Adaptive Graph Structure Estimation with Long-Tail Distributed Implicit Graph, referred to as AGSEI. AGSEI comprises three main components: long-tail implicit graph construction, explicit graph structure estimation, and joint optimization. The first component relies on a multi-layer graph convolutional network to learn low-order to high-order node representations, compute node similarity, and construct several corresponding long-tail implicit graphs. Since the original imperfect graph structure can mislead GNNs into propagating false information, it reduces the reliability of the long-tail implicit graphs. AGSEI attempts to limit the aggregation of irrelevant information by introducing the Hilbert-Schmidt independence criterion. That is, maximizing the dependen..."
date = "2024-10-21"
image = ""
image_preview = ""
math = false
publication = "IEEE Transactions on Emerging Topics in Computing"
publication_short = ""
selected = false
title = "Adaptive Graph Structure Estimation with Long-Tail Distributed Implicit Graphs"
url_code = "//github.com"
url_dataset = ""
url_pdf = "10.1109/TETC.2024.3480132"
url_slides = ""
url_video = ""

[[authors]]
    name = "Yunfei He"
    is_member = true
[[authors]]
    name = "Yang Wu"
    is_member = true
[[authors]]
    name = "Lishan Huang"
    is_member = true
[[authors]]
    name = "Zhenwan Peng"
    is_member = true
[[authors]]
    name = "Fei Yang"
    is_member = true
[[authors]]
    name = "Yiwen Zhang"
    is_member = true
+++


<!-- You can add information in $\LaTeX$ and *Markdown* here. -->

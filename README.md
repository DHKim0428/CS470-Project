# CS470-Project

This academic project is based on [Embedding Poisoning](https://github.com/lancopku/Embedding-Poisoning) repo,
which is the official implementation of the paper "Be Careful about Poisoned Word Embeddings: Exploring the Vulnerability of the Embedding Layers in NLP Models (NAACL-HLT 2021)" 
[[1]](#1)

Also implement the Korean version of the attack based on the KLUE benchmark datasets [[2]](#2), kowikitext datasets [[repo]](https://github.com/lovit/kowikitext).

## Requirements

* python >= 3.6
* pytorch >= 1.7.0
* transformers >= 4.19.1

## How to use
Download dataset at [link](https://drive.google.com/drive/folders/1-tHnDS3yPSDq_eHkiYHduj65RBtxi4di?usp=sharing).
Read the description of the cs470_colab_replication.ipynb

## References
<a id="1">[1]</a> 
Wenkai Yang, Lei Li, Zhiyuan Zhang, Xuancheng Ren, Xu Sun, and Bin He. 2021. 
Be Careful about Poisoned Word Embeddings: Exploring the Vulnerability of the Embedding Layers in NLP Models. 
In Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, pages 2048–2058, Online. Association for Computational Linguistics.

<a id="2">[2]</a>
Sungjoon Park, Jihyung Moon, Sungdong Kim, Won Ik Cho, Jiyoon Han, Jangwon Park, Chisung Song, Junseong Kim, Yongsook Song, Taehwan Oh, Joohong Lee, Juhyun Oh, Sungwon Lyu, Younghoon Jeong, Inkwon Lee, Sangwoo Seo, Dongjun Lee, Hyunwoo Kim, Myeonghwa Lee, Seongbo Jang, Seungwon Do, Sunkyoung Kim, Kyungtae Lim, Jongwon Lee, Kyumin Park, Jamin Shin, Seonghyun Kim, Lucy Park, Alice Oh, Jungwoo Ha, Kyunghyun Cho. 2021. 
Klue: Korean language understanding evaluation. 
arXiv preprint arXiv:2105.09680.


# keyphrase-extraction-as-sequence-labeling-data
Dataset for the paper entitled, Keyphrase Extraction from Scholarly Articles as Sequence Labeling using Contextualized Embeddings.


This repository contains only the datasets used in the experiments and their overview

For more details on how the dataset was created, and the models trained on them,
please refer to our paper, [Keyphrase Extraction from Scholarly Articles as Sequence Labeling using Contextualized Embeddings](https://arxiv.org/abs/1910.08840)

We ran our experiments on three different publicly available keyphrase extraction datasets after transforming them into a format suitable for sequence labeling tasks. The formatted datasets are: 
1. [Inspec](https://github.com/midas-research/keyphrase-extraction-as-sequence-labeling-data/tree/master/Inspec) (Hulth 2003), 
2. [SemEval-2010](https://github.com/midas-research/keyphrase-extraction-as-sequence-labeling-data/tree/master/processed_semeval-2010) (Kim et al. 2010) (referred to as SE- 2010), 
3. [SemEval-2017](https://github.com/midas-research/keyphrase-extraction-as-sequence-labeling-data/tree/master/SemEval-2017) (Augenstein et al. 2017) (referred to as SE-2017)

We didn't change the tagging scheme for SE-2017 as they were already in a suitable format. We used the following tagging scheme for the other two datasets (Inspec and SE-2010).

<br>
<p align="center">
  <img src="https://github.com/midas-research/keyphrase-extraction-as-sequence-labeling-data/blob/master/tagging-scheme.png" alt="Tagging Scheme"  width="80%"/>
  <br>
</p>
<br>

Where, 
k<sub>B</sub>


## General Dataset Stats

<br>
<p align="center">
  <img src="https://github.com/midas-research/keyphrase-extraction-as-sequence-labeling-data/blob/master/keyphrase-stats.png" alt="General Dataset Stats"  width="80%"/>
  <br>
</p>
<br>

## BiLSTM vs BiLSTM-CRF (F1-score)

<br>
<p align="center">
  <img src="https://github.com/midas-research/keyphrase-extraction-as-sequence-labeling-data/blob/master/bltsm-vs-blstm-crf.png" alt="BiLSTM vs BiLSTM-CRF (F1-score)"  width="60%"/>
  <br>
</p>
<br>

## Fine-tuning vs Pretrained (F1-score)

<br>
<p align="center">
  <img src="https://github.com/midas-research/keyphrase-extraction-as-sequence-labeling-data/blob/master/fine-tuning-vs-pre-trained.png" alt="Fine-tuning vs Pretrained (F1-score)"  width="60%"/>
  <br>
</p>
<br>

## Embedding models comparison (F1-score)

<br>
<p align="center">
  <img src="https://github.com/midas-research/keyphrase-extraction-as-sequence-labeling-data/blob/master/embedding-model-comparison.png" alt="Embedding models comparison (F1-score)"  width="60%"/>
  <br>
</p>
<br>

## References

Please cite [[1]](https://arxiv.org/abs/1910.08840) if you found the resources in this repository useful.


[1] Sahrawat, D., Mahata, D., Kulkarni, M., Zhang, H., Gosangi, R., Stent, A., Sharma, A., Kumar, Y., Shah, R.R., & Zimmermann, R. (2019). [Keyphrase Extraction from Scholarly Articles as Sequence Labeling using Contextualized Embeddings](https://arxiv.org/abs/1910.08840). ArXiv, abs/1910.08840.


```
@article{Sahrawat2019KeyphraseEF,
  title={Keyphrase Extraction from Scholarly Articles as Sequence Labeling using Contextualized Embeddings},
  author={Dhruva Sahrawat and Debanjan Mahata and Mayank Kulkarni and Haimin Zhang and Rakesh Gosangi and Amanda Stent and Agniv Sharma and Yaman Kumar and Rajiv Ratn Shah and Roger Zimmermann},
  journal={ArXiv},
  year={2019},
  volume={abs/1910.08840}
}
```

If you are using this resource in your experiments, then please also cite:

[2] Hulth, A. (2003). Improved Automatic Keyword Extraction Given More Linguistic Knowledge. EMNLP.

[3] Kim, S.N., Medelyan, O., Kan, M., & Baldwin, T. (2010). SemEval-2010 Task 5 : Automatic Keyphrase Extraction from Scientific Articles. SemEval@ACL.

[4] Augenstein, I., Das, M., Riedel, S., Vikraman, L., & McCallum, A. (2017). SemEval 2017 Task 10: ScienceIE - Extracting Keyphrases and Relations from Scientific Publications. SemEval@ACL.



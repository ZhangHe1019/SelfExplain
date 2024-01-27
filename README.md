# SelfExplain Framework

The code for the SelfExplain framework (https://arxiv.org/abs/2103.12279) 

Currently, this repo supports SelfExplain-XLNet and SelfExplain-RoBERTa version for SST-2 dataset, SST-5 dataset, 
and SUBJ dataset. We have also tested it with CoLA, which only RoBERTa provide reasonable performance because
sentences in the CoLA are too short for XLNet.
 

## Citation 

```
@inproceedings{rajagopal-etal-2021-selfexplain,
    title = "{SELFEXPLAIN}: A Self-Explaining Architecture for Neural Text Classifiers",
    author = "Rajagopal, Dheeraj  and
      Balachandran, Vidhisha  and
      Hovy, Eduard H  and
      Tsvetkov, Yulia",
    booktitle = "Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing",
    month = nov,
    year = "2021",
    address = "Online and Punta Cana, Dominican Republic",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.emnlp-main.64",
    doi = "10.18653/v1/2021.emnlp-main.64",
    pages = "836--850",
}
```

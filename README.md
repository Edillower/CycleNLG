# Faithful Low-resource Data-to-Text Generation through Cycle Training 

Howdy! 

(July 11th, 2023 Update) 

I'm happy to share that our code is publically available at: https://github.com/amzn/faithful-data2text-cycle-training 

Our code include a little extra functionalies beyond what we have reported in this paper, and feel free to use it for further research : ) 

As the we don't have the ownership of the data, we advise you to check the offical data release of WebNLG and DART. 

In the meantime, I will keep this repository open. If you have any questions regarding the preprocessing of the data, running of the model, data annotation, use of the slides, etc., you are very welcomed to open an issue here or email me directely via [wang(at)tamu.edu]. I'm also open to any potential collaboration opportunities.  

Thanks again for your interests in our work, and we hope it could help you! 


~~Our code release is under Amazon's internal approval process.
The code will be released at https://github.com/amzn, and we will update the repository link once approved. 
In the meantime, you are very welcome to contact us if you need any implementation assistance to replicate the work prior to the official code release.~~

## Cite us
Please use the following bibtex when referencing this work:
```
@inproceedings{wang-etal-2023-faithful,
    title = "Faithful Low-Resource Data-to-Text Generation through Cycle Training",
    author = "Wang, Zhuoer  and
      Collins, Marcus  and
      Vedula, Nikhita  and
      Filice, Simone  and
      Malmasi, Shervin  and
      Rokhlenko, Oleg",
    booktitle = "Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = jul,
    year = "2023",
    address = "Toronto, Canada",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.acl-long.160",
    pages = "2847--2867",
    abstract = "Methods to generate text from structured data have advanced significantly in recent years, primarily due to fine-tuning of pre-trained language models on large datasets. However, such models can fail to produce output faithful to the input data, particularly on out-of-domain data. Sufficient annotated data is often not available for specific domains, leading us to seek an unsupervised approach to improve the faithfulness of output text. Since the problem is fundamentally one of consistency between the representations of the structured data and text, we evaluate the effectiveness of cycle training in this work. Cycle training uses two models which are inverses of each other: one that generates text from structured data, and one which generates the structured data from natural language text. We show that cycle training, when initialized with a small amount of supervised data (100 samples in our case), achieves nearly the same performance as fully supervised approaches for the data-to-text generation task on the WebNLG, E2E, WTQ, and WSQL datasets. We perform extensive empirical analysis with automated evaluation metrics and a newly designed human evaluation schema to reveal different cycle training strategies{'} effectiveness of reducing various types of generation errors.Our code is publicly available at https://github.com/Edillower/CycleNLG.",
}
```

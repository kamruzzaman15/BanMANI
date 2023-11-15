# BanMANI
This is the Benchmark Dataset for identifying manipulated social media news in Bangla

Both the train and test data are in the BanMANI.csv file. 

In this paper, we present a semi-automatic method for generating such a dataset, which allows scalable dataset collection using annotators efficiently for languages like Bamgla with few available NLP tools. We also use zero-shot ChatGPT (GPT-3.5) and fine-tune GPT-3 to evaluate our dataset. 

This paper is accepted and presented at the 16th Workshop on Building and Using Comparable Corpora, Co-located with RANLP 2023, and incorporates the first Workshop on Computational Terminology in NLP and Translation Studies (ConTeNTs), Varna, Bulgaria. 

The full paper is available at https://aclanthology.org/2023.contents-1.7/

If you use this work, please cite:





@inproceedings{kamruzzaman-etal-2023-banmani,
    title = "{B}an{MANI}: A Dataset to Identify Manipulated Social Media News in {B}angla",
    author = "Kamruzzaman, Mahammed  and
      Shovon, Md. Minul Islam  and
      Kim, Gene",
    editor = "Haddad, Amal Haddad  and
      Terryn, Ayla Rigouts  and
      Mitkov, Ruslan  and
      Rapp, Reinhard  and
      Zweigenbaum, Pierre  and
      Sharoff, Serge",
    booktitle = "Proceedings of the Workshop on Computational Terminology in NLP and Translation Studies (ConTeNTS) Incorporating the 16th Workshop on Building and Using Comparable Corpora (BUCC)",
    month = sep,
    year = "2023",
    address = "Varna, Bulgaria",
    publisher = "INCOMA Ltd., Shoumen, Bulgaria",
    url = "https://aclanthology.org/2023.contents-1.7",
    pages = "51--58",
    abstract = "Initial work has been done to address fake news detection and misrepresentation of news in the Bengali language. However, no work in Bengali yet addresses the identification of specific claims in social media news that falsely manipulate a related news article. At this point, this problem has been tackled in English and a few other languages, but not in the Bengali language. In this paper, we curate a dataset of social media content labeled with information manipulation relative to reference articles, called BanMANI. The dataset collection method we describe works around the limitations of the available NLP tools in Bangla. We expect these techniques will carry over to building similar datasets in other low-resource languages. BanMANI forms the basis both for evaluating the capabilities of existing NLP systems and for training or fine-tuning new models specifically on this task. In our analysis, we find that this task challenges current LLMs both under zero-shot and fine-tuned set- things",
}






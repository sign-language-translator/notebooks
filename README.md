# Jupyter Notebooks for Sign Language Translator

Jupyter notebooks using the <kbd>[sign_language_translator](https://github.com/sign-language-translator/sign-language-translator)</kbd> package and showing demos as well.

## Open in Google Colab ![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)

<pre>
<b>notebooks</b>
├── README.md
├── experiments.ipynb
├── <b>data_collection</b>
│   ├── clip_extractor.ipynb
│   ├── hugging_face_text_datasets.ipynb
│   ├── language_models.ipynb
│   ├── names_LM.ipynb
│   ├── parallel_corpus.ipynb
│   ├── synonyms.ipynb
│   ├── text_cleaning.ipynb
│   ├── text_extraction.ipynb
│   ├── text_scrapper.ipynb
│   ├── <a href="https://colab.research.google.com/github/sign-language-translator/notebooks/blob/main/data_collection/trim_clips.ipynb">trim_clips.ipynb</a>:   <sub><sup>analyze position of wrists in frame and remove pauses at start & end</sup></sub>
│   └── zip_dataset.ipynb
│
├── <b>model_training</b>
│   ├── embeddings.ipynb
│   ├── ngram_training.ipynb
│   └── transformer_lm_training.ipynb
│
├── <b>text</b>
│   ├── align_embeddings.ipynb
│   ├── frequency.ipynb
│   ├── text_embedding.ipynb
│   └── vocab.ipynb
│
├── <b>translation</b>
│   └── <a href="https://colab.research.google.com/github/sign-language-translator/notebooks/blob/main/translation/concatenative_synthesis.ipynb">concatenative_synthesis.ipynb</a>:    <sub><sup>(text to sign) join sign for each word in text and play</sup></sub>
│
└── <b>vision</b>
    ├── concatenate_demo.ipynb
    ├── landmark_display.ipynb
    ├── transforms_demo.ipynb
    ├── video_embedding.ipynb
    ├── video.ipynb
    ├── <b>inputs</b>
    │   └── *
    └── <b>outputs</b>
        └── *
</pre>

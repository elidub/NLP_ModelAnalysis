# Model Analysis of Tree-LSTM and ... (more)

We present a comparative review of where we test various BOW and LSTM models to asses the impact of word embedding (GloVe and Word2Vec), word order, supervising node-sentiment and hierarchy. Our analysis shows that Tree-LSTMs are the most effective for sentiment analysis, and incorporating additional context and structure into the models can improve their performance. We also found that word order-sensitive models can capture long-term dependencies in text data and outperform traditional models. Additionally, choosing the right word embedding is important, and incorporating syntactic structure (word order, hierarchy, supervising node sentiment) can improve performance further.

This paper was written in the context of the context of a project for the course "Natural Language Processing 1" at the University of Amsterdam. The full paper can be found [here](some link).

## Repository Structure

- `figures/` All saved figures produced by the notebook and shown in the paper.
- `models/` All the trained models. Models can be retrained by running the notebook. Index after model refers to different seeds.
- `trees/` The data, i.e. the parsed trees of the sentences to classify.
- `env_nlp1.yml` The Conda environment used for this project. Can be installed with `conda env create -f env_nlp1.yml`.
- `modelanalysis.ipynb` All code training and evaluating the models and producing the figures. The notebook is an adapted version of the instructions for the project. We advise to set the global setting `LOAD_MODELS` to `True` to load the models instead of retraining them. This will save a lot of time.
- `NLP_paper_Dubbeldam_Vermeer.pdf` The full paper.

## Contact
For any questions, please contact [eliasdubbeldam@gmail.com](mailto:eliasdubbeldam@gmail.com)


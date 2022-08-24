# **SentimentArcs: Novels Corpus**
## **A Curated Reference Corpus of Novels for analyzing sentiment over time**


A corpus of diverse novels to provide an reference for time series sentiment analysis of long-form narratives. This one (of several) baseline reference corpus accompanying the SentimentArcs ensemble of models.


## **Problem Definition and Goal**

Unlike most sentiment analysis tasks, diachronic long-form narrative is more complex, diverse and interpretive in nature. For example, long-form sentiment analysis results in time series rather than simple point estimates of sentiment. This time series involves more involved questions like chunking, smoothing and feature detection (e.g. peaks/valleys).

Typical sentiment analysis tasks work on relatively short product reviews or social media tweets. In contrast, long-form narratives in novel form usually involve more complex, subtle and contradictory use of language and narrative structure. To address these issues, SentimentArcs is a pipeline of Jupyter notebooks designed to incorporate an expert human-in-the-loop.

To orientate and efficiently utilize the expert human-in-the-loop, this SentimentArc Novels Reference Corpus was created to provide an initial reference set of data for exploring, critiquing, and validating the analysis of new texts in the future.

## **Curation Guidelines**

The principles used to compile this reference corpus of novels is described in the Paper [SentimentArcs: A Novel Method for Self-Supervised Sentiment Analysis of Time Series Shows SOTA Transformers Can Struggle Finding Narrative Arcs](https://arxiv.org/abs/2110.09454)

```
SentimentArcs’ corpora consists of 25 narratives selected to create a diverse set of well recognized novels that can serve as a benchmark for future studies. The composition of the corpora was limited by the effect of copyright laws as well as historical imbalances. Most works were obtained from US and Australian Gutenberg Projects (Gutenberg, 2021) (Project Gutenberg, 2021a). The corpora is expected to grow in size and diversity over time. We welcome collaboration with domain experts who can provide analysis and annotations on long text narratives (e.g. individual novels, collected works, plays, long social media threads, news and social media compilations, etc).

Each novel in the corpora was parsed into lines as described in the Text Preprocessing section below. The minimum corpus length is 1,399 lines, the maximum length is 13,258 lines, and the mean length is 4,856 lines. There is significant variation in lengths with a standard deviation of 2,899 lines and a 25-75% quartile range between 2,984 to 6,448. There is a right distributional skew of novel lengths as seen in Figure 2 below.

Several dimensions of diversity were considered for inclusion including popularity, period, genre, topic, style and author diversity. The first version of our corpus includes only English, although Proust and Homer are included in translation. SentimentArcs has processed a larger set of novels, including some in foreign languages. The initial reference corpus is in English since performance across all ensemble models was uneven in less resourced languages (Dashtipour et al.,
2016).

SentimentArcs’ corpora spans approximately 2300 years from Homer’s Odyssey to the 2019 Machines like Me by
award-winning author, Ian McEwan. Early 20th century modernists are emphasized with authors like Marcel Proust
and Virginia Woolf because this is the speciality of our collaborating literary scholar, Katherine Elkins. In upcoming publications, Elkins provides the ground truth domain expertise with a close and intermediate reading of the 840 sentiment arcs produced by the ensemble’s 34 models processing each of the 25 works.

In sum, the corpora includes (1) the two most popular novels on Gutenberg.org (Project Gutenberg, 2021b), (2) eight of the fifteen most assigned novels at top US universities (EAB, 2021), and (3) three works that have sold over 20 million copies (Books, 2021). There are eight works by women, two by African-Americans and five works by two LGBTQ authors. Britain leads with 15 authors followed by 6 Americans and one each from France, Russia, North Africa and Ancient Greece.
```

![https://github.com/jon-chun/sentimentarcs_notebooks/raw/main/images/paper_sentimentarcs_arxiv.jpg](https://github.com/jon-chun/sentimentarcs_notebooks/raw/main/images/paper_sentimentarcs_arxiv.jpg)

## **Access**

All novels in the SentimentArc Novels Reference Corpus are represented here as time series based upon various sentiment analysis models. The specific preprocessing, models, hyperparameters, and postprocessing steps taken are described in the (SentimentArcs)[] research paper. 

Due to copyright laws, only those novels which are in the Public Domain can be provided in this Github repo.

## **Application and Interpretation**

Both the [SentimentArc series of Jupyter notebooks](https://github.com/jon-chun/sentimentarcs_notebooks) as well as this SentimentArc Novels Reference Corpus are the basis for Katherine Elkins's Cambridge University Press book: [The Shapes of Stories: Sentiment Analysis for Narrative](https://www.cambridge.org/core/elements/abs/shapes-of-stories/3047F01956467FA981DB9F14A18A6725). Refer to this text for an indepth explaination of how to use these tools for sentiment analysis of long-form narrative.

![https://www.cambridge.org/core/elements/abs/shapes-of-stories/3047F01956467FA981DB9F14A18A6725](https://assets.cambridge.org/97810092/70397/cover/9781009270397.jpg)
## **Contributions**

If you are interesting in using SentimentArcs for long-form narrative analysis and have new texts to share for inclusion into the corpus, please contact the authors at:

* elkinsk@kenyon.edu
* chunj@kenyon.edu


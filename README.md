# Visualizing Trends in Education Research Using NLP and Network Analysis

## Abstract

Papers published in reputable journals tend to reflect the prevailing values and ideologies of their time. To study how these perspectives in education have changed over time, we used Natural Language Processing and Machine Learning to process over 1 million education-related articles published from 1980 to 2020. By extracting keywords from titles and abstracts, we formed term networks and clustered them using k-means.

Using VosViewer, we generated network graphs for five time periods. These graphs display terms as nodes, with node size representing frequency and edge thickness representing co-occurrence strength. We focused on trends related to keywords such as **technology**, **child**, **success**, and **mathematics**, observing how their relationships with other terms evolved across decades.

## Methodology

- **Dataset**: 1MILSED, comprising 1,035,065 education publications from Scopus, Unpaywall, and PlumX
- **Periodization**: Five decades (1980–1989, 1990–1999, 2000–2009, 2010–2019, 2020)
- **Tools**: VosViewer for network generation and coordinate computation
- **Graph Thresholds**: Minimum term co-occurrence set to 101 for sparsity
- **Normalization**: Only journals and terms appearing in all five periods were retained

## Key Observations

- **Mathematics**: Initial focus on coursework gradually shifted to student-centered concerns like interest and disability
- **Success**: Shift from individual results to collaborative and process-oriented definitions
- **Technology**: Growth from marginal to central, reflecting its rising importance in education and broader society

## Poster

[Click here to view the full poster (PDF)](./poster.pdf)

Alternatively, if your platform supports embedded PDFs:

```html
<embed src="poster.pdf" type="application/pdf" width="100%" height="600px" />

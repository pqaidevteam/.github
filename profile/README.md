# PQAI: Patent Quality Artificial Intelligence

PQAI is a collaborative initative to build open-source tools adapted for patent
data mining using natural language processing (NLP) and machine learning (ML).

PQAI provides ready-to-use implementations of a number of software components
frequently used in patent data mining. These components have been used to create
an openly accessible [prior-art search engine](https://search.projectpq.ai/).

Each component is available as an independently deployable [FastAPI](https://fastapi.tiangolo.com/) app:

1. [pqai-db](https://github.com/pqaidevteam/pqai-db)
1. [pqai-encoder](https://github.com/pqaidevteam/pqai-encoder)
1. [pqai-index](https://github.com/pqaidevteam/pqai-index)
1. [pqai-classifier](https://github.com/pqaidevteam/pqai-classifier)
1. [pqai-reranker](https://github.com/pqaidevteam/pqai-reranker)
1. [pqai-snippet](https://github.com/pqaidevteam/pqai-snippet)

Another component, called [pqai-gateway](https://github.com/pqaidevteam/pqai-gateway)
provides an extensible frameworks in which various plugins can be written to
orchestrate inter-component communication to achieve real-word tasks such
as prior-art searching.

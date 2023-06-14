# Bibliographic Graph Analysis and Clustering of Book Titles

This project focuses on conducting a bibliographic graph analysis and clustering of book titles using abstracts. The analysis provides insights into the relationships between publishers and authors, as well as the clustering patterns among book titles. The project utilizes Python and various data analysis libraries to perform the analysis.

## Dataset

The dataset used in this project is the "Bulk Bookstore Dataset" (bulk_bookstore_dataset.csv). It contains information about book titles, authors, publishers, and languages. The dataset is preprocessed to select relevant columns and remove any missing values.

## Methodology

The project follows the following methodology:

1. **Bibliographic Graph Analysis:** The dataset is used to construct a directed graph, representing the relationships between publishers and authors. The graph is visualized to understand the collaborative networks within the book industry.

2. **Clustering Analysis:** The abstracts of book titles are vectorized using TF-IDF and reduced in dimensionality using Truncated SVD. K-means clustering is applied to group similar book titles based on their abstracts. The clusters are visualized in 3D space to identify thematic clusters.

3. **Distribution Analysis:** The distribution of variables such as title, author, and publisher is analyzed using count plots. This provides insights into the frequencies and distribution patterns within the dataset.

## Results

The project yields the following results:

- The bibliographic graph visualization reveals the connections and collaborations within the book industry, highlighting the relationships between publishers and authors.
- The clustering analysis identifies thematic clusters among book titles based on their abstracts, providing a deeper understanding of the content similarities.
- The distribution analysis shows the frequencies and distribution patterns of book titles, authors, and publishers within the dataset.

## Conclusion and Future Work

The project concludes that bibliographic graph analysis and clustering techniques can provide valuable insights into the book industry. The relationships between publishers and authors, as well as thematic clusters among book titles, can be uncovered through these analyses. The findings have implications for collaboration, marketing strategies, and recommendation systems.

Future work can include:

- Conducting a more comprehensive network analysis of the bibliographic graph to uncover important nodes, influential publishers or authors, and cohesive clusters.
- Exploring additional textual features beyond abstracts, such as book summaries or keywords, to enhance clustering results and enable finer categorization.
- Incorporating temporal aspects to analyze trends, changes, and evolution in the collaborations and book topics over time.
- Developing predictive models or recommendation systems based on the insights gained from the analysis.
- Expanding the dataset by including diverse data sources to enrich the analysis and validate findings.

## Dependencies

- Python 3.x
- pandas
- networkx
- matplotlib
- scikit-learn
- seaborn


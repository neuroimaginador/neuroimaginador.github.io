---
title: "Mining Fuzzy Concept Lattices"
authors:
- Manuel Ojeda-Hernández
- admin
- Ángel Mora
- Pablo Cordero
date: "2022-07-04T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-21T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In the *22nd International Conference on Computational and Mathematical Methods in Science and Engineering 2022*
publication_short: In *CMMSE 2022*

abstract: One of the ways to represent the implicit knowledge in a binary dataset under the paradigm of Formal Concept Analysis is the concept lattice. This lattice allows describing a hierarchical biclustering between objects and attributes of a formal context. Concepts are the fixed points of a Galois connection, describing a closure system. In practice, the computation of such lattice presents a high complexity, the number of concepts can be exponential in the size of the input context. Therefore, there is interest in developing new algorithms that take advantage of the lattice structure to efficiently compute the concept set. Thus, many algorithms have been proposed to compute the concept lattice in this binary setting in the last years. To avoid the complete enumeration of subsets to check which of them are closed, some pruning strategies have been proposed. For example, the NextClosure algorithm defines a lectic order in which to explore closed sets. Other strategies are based on a recursive tree search accompanied by canonicity tests that allow a more efficient exploration. Those based on the CbO strategy, such as FastCbO (FCbO), or InClose stand out. It is possible to extend this framework to take into account the different degrees to which an attribute could be present in an object. Through this extension, it is possible to model fuzzy situations where the attribute is not 100% present in an object, giving flexibility to the model. In this paper, we extend the previous algorithms for the calculation of the fuzzy concept lattice. We show how the InClose family of algorithms can be extended from the binary setting to the fuzzy one, detailing the differences and how new canonicity tests can be employed in order to reduce the computational cost of determining the set of concepts. We show that these new algorithms can compete with the state of the art in terms of execution time and in number of operations performed. These algorithms may open a new research line in which optimised algorithms can be deduced and built ad hoc for the computation of the fuzzy concept lattice.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Formal concept analysis
- Concept lattice
- Algorithms
featured: true

url_pdf: publication/2022-cmmse/paper.pdf
url_slides: 'publication/2022-cmmse/slides.pdf'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [2019-flair]

---

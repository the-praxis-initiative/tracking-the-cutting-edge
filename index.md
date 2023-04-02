# Research Topics in the State of the Art (2023)

Welcome to the session for **Research Topics in the State of the Art**, as applied to knowledge graphs, the Semantic Web, and application scenarios. This session takes the form of a "Survey of Surveys", where we have invited several speakers whom have conducted thorough research into the state of the art in specific topic areas of knowledge graphs, their construction, and how they can be applied more broadly. The purpose of this session is to address the following questions.
* What is the state of the art?
* What are the research gaps yet to be addressed?
* Who is on the cutting edge?
* How can the state of the art be applied to solve current problems?

## Program
This session will be held by the [Knowledge Graph Conference](https://knowledgegraph.tech/) on May 11th from 11am to 12:30pm EST and continuing from 2-3pm EST.
* Introduction (10 minutes)
* Each talk will be about 20 minutes long with an additional 5 minutes of Q&A.

## Speakers

### Information Extraction meets the Semantic Web: A Survey
**Authors:** Jose L. Martinez-Rodriguez, *Aidan Hogan*, Ivan Lopez-Arevalo

**Abstract:** We provide a comprehensive survey of the research literature that applies Information Extraction techniques in a Semantic Web setting. Works in the intersection of these two areas can be seen from two overlapping perspectives: using Semantic Web resources (languages/ontologies/knowledge-bases/tools) to improve Information Extraction, and/or using Information Extraction to populate the Semantic Web. In more detail, we focus on the extraction and linking of three elements: entities, concepts and relations. Extraction involves identifying (textual) mentions referring to such elements in a given unstructured or semi-structured input source. Linking involves associating each such mention with an appropriate disambiguated identifier referring to the same element in a Semantic Web knowledge-base (or ontology), in some cases creating a new identifier where necessary. With respect to entities, works involving (Named) Entity Recognition, Entity Disambiguation, Entity Linking, etc. in the context of the Semantic Web are considered. With respect to concepts, works involving Terminology Extraction, Keyword Extraction, Topic Modeling, Topic Labeling, etc., in the context of the Semantic Web are considered. Finally, with respect to relations, works involving Relation Extraction in the context of the Semantic Web are considered. The focus of the majority of the survey is on works applied to unstructured sources (text in natural language); however, we also provide an overview of works that develop custom techniques adapted for semi-structured inputs, namely markup documents and web tables. 

Slides: [slides](./slides/slides.pdf)

Background knowledge: N/A

### A Survey on Visual Transfer Learning using Knowledge Graphs
**Authors:** *Sebastian Monka*, Lavdim Halilaj, Achim Rettinger

**Abstract:** The information perceived via visual observations of real-world phenomena is unstructured and complex. Computer vision (CV) is the field of research that attempts to make use of that information. Recent approaches of CV utilize deep learning (DL) methods as they perform quite well if training and testing domains follow the same underlying data distribution. However, it has been shown that minor variations in the images that occur when these methods are used in the real world can lead to unpredictable and catastrophic errors. Transfer learning is the area of machine learning that tries to prevent these errors. Especially, approaches that augment image data using auxiliary knowledge encoded in language embeddings or knowledge graphs (KGs) have achieved promising results in recent years. This survey focuses on visual transfer learning approaches using KGs, as we believe that KGs are well suited to store and represent any kind of auxiliary knowledge. KGs can represent auxiliary knowledge either in an underlying graph-structured schema or in a vector-based knowledge graph embedding. Intending to enable the reader to solve visual transfer learning problems with the help of specific KG-DL configurations we start with a description of relevant modeling structures of a KG of various expressions, such as directed labeled graphs, hypergraphs, and hyper-relational graphs. We explain the notion of feature extractor, while specifically referring to visual and semantic features. We provide a broad overview of knowledge graph embedding methods and describe several joint training objectives suitable to combine them with high dimensional visual embeddings. The main section introduces four different categories on how a KG can be combined with a DL pipeline: 1) Knowledge Graph as a Reviewer; 2) Knowledge Graph as a Trainee; 3) Knowledge Graph as a Trainer; and 4) Knowledge Graph as a Peer. To help researchers find meaningful evaluation benchmarks, we provide an overview of generic KGs and a set of image processing datasets and benchmarks that include various types of auxiliary knowledge. Last, we summarize related surveys and give an outlook about challenges and open issues for future research.

Slides: [slides](./slides/slides.pdf)

Background knowledge: N/A

### When Linguistics Meets Web Technologies. Recent advances in Modelling Linguistic Linked Data
**Authors:** *Fahad Khan*, Christian Chiarcos, Thierry Declerck, Daniela Gifu, Elena González-Blanco García, Jorge Gracia, Max Ionov, Penny Labropoulou, Francesco Mambrini, John McCrae, Émilie Pagé-Perron, Marco Passarotti, Salvador Ros, Ciprian-Octavian Truica

**Abstract:** This article provides an up-to-date and comprehensive survey of models (including vocabularies, taxonomies and ontologies) used for representing linguistic linked data (LLD). It focuses on the latest developments in the area and both builds upon and complements previous works covering similar territory. The article begins with an overview of recent trends which have had an impact on linked data models and vocabularies, such as the growing influence of the FAIR guidelines, the funding of several major projects in which LLD is a key component, and the increasing importance of the relationship of the digital humanities with LLD. Next, we give an overview of some of the most well known vocabularies and models in LLD. After this we look at some of the latest developments in community standards and initiatives such as OntoLex-Lemon as well as recent work which has been in carried out in corpora and annotation and LLD including a discussion of the LLD metadata vocabularies META-SHARE and \textit{lime} and language identifiers. In the following part of the paper we look at work which has been realised in a number of recent projects and which has a significant impact on LLD vocabularies and models. 

Slides: [slides](./slides/slides.pdf)

Background knowledge: N/A

### A Survey on Knowledge Graph Embeddings with Literals: Which model links better Literal-ly?
**Authors:** *Genet Asefa Gesese*, Russa Biswas, Mehwish Alam, Harald Sack

**Abstract:** Knowledge Graphs (KGs) are composed of structured information about a particular domain in the form of entities and relations. In addition to the structured information KGs help in facilitating interconnectivity and interoperability between different resources represented in the Linked Data Cloud. KGs have been used in a variety of applications such as entity linking, question answering, recommender systems, etc. However, KG applications suffer from high computational and storage costs. Hence, there arises the necessity for a representation able to map the high dimensional KGs into low dimensional spaces, i.e., embedding space, preserving structural as well as relational information. This paper conducts a survey of KG embedding models which not only consider the structured information contained in the form of entities and relations in a KG but also the unstructured information represented as literals such as text, numerical values, images, etc. Along with a theoretical analysis and comparison of the methods proposed so far for generating KG embeddings with literals, an empirical evaluation of the different methods under identical settings has been performed for the general task of link prediction.

Slides: [slides](./slides/slides.pdf)

Background knowledge: N/A

## Organizing Committee
* Annalisa Gentile<br />
IBM Research
* Kunal Sengupta<br />
Amazon Neptune
* Cogan Shimizu<br />
[Knowledge and Semantics Technologies (KASTLE) Lab](kastle-lab.github.io/), Wright State University

## Partners
* Pascal Hitlzer<br />
[Data Semantics Lab](https://daselab.org/), Kansas State University<br />
[Semantic Web](https://semantic-web-journal.net/)
* François Scharffe<br />
[Knowledge Graph Conference](https://knowledgegraph.tech/)
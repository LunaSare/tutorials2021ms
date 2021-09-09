**submission**<br>

Journal of Statistics and Data Science Education<br>
Peer J?

**Subject of journal issue**: Teaching reproducibility and responsible workflow.


**Title of Manuscript**<br>
Promoting analysis reproducibility with accessibility: An example in phylogenetics.

**Authors**<br>
Luna L Sanchez-Reyes and Emily Jane McTavish

**Goal of the ms:**<br>
A lesson in reproducible analyses and workflows for phylogenetics and evolution, separate from software package publication.

We are using a backwards design strategy to write the ms.

## Introduction

Reproducibility, --the extent to which consistent results are obtained when a scientific experiment is repeated (https://cure.web.unc.edu/defining-reproducibility/)-- is a key aspect for the advancement of Science (CITE).
Reproducibility rates in the natural sciences are low (https://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.0020124), which have prompted rising concerns about a reproducibility crisis in the field (CITE). Reproducibility is composed of many elements (availability, accesibility,... ). In this work, we focus on identifying and addressing factors that have affected negatively scientific accessibility in the natural sciences.

For research areas in which computation plays a significant role in deriving scientific findings, efforts have been largely focused on incentivizing a shift from normalized scientific sharing practices towards improving availability of raw data from experiments, the computational code used to manage and analyze the data, and the corresponding documentation for data and code, through deposition in a public database or repository (CITE). Availability of data, code and documentation is considered to be the key requirement for reproducibility by many (https://rss.onlinelibrary.wiley.com/doi/full/10.1111/j.1740-9713.2015.00827.x).

However, scientific information available in public repositories can have limited access in various ways. For example, data and code might have been shared using formats that are not computer readable, hindering their reanalysis and reuse (for example, sharing a datatble as an image, instead of a txt file). Moreover, there might be country or institution based restrictions to data download, data embargoes by the authors, or the repository might require a suscription to download the data.
Conceptual, financial, language, etc., accessibility must be addressed too. In sum, availability does not automatically imply accessibility (Box 1), and to achieve full reproducibility, availability must be accompanied by accessibility. 


Phylogenetics is a field in the natural sciences that focus on understanding of evolutionary relationships among organisms by inference of phylogenetic trees, providing the basis to study and understand biological processes (CITE). Improving reproducibility and availability of phylogenetic research is of great importance for biological research (CITE).

The Open Tree of Life project (OpenTree) has developed a platform to standardize sharing and storing of results from phylogenetic research, with the goal of synthesizing a single phylogenetic tree encompassing all life (CITE).
While all data in OpenTree can be accessed programmatically through its many Application Programming Interface (API) services (CITE), 
R packages (CITE) and Python libraries (CITE) have been developed as wrappers for OpenTree API services for the benefit of a wider programming audience.
The R and Python OpenTree wrappers have been utilized by computer-savvy individuals, to seamlessly establish reproducible workflows to use and reuse expert phylogenetic knowledge for biological research (CITE datelife, …) and education (CITE phylotastic, galacticEdTools, …). 

Inherently, efforts to increase reproducibility and availability have also increased computational knowledge and skill requirements in all areas of research, and phylogenetics is no exception.

Computing is not a common skill nor main interest among biologists, and OpenTree's high-level programming language wrappers are still infrequently or not fully adopted by students and researchers with any level of programming knowledge, slowing down a wider adoption of reproducbile workflows in phylogenetics.

In this work we focus on improving accessibility of documentation.

**_Link: Why focus on documentation?_**

Good primary documentation for code describes general usage of individual functions, the components and variables a function can take, and it should be accompanied with function usage examples on how to apply it (CITE).

As opposed to code, primary documentation is written in natural language (i.e., any known human language, e.g., English, Spanish, Chinese) and usually makes use of highly specialized computational jargon (computationally specific concepts, words, and phrases) as well as formal language, which often slows down or even obstructs examination, application, and adoption of code by external individuals. 

Because primary documentation is considered a professional document, acceptance of the research by the scientific community could be reduced if a more informal language is used.

Secondary types of documentation, such as vignettes and tutorials, demonstrate more cases of individual function usage, and describe analysis workflows in more detail, as well as function associations to generate a specific analysis and results. While secondary documentation has become more common practice, it is still often generated using highly specialized language. 

In this paper, we identify the necessity for secondary documentation that is written down using language that is common to the target audience to facilitate examination, application, and adoption of code by the wider audience.

We present a set of principles to generate tutorials that improve accessibility of code and documentation. We applied these principles to a series of tutorials and vignettes for the Open Tree of Life package.

## Methods

### Principles

- To make documentation of packages more accesible, using common (informal?) language is the best. Explaining computational terms that are needed at the beginning and also throught the text.
- Create documents that persist and are free for use and reuse, so they are available for the users to go back to them any time they need them, and to be passed on to other users.
- Use charismatic organisms to make examples
- Demonstrate errors
- Demonstrate warnings
- Help users to not be afraid of errors and warnings, but instead to use them to their advantage (CITE carpentries)
- Give alternatives on what to do when faced with an error or warning, and demonstrate these alternatives.
- 
## Results





We have received emails from senior researchers thanking us for this materials, and students have been able to engage using the packages with less hep from the PIs.


### Box 1
Availability does not impy accessibility. One example I really like is the marshmallows in an office. The marshmallow bags were there, availabe for anyone to eat them. But until someone opened the bag and put the marshmallows in a tray or container, people started eating them. Maybe it was something psychological in this case. But the point is that simply sharing your code and documenting it might not be enough for the average researcher to reproduce, they'll be able to figure it out, but the time needed to do so might not be worthy in their mind, or might not be something they can invest in, even if it would be useful for them long term, the short term investment is too intense.
Let alone students that are just starting, it is even more daunting for them.


## Discussion

The principles to create tutorials described here facilitate adoption of software and analysis wokflows among researchers at different academic levels, from undergards to established researchers.

It will also help closing the gap between students that had access to computational resources (and computational training) from an early age and students that did not. Late access to computational resources and training can occur due to lack of economic resources, often ocurring in households from underrepresented communities and minorites. It can also be due to gender-biased parental and community pressures, in which males are more often encouraged to perform activities related to computers, while females are discouraged.

How to balance software acceptance VS. adoption?
These principles can be used to aide not only reproducibility, but also software adoption in the natural sciences.














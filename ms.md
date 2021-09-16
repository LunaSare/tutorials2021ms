**submission**<br>

Journal of Statistics and Data Science Education<br>
Peer J?

**Subject of journal issue**: Teaching reproducibility and responsible workflow.


**Title of Manuscript**<br>
Promoting analysis reproducibility with accessibility: An example in evolutionary biology.

**Authors**<br>
Luna L Sanchez-Reyes and Emily Jane McTavish

**Goal of the ms:**<br>
A lesson in reproducible analyses and workflows for evolutionary biology, separate from software package publication.

We are using a backwards design strategy to write the ms. (?)

## Introduction

Reproducibility --the extent to which consistent results are obtained when a scientific experiment is repeated [@repdef2021]-- is a key aspect for the advancement of science, as it constitutes a minimum standard to understand scientific results, to determine their reliability and generality, and eventually to build more scientific knowledge upon those results  [@king1995replication; @peng2011reproducible; @powers2019open].
Reproducibility rates in the natural sciences are low [@ioannidis2005most; @prinz2011believe], prompting concerns about a reproducibility crisis in the field [@baker2016reproducibility]. The scientific community has united to incentivize cultural changes that will improve reproducibility rates long term, such as transparency, availability, and workflow automatization, to name a few [@peng2015reproducibility].
We argue that accesibility is a key aspect that must accompany availability (Box 1) in order to achieve full workflow automatization and reproducibility. We focus on identifying factors that have specifically affected accessibility in the natural sciences, and ways researchers can address it to ensure reproducible and automatic workflows.
> [name=Emily Jane McTavish] maybe define accessibility?

We use an example in evolutionary biology. This example focuses on understanding the shared ancestry among organisms through evolutionary trees. These phylogenetic trees provide the basis to study and understand biological processes [@dobzhansky1973nothing]. Hence, improving reproducibility and availability of phylogenetic research is relevant for many aspects of biological research.
The Open Tree of Life project (OpenTree) has developed a platform that facilitates availability of results from phylogenetic research, by standardizing and storing phylogenetic data with the goal of synthesizing a single phylogenetic tree encompassing all life [@opentreeoflife2019synth].
All data in OpenTree is open access and available programmatically through its many Application Programming Interface (API) services [@opentreeAPIs].
Additionally, R packages [@michonneau2016rotl] and Python libraries [@mctavish2021opentree] have been developed as wrappers for OpenTree API services to make them available to a wider programming audience.
The R and Python OpenTree wrappers have been utilized by computer-literate individuals, to seamlessly establish reproducible workflows to use and reuse expert phylogenetic knowledge for biological research [@sanchez2019datelife] and education [@nguyen2020phylotastic; @phylotasticedtools; @galacticedtools].

The OpenTree project demonstrates that efforts to increase reproducibility and availability have also increased the baseline required computational knowledge and skills in phylogenetic research.
These computational skills requirements are likely increasing across all natural sciences.
Computing is not traditionally a core skill taught to biologists and naturalists.
However, many students are now being trained in R as a statistics and data analysis environment.
> []cite?

In order for reproducible computational tools to be adopted for research, they much be accessible to reseachers.
Data and code availability is a core requirement for reproducibility research [@peng2011reproducible; @sandve2013ten; @powers2019open].
However, the utility of data resources is limited by the technical challenges of accessing the data.
In order to motivate reproducible research, that gap needs to be bridged.
(Argument link needed here (?): Why focus on documentation next?)
In this work we focus on improving accessibility of code examples and documentation.
In particular, we identify the necessity for documentation that is written down using language that is common to the target audience to facilitate examination, application, and adoption of code by the wider audience.

We present a set of principles to generate documentation that improves accessibility of code and documentation. We applied these principles to a series of tutorials and vignettes for the OpenTree project.

## Methods

### Identifying hurdles to accesibility

Good primary documentation for code describes general usage of individual functions, the components and variables a function can take, and it should be accompanied with function usage examples on how to apply it (CITE).

As opposed to code, primary documentation is written in natural language (i.e., any known human language, e.g., English, Spanish, Chinese) and usually makes use of highly specialized computational jargon (computationally specific concepts, words, and phrases) as well as formal language, which often slows down or even obstructs examination, application, and adoption of code by external individuals.

Because primary documentation is considered a professional document, acceptance of the research by the scientific community could be reduced if a more informal language is used.

Secondary types of documentation, such as vignettes and tutorials, demonstrate additional cases of individual function usage, and describe analysis workflows in more detail, as well as function associations to generate a specific analysis and results. While secondary documentation has become more common practice, it is still often generated using highly specialized language (example).


### Adressing hurdles to accesibility: the principles

#### 1. Demonstrate integration of function usage with motivating examples

We examined primary documentation from the OpenTree API R wrapper package `rotl`.

We designed a workflow that visits as many functions as possible, while answering to uses that are most commonly requested by users of OpenTree.
By framing the use cases in highly requested tasks, the documenation follows a narrative conceptual arc, making the translation to biological use cases clear.

> [name=Emily Jane McTavish]Brief para or figure on what the motivating example is here

#### 2. Demonstrate errors and warnings thoroughly

Primary documentation focuses on demonstrating usage function with examples that work seamlessly without errors. We argue that the opposite is needed to support user adoption of reproducibile workflows: demonstrate examples that do not work as expected and exemplify ways to address them. We identify inputs that would give a wide range of warnings and errors, focusing on demonstrating these cases. This helps users to not be afraid of errors and warnings, but instead to use them to their advantage (CITE carpentries).

We also identify effects of warnings and errors downstream of the workflow.

We identify ways to evaluate inputs to know if they will produce an error, and design alternatives on what to do when faced with an error or warning, and demonstrate these alternatives.
One of the most essential skills in programming is interpreting and moving forward from errors.
Many finely honed tutorials do not trigger errors, which preculdes helping studnts to develop the tools to understand and address errors when the do encounter them, as they inevitably will!

> [name=Emily Jane McTavish]Show where you deal with an error in your tutorial
>
#### 3. Avoid jargon and expert language.

We focused on complementing the primary documentation by identifying computational concepts that were assumed or were not explained in depth.

We wrote the tutorials using informal language, explaining computational terms that are key for the workflow both at the beginning and throught the text.

We vetted the tutorials with an audience on workshops as well as individual users.

We choose examples that are charismatic for the audience.

> [name=Emily Jane McTavish]Specify what one you used!
>
#### 4. Make it stable through time.

We published the tutorials on a public, free license, free of cost, and free for use and reuse repository and persistent website.
The tutorial is available for the users to go back to it any time they need it, and to be passed on to other users.

Following the carpentries [@CITE], we created a main version of the tutorial that is updated. Versions presented on workshops are a copy from the original repository, and represent a stable and temporal snapshot of the functions and workflows presented in the tutorial.

> [name=Emily Jane McTavish] Show the page, or the layout, or something :P


#### 5. The (now) classics of computational reproducibility

Provide all information on package version and system capabilities.

> [name=Emily Jane McTavish]link to where/and how you did that

## Results

SSB workshop tutorials http://opentreeoflife.github.io/SSBworkshop/ - use of DateLife and rotl https://lunasare.github.io/ssb2020_workshop/

We explain the warnings and errors and design ways to avoid them, and detect them beforehand (i.e., before using an input that would give an error). We explain the consequences of warnings.

We designed ways to access the different elements of the outputs.

We have received emails from senior researchers thanking us for this materials, and students have been able to engage using the packages with less hep from the PIs.

## Discussion

The principles to create tutorials described here facilitate adoption of software and analysis wokflows among researchers at different academic levels, from undergrads to established researchers.

It will also help closing the gap between students that had access to computational resources (and computational training) from an early age and students that did not. Late access to computational resources and training can occur due to lack of economic resources, often ocurring in households from underrepresented communities and minorites. It can also be due to gender-biased parental and community pressures, in which males are more often encouraged to perform activities related to computers, while females are discouraged.

How to balance software acceptance VS. adoption?
These principles can be used to aide not only reproducibility, but also software adoption in the natural sciences.

Discuss: why address accessibility and not other apects of reproducibility?


## Conclusion

Making accessible reproducible workflows has several advantages:

save explanation/training time when analyses are run again by students and collaborators.

save research time for yourself when analyses are run again with more data, a different dataset, a different organism or biological model.

scientific efforts can build off of each other


### Box 1
Availability does not imply accessibility. One example I really like is the marshmallows in an office. The marshmallow bags were there, availabe for anyone to eat them. But until someone opened the bag and put the marshmallows in a tray or container, people started eating them. Maybe it was something psychological in this case. But the point is that simply sharing your code and documenting it might not be enough for the average researcher to reproduce, they'll be able to figure it out, but the time needed to do so might not be worthy for them, or might not be something they can invest in, even if it would be useful for them long term, the short term investment is too intense.
Let alone students that are just starting, it is even more difficult for them.

## References

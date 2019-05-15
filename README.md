# Mike's Fork of `contrastive` for Contrastive-PCA

For finding patterns in data subtracting out variance from a 'background' dataset.

**Original library:** [https://github.com/abidlabs/contrastive]()

**Original publication:** [Exploring patterns enriched in a dataset with contrastive principal component analysis](https://www.nature.com/articles/s41467-018-04608-8.pdf/) in *Nature Communications* (2018).


###  Fork motivation
The original `contrastive` interface hides most of the information users of packages such as `sklearn` are used to, such as the new basis vectors and their explained variance ratios. This is my attempt to modify the interface to extract this information. 

### Installing during development

During the development process use 

```
pip install -e </path/to/dir/that/contains/setup.py>
``` 
to install the current build of the project to your environment. 
 


 

